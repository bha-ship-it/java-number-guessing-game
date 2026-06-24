import java.util.Random;
import java.util.Scanner;

public class NumberGame {

    public static void main(String[] args) {

        Random random = new Random();
        Scanner scanner = new Scanner(System.in);

        int secretNumber = random.nextInt(100) + 1; // Generates number between 1 and 100
        int guess;
        int attempts = 0;

        System.out.println("==================================");
        System.out.println("      Welcome to Number Game");
        System.out.println("==================================");
        System.out.println("Guess a number between 1 and 100");

        do {
            System.out.print("Enter your guess: ");
            guess = scanner.nextInt();
            attempts++;

            if (guess > secretNumber) {
                System.out.println("Too High! Try again.");
            } 
            else if (guess < secretNumber) {
                System.out.println("Too Low! Try again.");
            } 
            else {
                System.out.println("Correct! You guessed the number.");
                System.out.println("Total Attempts: " + attempts);
            }

        } while (guess != secretNumber);

        scanner.close();
    }
}
