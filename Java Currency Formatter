import java.util.*;
import java.text.*;

public class Solution {
    
    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);
        double payment = scanner.nextDouble();
        scanner.close();
        
        //Creating new Locale for India as it does not have predefined Locale.
        Locale INDIA = new Locale("en","IN");
        
        // Write your code here.
        NumberFormat c = NumberFormat.getCurrencyInstance(Locale.CHINA);
        NumberFormat f = NumberFormat.getCurrencyInstance(Locale.FRANCE);
       NumberFormat i = NumberFormat.getCurrencyInstance(INDIA);
        NumberFormat us = NumberFormat.getCurrencyInstance(Locale.US);
        
        System.out.println("US: " + us.format(payment));
        System.out.println("India: " + i.format(payment));
        System.out.println("China: " + c.format(payment));
        System.out.println("France: " + f.format(payment));
    }
}
