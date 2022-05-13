# ManavKasa

Manav Kasa Programı
Java ile kullanıcıların manavdan almış oldukları ürünlerin kilogram değerlerine göre toplam tutarını ekrana yazdıran programı yazın.

Meyveler ve KG Fiyatları

Armut : 2,14 TL
Elma : 3,67 TL
Domates : 1,11 TL
Muz: 0,95 TL
Patlıcan : 5,00 TL

import java.util.Scanner;

public class Main {

    public static void main(String[] args) {

        double armut_fiyat=2.14, elma_fiyat=3.67, domates_fiyat=1.11, muz_fiyat=0.95, patlican_fiyat=5.0;
        double armut, elma, domates, muz, patlican, total;

        Scanner input = new Scanner(System.in);

        System.out.println("Armut kac kilo : ");
        armut = input.nextDouble();
        armut = armut*armut_fiyat;
        System.out.println(armut);

        System.out.println("Elma kac kilo : ");
        elma = input.nextDouble();
        elma = elma*elma_fiyat;
        System.out.println(elma);

        System.out.println("Domates kac kilo : ");
        domates = input.nextDouble();
        domates = domates*domates_fiyat;
        System.out.println(domates);

        System.out.println("Muz kac kilo : ");
        muz = input.nextDouble();
        muz = muz*muz_fiyat;
        System.out.println(muz);

        System.out.println("patlican kac kilo : ");
        patlican = input.nextDouble();
        patlican = patlican*patlican_fiyat;
        System.out.println(patlican);

        total = armut + elma + domates + muz + patlican;

        System.out.println("Toplam :" + total);
    }
}



