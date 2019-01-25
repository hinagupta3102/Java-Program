# Java-Program
package labassignment1;

import java.util.Scanner;

import javax.swing.JOptionPane;

public class LabAssignment1 {
	
	public static void main(String[] args) {
		Scanner scanner = new Scanner(System.in);
		System.out.println("Enter an operation");
		String operation = scanner.nextLine();
		//TODO Put the Scanner input code here
		//Sample code for the ADD input
		
		
		
		if (operation.equals( "ADD" )){
	int int1 = Integer.parseInt( JOptionPane.showInputDialog("Enter first number to add") );
	int int2 = Integer.parseInt( JOptionPane.showInputDialog("Enter second number to add"));
	
	int sum = int1 + int2;
	
	JOptionPane.showMessageDialog(null, "The sum is: " + sum); }
		
	
	//TODO Declare a variable of type int. Name it "sum" and set the value as the ADD operation
	
		if(operation.equals("SUBTRACT")){
	long long1 = Long.parseLong( JOptionPane.showInputDialog("Enter first number to subtract"));
	long long2 = Long.parseLong( JOptionPane.showInputDialog("Enter second number to subtract"));
	
	long sub = long1 - long2;
	
	JOptionPane.showMessageDialog(null,  "The answer to the subtraction operation is:" + sub);
		}
			
		if(operation.equals("MULTIPLY")){
	float float1 = Float.parseFloat( JOptionPane.showInputDialog("Enter first number to multiply"));
	float float2 = Float.parseFloat( JOptionPane.showInputDialog("Enter second number"));
	float mul = float1 * float2;
	
	JOptionPane.showMessageDialog(null, "The multiplication operation is" + mul);
	
		}
			
		if(operation.equals("DIVIDE")){
	double double1 = Double.parseDouble( JOptionPane.showInputDialog("Enter first number to divide"));
	double double2 = Double.parseDouble( JOptionPane.showInputDialog("Enter second number to divide"));
	
	double div = double1 / double2;
	
	JOptionPane.showMessageDialog(null, "The division operation is:" + div);
		}
	
	System.exit(0);
	
	//JOptionPane.showMessageDialog(null, "The answer is");
	//JOptionPane.showMessageDialog(null,"The answer is");
	}
	
	//TODO Add codes for the other operations here.
	//Name result variables as: "difference" (for subtraction),
	// "product"(for multiplication), "quotient" (for division)

	//End and exit the app
	
	}
