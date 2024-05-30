# Weightconverter
package javaprojectfirstpackage;

import java.util.Scanner;

public class WeightConverter {

	public static void main(String[] args) {
		// TODO Auto-generated method stub
		Scanner sc = new Scanner(System.in);
		System.out.print("Enter The number of KG:");
		double Weight_In_KG = sc.nextDouble();

		double pounds = Weight_In_KG * 0.453592;
		System.out.println("After the convertion from Kg TO pounds:" + pounds+" [Ibs]");
		double Tons = Weight_In_KG / 1000;
		System.out.println("After the convertion from Kg TO Tons:" + Tons+" [t]");

	}

}
