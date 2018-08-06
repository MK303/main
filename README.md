# main
TASK 1

package main;

import java.util.Scanner;

public class task1 {

	public static void main(String[] args) {
		Scanner sc = new Scanner(System.in);
		System.out.println("Input number here");
		int a = sc.nextInt();

		int f = a % 100000 / 10000;
		System.out.println(f);

		int e = a % 10000 / 1000;
		System.out.println(e);

		int d = a % 1000 / 100;
		System.out.println(d);

		int c = a % 100 / 10;
		System.out.println(c);

		int b = a % 10;
		System.out.println(b);

		sc.close();

	}

}
