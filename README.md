# v-cut-kitle-indeksi-hesaplama

import java.util.Scanner;

public class indeks{

   public static void main(String[] args){
   
   double boy , kilo;
   
   Scanner inp = new Scanner(System.in);
   
   System.out.println("boyunuzu metre cinsinden giriniz:");
   boy = inp.nextDouble();
   
   System.out.println("lütfen kilonuzu giriniz:);
   kilo = inp.nextDouble();
   
   double indeks = kilo / (boy*boy);
   
   System.out.println("vücut kitle indeksiniz:" + indeks);
   
   }
   
 }
