

    
import java.util.Scanner;

public class Hello {
    public static void main(String[] args) {
        Scanner input = new Scanner(System.in);
        
        System.out.print("Item: ");
        String Item = input.nextLine();
        
        System.out.print("price: ");
        double price = input.nextDouble();
        
        System.out.print("Quantity: ");
        int quantity = input.nextInt();
        
        double total = quantity * price;
        
        System.out.println("===RECEIPT===");
        System.out.println("Item: " + Item);
        System.out.println("Quantity: " + quantity);
        System.out.println("Total: " + total);
    }
}
