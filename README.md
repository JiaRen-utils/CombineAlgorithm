# CombineAlgorithm
This is an algorithm to solve the combination of several numbers

从给定的M个对象去取N个对象，得到 C(m,n)个数 = (m!)/(n!*(m-n)!) 的结果，并可现实所有结果。
并得到结果的个数。

# 用法实例
   /**
  	 * 用法实例
  	 * @param args
  	 * @throws Exception
  	 * @since megagao 2016-5-20 下午8:11:05
  	 */
  	public static void main(String[] args) throws Exception{
  		Integer[] a = new Integer[]{1,2,3,4,5,6};
  		CombineAlgorithm ca = new CombineAlgorithm(a,3);
  		
  		Object[][] c = ca.getResult();
  		for(int i = 0; i<c.length; i++){
  			System.out.println(Arrays.toString(c[i]));
  		}
  	}
