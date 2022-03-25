# rango-de-edad
package rangoedad;
import java.util.*;

public class Rangoedad {


    public static void main(String[] args) {
Scanner sc= new Scanner(System.in);
int edad;
System.out.println("Dame tu edad");
edad=sc.nextInt();
if(edad>=0&&edad<=17){
    System.out.println("eres menor de edad");
}
  if(edad>=18&&edad<=59){
    System.out.println("eres mayor de edad");  
  }
  if(edad>=60&&edad<=100){
    System.out.println("eres de la tercera edad");
  }
  else
      System.out.println("No estas en el rango de edad");
  


}
       
    }
