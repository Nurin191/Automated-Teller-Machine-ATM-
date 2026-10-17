import java.util.Scanner;
public class Solution {

	public static void main(String[] args) {
		// TODO Auto-generated method stub
         Scanner input = new Scanner(System.in);

	        final int PIN = 1234;
	        double balance = 1000.00;

	        int enteredPIN = input.nextInt();

	        if (enteredPIN != PIN) {
	        	System.out.println("Invalid PIN");
	            input.close();
	            return;
	            
	        }

	        System.out.println("Authentication successful!");

	        int option = input.nextInt();

	        switch (option) {
	            case 1:
	                System.out.printf("Your current balance is: RM%.2f%n", balance);
	                break;

	            case 2:
	                double deposit = input.nextDouble();
	                if (deposit > 0) {
	                	balance += deposit;
	                    System.out.printf("Successfully deposited: RM%.2f%n",deposit);

	                } else {

	                    System.out.println("Invalid deposit amount");

	                }

	                break;

	            case 3:
	            	double withdrawal = input.nextDouble();
                    if (withdrawal <= 0) {
                    	System.out.println("Invalid withdrawal amount");

	                } else if (withdrawal > balance) {

	                    System.out.println("Insufficient funds");

	                } else {

	                    balance -= withdrawal;
	                    System.out.printf("Successfully withdrew: RM%.2f%n",withdrawal);

	                }

	                break;

	            case 4:
               System.out.println("Thank You");

	                break;
                    default:
                    	System.out.println("Invalid option"); }

	}

}
