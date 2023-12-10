import java.util.*;
class Solver {
  public static void main(String[] args) 
  {

    int counter = 0; //Keeps track of iterations; initial value set to 0

    Scanner keyboard = new Scanner(System.in);
    int num; //The value of the starting integer

    System.out.print ("Enter a positive integer: ");
    num = keyboard.nextInt();
    System.out.println();
    
    System.out.println("Iteration #0: " + num);
    
    while (num != 1) //How long the program will run
    {
      if (num % 2 == 1) // If value is odd,
      {                 
        num = num * 3 + 1; // multiply by 3x + 1
        counter++; // Adds one to counter for every iteration
      }
      else // If value is odd,           
      {
        num = num / 2; // divide by 2   
        counter++; // Adds one to counter for every iteration
      }
      System.out.println("Iteration #" + counter + ": " + num); //prints every iteration
    } //close loop
    System.out.println();
    System.out.println("Total number of iterations: " + counter);
  } 
}
