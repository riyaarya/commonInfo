
# 1: What are Java Oop concept?

# 2: what is the meaning of polymorphism?

# 3: what is function overloading?
Functon overloading  is polymosrphsihm concept in which there may be number of function with same name but they are invoked based on parameter passed to them. For example 
the abive two function have same name sum but one sums the two integere values and second gives sum of three.

# 4: what is function overriding?
Overridding is a polymorphism concept in which subclass has  function with same name  as like super class. But when we inherit the supar class method gets overridden by subclass method.

examople see this 

class  car
{
    public void cartypeprint()
   {
 system.out.println(“Car Audi”);
   }
}
class vehicle extends car
{

  public void cartypeprint()
    {  
    system.out.println(“Car BMW”);
}
}

now if we create the object of class vehicle and we call cartypeprint it will print  “Car BMW”


# 5: What is inheritance?
Inheritnavce is concpet or methododlogy using whihc  we inhrit the propety of one class into other class. For example if we say bmw is class and vehicle is a class here we see that bmw if type vehicle so it will inhrit the propety of vehicle 
bmq inhrit priperty pf vehicle
in Java achieve this usng extends keyword 
<subclass> extends <super class>
This improves the code reusabbility  

# 6: Can you write example of inheritance?

# 7: What is constructor in Java?
Constructor are the mthod which has same name as class name. Java automatically creates an construtor  evenif we dont define them. Its invoked when an object of class is initiated. There are basically two type of cinstrctor 
1: default is one  created by even if we dont create that or we define but we dont pass any parameters just to initiae object.
2: Parameterses is the function or constructor with parameteres it can have multile parametheres 

# 8: What is the use of constructor?
TO INITIATE THE OBJECT  basically but this is also used to set some dafault setting if we work with framwoek like reeader me kiya tha work book ke liye path setting
OK G

# 9: How many constructor we can define in java?
We can define as many as we want but all should have either fifferent parameter or return type (constructor overloading)

# 10: Does Java provide constructor by its own or you have to write?
Yes it provideds even if we dont define one wich is invoked when we create objec

are wehen we do like this

Classname object name = new Classname()// this the one is invoking right when we are cteateing object
dekho what i mean agar hum calss me koi constructor nai banate na to java khud ek constructor banata hai we generat dont see right?
Ha
to wo kab inovike hota ha jab hum object create karte hai 
object kaise create karte hai 

Classname object name = new Classname()/
aise hi to karte hai na 
ha
to yahi to bol raha hoon ye jo classname() hai ye us construcyor ko call kar rah ahai 
pahle copiler dekhta hai agar ye define hai class me tho thuk nahi to ye java wala use kar leta hai


# 11: What is abstract class?

# 12: what is the abstract method?

# 13: What is the use of abstract class?

# 14: What is interface?

# 15: Why use interface over abstract class?

# 16: What is exception handling in java?

Exception handling a methodology using which we try to minimize the unwanted behaviour or control the unwanted behavior of the program or software. Java provides exception handling class which has defined set of exceptions as well as we can alos define the special exception or condition.

17: What is try and catch?
Using Try and Catch we handle the exception in java. Basically the code that can possibly throw error we put in Try block and if that exception or error occured then its catch by Catch block.

Example:

try
{
num=i/m;// if m is 0 it will catch divide by 0 exception 

}catch(Exception e)
{

}

# 18: Write the general syntax for try and catch?
try{
/*
Code that can possibly throw error
*/
}catch()
{
/*
code that will perform damage control or do something when the exception is caught
*/
}

# 19: What is the exception name if file is not able to locate?

When the program is not able to locate file or file path is wrong it will Senf FileNotFoundException

# 20: What is use of static?

Static is keyword in java which is used to memory management. Any variable, method or class can be defined static, once its defined static its allocated only once and then from that memory only its used. 

For better example see this page and the image at down - https://www.javatpoint.com/static-keyword-in-java

# 21: What is Final and finally in java?

Final is the keyword which is used to make any variable, method or class constant or rigid state which have restricts the normal use 

- if the variable is defined as Final and assigned a value its value can not be changed in any condition
- if a method is defined Final it can not be overridden when extendsto other class, meaning lets say if the class  has a method like this

class Bike{  
  final void run(){System.out.println("running");}  
}  
     
class Honda extends Bike{  
   void run(){System.out.println("running safely with 100kmph");}  
     
   public static void main(String args[]){  
   Honda honda= new Honda();  
   honda.run();  
   }  
}  
in this even if we extends the class bike and then define run again in this method, the run of super class cant be overridden.

- if the class is defined Final we cant not extend that class

final class Bike{}  
  
class Honda1 extends Bike{  
  void run(){System.out.println("running safely with 100kmph");}  
    
  public static void main(String args[]){  
  Honda1 honda= new Honda1();  
  honda.run();  
  }  
} 

above code will give error

--------------------------------------------------------------
On the other hand finally is adjacent block to try catch which runs without being effected from what happened in the try block or the Catch block.
try
{

}Catch()
{
}
finally
{
}


# 22: When we use super keyword in java?
Super keyword is used in the subclass when two methods are overridden. Its used to get the access or functionality of overridden method of super class.

Example:
class Animal
{  
    void eat()
    {
    System.out.println("eating...");
    }  
}  
class Dog extends Animal
{  
void eat(){System.out.println("eating bread...");}  
void bark(){System.out.println("barking...");}  
void work(){  
super.eat();  
bark();  
}  
} 

# 23: Write an example of array list in java?
Array list is the collection similar data elements which can be defined by the following way -
ArrayList<Integer> possibleValues2 =
    new ArrayList<Integer>(Arrays.asList(1,2,3,4,5,6,7,8,9));
    
    or
 ArrayList<Integer> possibleValues2 = new ArrayList();

# 24.what is encapsulation
ecapsulation is cncept of wrapping of data and method in single unit. IN java we achive this  by defining class where all the variables and method resides in class

# 25.What is class
Class is unit which defines the bahviour of the object for example if we see an example a dog is an object bloonging to animal class
whihc can have its behavioru such as color, number of les kind of stuff
or for example bmw cars are object of class vehicle 
so class defines behaviour of vehicle
in java its an encapsulation concept where the bahvor is in form of data and method and wrappedin unitcalled class

# 27.what is object
object is the instance of a class. For example if we define object of the class BMW class like bmw_1 it is an instance of class which has its state and property.
