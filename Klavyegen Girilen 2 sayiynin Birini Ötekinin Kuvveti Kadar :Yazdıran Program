import java.util.Scanner;

class App{
    public static void main(String[] args) {
        Scanner kb = new Scanner(System.in);
        System.out.println("A sayisini giriniz");
        int a = Integer.parseInt(kb.nextLine());
        System.out.println("B sayisini Giriniz");
        int b = Integer.parseInt(kb.nextLine());

        System.out.printf("A sayisinin B. değeri %d%n",NumberUtil.pow(a,b));
    }
}

class NumberUtil{
    public static int pow(int a,int b)
    {
        b = Math.abs(b);
        int result = 1 ;
        for (int i = 0 ; i < b ; ++i)
            result *= a;
        return result;

    }
}
