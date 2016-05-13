# PrimeNumberIdentification
import java.util.Scanner;

public class PrimeIdentification {
	public static void main(String[] args) {
		
		int n; int m = 2; 
		
		Scanner in = new Scanner(System.in); // Java scanner scans up to 8 numbers
		System.out.println("Enter a number to check if it is prime:\n");
		n = in.nextInt();
		
		if (n < 0) {
			System.out.println("Negative numbers are not prime!");
		}
		
		if (n == 0) {
			System.out.println("0 is not a prime number");
		}
		
		if (n == 1) {
			System.out.println("1 is not a prime number");
		}
		
		if (n == 2) {
			System.out.println("2 is a prime number");
		}
		
		if (n > 2) {
			while (n % m != 0) {
			m++;
				}
				
			}
			
			if (n == m) {
				System.out.println(+n+ " is a prime number");
			}
			
			if (m != n) {
				System.out.println(+n+ " is not a prime number");
				System.out.println("It is divisible to "+m);
			}
		}
	}
