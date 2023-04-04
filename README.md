# ass1
import java.util.*;
class Main
{
    public static void multipleif(int b)
    {
        if(b>10)
        {
            System.out.println(b + " is greater than 10");
        }
         if(b<100)
        {
            System.out.println(b + " is lesser than 100");
        }
         if(b<0)
        {
            System.out.println(b + " is a negative number");
        }
    }
    public static void elseifladder(char c)
    {
        if(c=='a')
        {
            System.out.println(c + " is a vowel");
        }
        else if(c=='e')
        {
            System.out.println(c + " is a vowel");
        }
        else if(c=='i')
        {
            System.out.println(c + " is a vowel");
        }
        else if(c=='o')
        {
            System.out.println(c + " is a vowel");
        }
        else if(c=='u')
        {
            System.out.println(c + " is a vowel");
        }
        else
        {
            System.out.println(c + " is a consonant");
        }
    }
    public static void multiif_elseif (int a)
    {
        if(a>=0 && a<10)
        {
           System.out.println(a +" is a single digit number ");
        }
        if(a>9 && a<100)
        {
           System.out.println(a +" is a double digit number");
        }
        if(a>99 && a<1000)
        {
           System.out.println(a +" is a triple digit number ");
        }
    }
    public static void main (String[] args)
    {
        Scanner sc = new Scanner (System.in);
        System.out.print("enter a number");
        int x = sc.nextInt();
        multipleif(x);
        System.out.print("enter a character");
        char ch = sc.next().charAt(0);
        elseifladder(ch);
        System.out.print("enter a number");
        int y = sc.nextInt();
        multiif_elseif(y);
    }
   
}
