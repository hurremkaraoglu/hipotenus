# hipotenus

import java.util.Scanner;

public class hipotenus {
    public static void main(String[] args) {
        // Değişkenleri oluşturalım
        int a, b;
        double c;

        // Kullanıcıdan verilerimizi alalım
        Scanner girdi = new Scanner(System.in);
        System.out.println("1. Kenarı Giriniz : ");
        a = girdi.nextInt();
        System.out.println("2. Kenarı Giriniz : ");
        b = girdi.nextInt();

        c = Math.sqrt((a*a) + (b*b));
        System.out.println("Hipotenüs : " + c);

    }
}
