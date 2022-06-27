# yildizlarlaElmasYapimi

Java'da döngüler kullanarak yıldızlar ile elmas yapınız.

    *    
   ***    
  *****  
 *******  
*********  
 *******  
  *****  
   ***  
    *


 public static void main(String[] args) {

        Scanner input = new Scanner(System.in);
        System.out.println("Yildiz olusuturulacak Basamak Sayisini Giriniz : ");
        int n = input.nextInt();


        for (int i = 0; i <= n; i++) {

            for (int j = 0; j < (n - i); j++) {
                System.out.print(" ");
            }
            for (int k = 1; k <= (2 * i + 1); k++) {

                System.out.print("*");
            }
            System.out.println(" ");

        }
        for (int s = n; s > 0; s--) {

            for (int l = (n - s);l> 0; l--) {
                System.out.print(" ");
            }
            for (int m =(2 * s - 1);m>=1; m--) {

                System.out.print("*");
            }
            System.out.println(" ");


        }
    }
