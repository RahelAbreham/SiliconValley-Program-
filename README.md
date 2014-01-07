SiliconValley-Program-
======================
public static void main(String[] args) {

	ArrayList<Integer> list33 = new ArrayList<Integer>();
	float sum = 0;	
	for (int i = 0; i <= 1000; i++) {
		if(i%3 == 0){
			list33.add(i);
			sum = sum + (2*i);
		}
		else if(i%5 == 0){
			list33.add(i);
			sum = sum + (2*i);
		}
		else {
			sum = sum + i ;
		}
	}
     
	System.out.println( " The total sum is" + " : "+ sum );
	
}


}
