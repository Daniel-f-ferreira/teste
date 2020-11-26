# teste

package home.work4;

import java.util.Scanner;


/**
 *
 * @author Daniel Freitas Ferreira
 * //This program has the purpose of classifying the user in 3 categories. 
 * //New to vote, hardworking and retired.
 */
public class HomeWork4 {


    public static void main(String[] args) {
        // Get some input from the user and make some decisions based on the input
        
        Scanner myKB = new Scanner(System.in);
        int userNum; // user inform the age
        
        System.out.println("How Old Are You?");
        
        try{
            userNum = myKB.nextInt(); //reads the next int from the scanner
            
                 
            if ( userNum < 18) {
            
                // if the age is less than 18 will print (To Young to Vote) 
                System.out.println("To Young to Vote");
            }
             if (userNum  >= 18 ){
                 // if the age is more than 18 and less than 66 will print ( work Hard)
                System.out.println("Work Hard");
            }
             
             if (userNum >=65 ){
            
                System.out.println("Enjoy Your Reteirment  ");
            }
            
            
                               
        }
        catch (Exception e){
            //i
            System.out.println("");
        }
        
    }
    
}
