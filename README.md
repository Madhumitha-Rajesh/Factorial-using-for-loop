# Factorial-using-for-loop
import java.util.Scanner;

public class FactorialForLoop {
    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);
System.out.print("Enter a number to calculate its factorial: ");
int num = scanner.nextInt();
long factorial = 1;
// Calculate factorial using for loop
for (int i = 1; i <= num; i++) {
      factorial *= i; // Multiply current number
        }
System.out.println("The factorial of " + num + " is: " + factorial);
scanner.close();
    }
}

output-

Enter a number to calculate its factorial: 5
The factorial of 5 is: 120
