# DaireAlan
### Java-101 Daire Alan Hesaplama
  (www.patika.dev)

import java.util.Scanner;

public class DaireAlan {
    public static void main(String[] args) {

        double r,alan,aci;
        double pi = 3.14;




        Scanner girdi=new Scanner(System.in);

        System.out.print("Lütfen dairenin yarıçapı giriniz: ");
        r = girdi.nextDouble();

        System.out.print("Lütfen merkez açı ölçüsünü giriniz: ");
        aci = girdi.nextDouble();
        
        alan = (pi*(r*r)*aci)/360;
        System.out.println("Dairenizin Alanı: "+alan);



    }
    }
