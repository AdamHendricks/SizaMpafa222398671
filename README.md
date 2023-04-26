
package javaapplication1;
import java.util.Scanner;
/**
 *
 * @author SIZA M
 */
public class JavaApplication1 {

    /**
     * @param args the command line arguments
     */
    double average;
    int perc;
    double selectionmark;
    public static void main(String[] args) {
        Scanner kbd= new Scanner(System.in);
        
        System.out.println("Enter subject percentage 1:");
        int percentage1 = kbd.nextInt();
        System.out.println("Enter subject percentage 2:");
        int percentage2 = kbd.nextInt();
        System.out.println("Enter subject percentage 3:");
        int percentage3 = kbd.nextInt();
        System.out.println("Enter subject percentage 4:");
        int percentage4 = kbd.nextInt();
        System.out.println("Enter subject percentage 5:");
        int percentage5 = kbd.nextInt();
        System.out.println("Enter subject percentage 6");
        int percentage6 = kbd.nextInt();
        
        double averag = (  percentage1+percentage2+percentage3+percentage4+percentage5+percentage6)/6;
System.out.println(" Matric average "+( + percentage1+percentage2+percentage3+percentage4+percentage5+percentage6)/6);

if (averag>=70)
{System.out.println("You've met the minimum NSC average requirements for BEng 4yr");
        } 
if (averag<70)
    System.out.println("You failed to meet the minimum NSC average requirements for BEng 4yr");

        System.out.println("Enter Mathematics percentage:"); 
        int Mathematics = kbd.nextInt();
        int math= Mathematics;
       
if (math>=70)
{System.out.println("You've met the minimum Mathematics NSC percentage requirements for BEng 4yr");}
else{
 System.out.println("You failed to meet the minimum Mathematics NSC percentage requirements for BEng 4yr");
}
        System.out.println("Enter Physical Sciences percentage:");
        int PhysicalSciences = kbd.nextInt();
        int physics= PhysicalSciences;
if (physics>=60)
{System.out.println("You've met the minimum Physical Sciences NSC percentage requirements for BEng 4yr");}
else{
    System.out.println("You failed to meet the minimum Physical Sciences NSC percentage requirements for BEng 4yr");
}
double selectionmark = math + physics +(6*averag);
System.out.println("Selection mark:"+ selectionmark);
double selection= selectionmark;
if (selection>=620)
{System.out.println("You have a GOOD CHANCE to ADMISSION  on Engineering programmes.");}
else{
    System.out.println("Your chances to admission on Engineering programmes are slim. ");
}

}
}


    
    
    
