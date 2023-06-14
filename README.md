
// Calculate the number of characters in the surnameint numberOfCharacters = surname.length();

import java.util.Scanner;

public class SurnameAndAge {

    public static void main(String[] args) {
        // Create a Scanner object to read input from the user
        Scanner scanner = new Scanner(System.in);

        // Prompt the user to enter their surname
        System.out.print("Enter your surname: ");
        String surname = scanner.nextLine();

        // Prompt the user to enter their age
        System.out.print("Enter your age: ");
        int age = scanner.nextInt();

        // Calculate the number of characters in the surname
        int numberOfCharacters = surname.length();

        // Check if the age is even or odd
        boolean isEven = (age % 2 == 0);

        // Print the results
        System.out.println("The number of characters in your surname is " + numberOfCharacters);
        if (isEven) {
            System.out.println("Your current age is an even number");
        } else {
            System.out.println("Your current age is an odd number");
        }
    }
}
