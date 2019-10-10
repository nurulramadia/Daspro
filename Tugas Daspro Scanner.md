
import java.util.Scanner;

public class Scannerjava{
    public static void main(String[] args) {
        int uangKas= 50;
        System.out.println("pengeluaran KAS kelas");
        System.out.println("Sapu :");
        Scanner input = new Scanner (System.in);
        int sapu = input.nextInt();
        System.out.println("Cermin :");
        int cermin = input.nextInt();
        System.out.println("komoceng :");
        int komoceng = input.nextInt();
        int total = sapu+cermin+komoceng;
        
        System.out.println("sisa uang Kas = " + (uangKas - total) +" Ribu");
        
        
        
        
        
}
}
