# Cost-of-Balloon
# Hackerearth Problem Solution in java

import java.util.Scanner;
public class costofballoon {

	public static void main(String[] args) {
        Scanner scan = new Scanner(System.in);
         int n = scan.nextInt();
         String str[] = new String[n];
        for (int i = 0; i < str.length; i++) {
			
        	String s = scan.nextLine();
		}
        String res = "";
        for (int i = 0; i < str.length-1; i++) {
        	for (int j = i+1; j < str.length; j++) {

    			if ((i+j) % 2 == 0) {
    				  res = "valid";
    			}
    			else {
    				res = "invalid";
    			}
			}
        	
		}
        System.out.println(res);
	}

}
