# Dik-Ucgende-Hipotenus-Bulma

import java.util.Scanner;

public class Main { public static void main(String[] args) {

int kenar1, kenar2;
double kenar3; 
Scanner inp = new Scanner(System.in);

System.out.println(" Birinci kenarin uzunlugunu girin:");
kenar1 = inp.nextInt();

System.out.println(" Ikinci kenarin uzunlugunu girin:");
kenar2 = inp.nextInt();

kenar3=Math.sqrt((kenar1*kenar1)+(kenar2*kenar2));
System.out.println("Hipotenus:" +kenar3);

    double cevre = (kenar1+kenar2+kenar3);
    double u = cevre / 2;
    double alan = Math.sqrt(u*(u-kenar1)*(u-kenar2)*(u-kenar3));
    
    System.out.println("Ucgenin Cevresi : " + cevre);
    System.out.println("Ucgenin Alanı : " + alan);
    }
}
