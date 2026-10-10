
import java.util.Scanner;

public class MovieTicket {
    public static void main(String[] args) {

        Scanner input = new Scanner(System.in);

        // Ask for movie information
        System.out.print("Movie Title: ");
        String movieTitle = input.nextLine();

        System.out.print("Ticket Price: ");
        double ticketPrice = input.nextDouble();

        System.out.print("Number of Tickets: ");
        int numberOfTickets = input.nextInt();

        // Calculate the total cost
        double totalCost = ticketPrice * numberOfTickets;

        // Display the receipt
        System.out.println("=== MOVIE TICKET RECEIPT ===");
        System.out.println("Movie Title: " + movieTitle);
        System.out.println("Ticket Price: " + ticketPrice);
        System.out.println("Number of Tickets: " + numberOfTickets);
        System.out.println("Total Cost: " + totalCost);

        input.close();
    }
}
