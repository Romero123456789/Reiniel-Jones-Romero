import java.util.Scanner; // import the scanner

public class Main {
	public static void main(String[] args) {
		System.out.println("Welcome to PHINMA \n");
		System.out.println("Sign Up");
	    Scanner myObj = new Scanner(System.in);
		
		//String Variables
		String firstName;
		String middleName;
		String lastName;
		String age;
		String address;
		String dateofBirth;
		
		
		//Enter your personal information
		System.out.println("First Name: ");
		firstName = myObj.nextLine();
		
		System.out.println("Middle Name: ");
		middleName = myObj.nextLine();
		
		System.out.println("Last Name: ");
		lastName = myObj.nextLine();
		
		System.out.println("Age: ");
		age = myObj.nextLine();
		
		System.out.println("Address");
		address = myObj.nextLine();
		
		System.out.println("Date of Birth: " );
		dateofBirth = myObj.nextLine();
		
		System.out.println("\n============================================== \n");
		
		System.out.println("Student Name is: " + firstName + middleName + lastName);
		System.out.println("Age: " + age);
		System.out.println("Address: " + address);
		System.out.println("Date of Birth: " + dateofBirth);
		
		
		
	}
}