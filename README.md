# loan-calculator
loan calculator
public class Main{
public static void main(Strings[] args){
 Scanner sc =new Scanner(System.in);
     int amount= sc.nextInt();
     float interest = 0.1f;
     int month= sc.nextInt();
        for (int i = 0; i < month; i++) {
            float n= amount*interest;
            amount= (int) (amount-n);
            amount++;

        }
        System.out.println(amount);
        }
      }
