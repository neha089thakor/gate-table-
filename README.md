# gate-table-import java.util.Scanner;

public class Main
{
    public static void main(String []args)
    {
        int a1 = 0 , b1 = 0;
        int a2 = 0 , b2 = 1;
        int a3 = 1 , b3 = 0;
        int a4 = 1 , b4 = 1;

        System.out.println("-------------------------------------------------");
        System.out.println("| A | B | A' | B' | A' + B' | (A'+B')' |   AB   |");
        System.out.println("-------------------------------------------------");

        if(a1==0 & b1==0)
        {
            int a01=1,b01=1,ab01=1,ab001=0,ab1=0;
            System.out.println("| " +a1+ " | " +b1+ " | " +a01+ "  |  " +b01+ " |    " +ab01+ "    |     " +ab001+ "    |    " +ab1+ "   | " );
        }

        System.out.println("-------------------------------------------------");

        if(a2==0 & b2==1)
        {
            int a02=1,b02=0,ab02=1,ab002=0,ab2=0;
            System.out.println("| " +a2+ " | " +b2+ " | " +a02+ "  |  " +b02+ " |    " +ab02+ "    |     " +ab002+ "    |    " +ab2+ "   | " );
        }

        System.out.println("-------------------------------------------------");

        if(a3==1 & b3==0)
        {
            int a03=0,b03=1,ab03=1,ab003=0,ab3=0;
            System.out.println("| " +a3+ " | " +b3+ " | " +a03+ "  |  " +b03+ " |    " +ab03+ "    |     " +ab003+ "    |    " +ab3+ "   | " );
        }

        System.out.println("-------------------------------------------------");

        if(a4==1 & b4==1)
        {
            int a04=0,b04=0,ab04=0,ab004=1,ab4=1;
            System.out.println("| " +a4+ " | " +b4+ " | " +a04+ "  |  " +b04+ " |    " +ab04+ "    |     " +ab004+ "    |    " +ab4+ "   | " );
        }

        System.out.println("-------------------------------------------------");
        System.out.println("Hence prove that (A'+B')' = AB ");





    }

}
