# CA2.timeTask
Repository for CA2 submissions
/*
 * To change this license header, choose License Headers in Project Properties.
 * To change this template file, choose Tools | Templates
 * and open the template in the editor.
 */
package ca2.timetask;

/**
 *
 * @author Z
 */
public class CA2TimeTask {
static void renanMethod(){
    /**
     *
    * @author Renan Gomes - Student Number: 2020295
    */
    System.out.println("This is Renan submission");
}

static void alessandroMethod(){
    /**
    *
    * @co-author Alessandro Souza - Student Number: 2020365
    */
    System.out.println("This is ALessandro's collaboration to the project.");

	{
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

static void lucasMethod(){
    /**
    *
    * @author Lucas Matteis - Student Number: 2020495
    */
    System.out.println("This is Lucas's commit.");
    }  
  
   String nameSurname, gender, name, line = "";
        int age;

        try {
            /*
            Reads file
            */
            Scanner scanner = new Scanner(new File("people.txt"));
            File arquivos[];
File diretorio = new File("people1.txt");
arquivos = diretorio.listFiles();

for(int i = 0; i < arquivos.length; i++){
   //leia arquivos[i];
}

            /*
            Reads variables from the file above
            */
            nameSurname = scanner.nextLine().toString();                        
            age = Integer.parseInt(scanner.nextLine());
            gender = scanner.nextLine().toString();

            
            /*
            Verifys gender and writes a line for future file
            */
            if (gender.length() > 1) {
                System.out.println("Error! invalid gender");
            } else if (gender.equals("M")) {
                line = "Mr";
            } else if (gender.equals("F")) {
                line = "Ms";
            } else if (gender.equals("T")) {
                line = "Mx";
            }

            if (verifyName(nameSurname)) {
                line +=  getSurname(nameSurname); 
                line += ",";
                name = getFirstName(nameSurname);
                line += getFirstInitial(name)+"\n";   
            } else {
                System.out.println("Invalid name");
            }
            if (age >= 0 && age <= 100) {
                line += status(age);
            } else {
                System.out.println("Invalid age");
            }
            BufferedWriter outputFile = new BufferedWriter(new FileWriter("myOutputFile.txt"));
            System.out.println(line);
            outputFile.write(line);
            outputFile.close();
            
        } catch (Exception e) {
            System.out.println("Fatal error!!!");
        }

    public static void main(String[] args) {
        renanMethod();
        alessandroMethod();
	lucasMethod();
        
    
    }
    package method;

/**
 *
 * @author Adson
 */
public class Method {
    static void 
    
    /**
     * @param args the command line arguments
     */ System.out.println("My name is Adson, this is my part");
}
    public static void main(String[] args) {
        System.out.println("Part 4");
        
    }
    
}

}
