import java.util.Scanner;

public class Main {
    public static void main(String[] args) {
        int a, b, select;


        Scanner input = new Scanner(System.in);
        System.out.println("ilk sayiyi yazin : ");
        a = input.nextInt();

        System.out.println("ikinci sayiyi yqazın : ");
        b = input.nextInt();

        System.out.println("1 =toplama\n2 = çıkarma\n3 = çarpma\n 4 =bölme");
        System.out.println("seçiniz : ");
        select = input.nextInt();

        switch (select) {

            case 1:
                System.out.println("toplam : " + (a + b));
                break;
            case 2:
                System.out.println("çıkarma" + (a - b));
                break;
            case 3:
                System.out.println("çarpma:" + (a * b));
                break;
            case 4:
                System.out.println("bölme:" + (a / b));
                break;

            default:
                System.out.println("geçgersiz seçim.");


        }
    }
}
