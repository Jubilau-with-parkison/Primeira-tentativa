# Primeira-tentativa
o scanner não fui eu que fiz 

import java.util.Scanner;

public class Main {
    public static void main(String[] args){

        Scanner sc = new Scanner(System.in);
        System.out.println("Coloque uma temperatura em Celsius: ");
        int temperature = sc.nextInt();
        int result = 0;
        result = (temperature * 9/5) + 32;
        System.out.println("Em Fareihaints: " + result);
        sc.close();
    }
}
