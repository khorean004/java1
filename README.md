# java1
package ders1;

import java.util.Locale;
import java.util.Scanner;

public class ders1{
	public static void main(String[] args) {
 
		System.out.println("bir sayi giriniz");
Scanner scan = new Scanner(System.in);
scan.useLocale(Locale.KOREAN);
double a= scan.nextDouble();
System.out.println("a nin degri"+a);
	
	}
	

}
