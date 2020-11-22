# CA2.timeTask
Repository for CA2 submissions

/*
*To change this license header, choose license Headers in Project Properties.
*To change this template file, choose Tools Templates 
*And open the template in the editor.
*/

package CA2_TimeTask;

/**
*
*@author Jeison
*/

public class CA2_TimeTask{

    static void renanMethod(){
        /**
        *
        *@author Renan Gomes - Student Number : 2020295
        */
        System.out.println("This is Renan Submission");
    }

    static void alessandroMethod(){
        /**
        *
        *@co-author Alessandro Souza - Student Number : 2020365
        */
        System.out.println("This is Alessandro's collaboration to the project.");
    

		Scanner myKB = new Scanner(System.in);
    
    int userAge;                                               
    
        System.out.println("Hello there, how old are you?");
        
        try{                                                    
        
    userAge = myKB.nextInt();           
    
    if (userAge <18){                   
        System.out.println("Sorry, you're too young to vote!");
        }
    
    else if (userAge >= 18 && userAge <= 66){                 
        System.out.println("Are you working hard?");
        }
       
    else {                                                      
        System.out.println("Enjoy retirement!");
        }
    
        }catch (Exception e){ 
                    
        System.out.println("Please, enter only whole numbers!"); 
        } 

     }
    
    static void jeisonMethod(){
        /**
        *@author Zhen Hao Ng -  Student Number :2014433
        */
        System.out.println("This is Zhen Hao Ng task submission");
    }    
    
    /**
    *@param args the command line arguments 
    */

    public static void main(String[] args){
        jeisonMethod();
        renanMethod();
        alessandroMethod();
    }
}
