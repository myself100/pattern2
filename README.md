# pattern2

import java.util.Scanner;
public class pattern {

	public static void main(String[] args) {
		// TODO Auto-generated method stub

		Scanner s=new Scanner(System.in);
		int n=s.nextInt();
		for(int i=1;i<=n;i++) {
			for(int j=1;j<=i;j++) {
				System.out.print((char)(j+96));
			}
			System.out.println();
		}
	}

}

output::   5                                /////when n is 5
a
ab
abc
abcd
abcde
