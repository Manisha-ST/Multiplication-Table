# Multiplication-Table

public class MultiplicationTable {
    public static void main(String[] args) {
        int number = 9; // Fixed number for the multiplication table


    System.out.println("Multiplication Table for " + number + ":");


// Generate the multiplication table
        for (int i = 1; i <= 10; i++) {
            System.out.println(number + " x " + i + " = " + (number * i));
        }
    }
}

OUTPUT:
Multiplication Table for 9:
9 x 1 = 9
9 x 2 = 18
9 x 3 = 27
9 x 4 = 36
9 x 5 = 45
9 x 6 = 54
9 x 7 = 63
9 x 8 = 72
9 x 9 = 81
9 x 10 = 90
