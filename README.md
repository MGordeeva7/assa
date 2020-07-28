# java


import java.util.Scanner;
 
public class MyClass {
 
    public static void main(String[] args) {
 
        double a, b, c, result;
        a = getNextNumber();
        System.out.println("Первое число: " + a);
 
        b = getNextNumber();
        System.out.println("Второе число: " + a);
 
        c = getNextNumber();
        System.out.println("Третье число: " + a);
 
        result = a * b * c;
        System.out.println(result);
    }
 
    public static double getNextNumber() {
        double result;
        Scanner scanner = new Scanner(System.in);
        result = scanner.nextDouble();
        scanner.close();
        return result;
    }
}
