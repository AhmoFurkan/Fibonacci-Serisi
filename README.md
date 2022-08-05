# Fibonacci-Serisi
Fibonacci serisi, her sayının kendinden önceki ile toplanması sonucu oluşan bir sayı dizisidir. Bu şekilde devam eden bu dizide sayılar birbirleriyle oranlandığında altın oran ortaya çıkar, yani bir sayı kendisinden önceki sayıya bölündüğünde altın orana gittikçe yaklaşan bir dizi elde edilir. 

Fibonacci dizisi, 0'dan başlar ve sonsuza kadar. Her rakam, bir önceki rakamla toplanır. Elde edilen sonuç rakamın sağ tarafına yazılır. Fibonacci dizisinin ilk on sayısı şu şekildedir:  9 Elemanlı Fibonacci Serisi : 0 1 1 2 3 5 8 13 21 34

    import java.util.Scanner;

    public class Main {
    public static void main(String[] args) {
        Scanner inp = new Scanner(System.in);
        System.out.print("Eleman sayısını giriniz :");
        int number = inp.nextInt();
        int a = 0, b = 1, total =0;

        for (int i = 1; i <= number; i++) {

            total = a + b;
            System.out.println(a + "+" + b + "=" + total);

            a = b;
            b = total;

            System.out.println();
        }
     }
    }
   ![image](https://user-images.githubusercontent.com/107626332/183039153-dd3f68a1-0564-4f4d-9415-58331deca90a.png)
https://app.patika.dev/ahmetfurkan
