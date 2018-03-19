
1: What are Java Oop concept?

2: what is the meaning of polymorphism?

3: what is function overloading?
Functon overloading  is polymosrphsihm concept in which there may be number of function with same name but they are invoked based on parameter passed to them. For example 
the abive two function have same name sum but one sums the two integere values and second gives sum of three.

4: what is function overriding?
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


5: What is inheritance?
Inheritnavce is concpet or methododlogy using whihc  we inhrit the propety of one class into other class. For example if we say bmw is class and vehicle is a class here we see that bmw if type vehicle so it will inhrit the propety of vehicle 
bmq inhrit priperty pf vehicle
in Java achieve this usng extends keyword 
<subclass> extends <super class>
This improves the code reusabbility  

6: Can you write example of inheritance?

7: What is constructor in Java?
Constructor are the mthod which has same name as class name. Java automatically creates an construtor  evenif we dont define them. Its invoked when an object of class is initiated. There are basically two type of cinstrctor 
1: default is one  created by even if we dont create that or we define but we dont pass any parameters just to initiae object.
2: Parameterses is the function or constructor with parameteres it can have multile parametheres 

8: What is the use of constructor?
TO INITIATE THE OBJECT  basically but this is also used to set some dafault setting if we work with framwoek like reeader me kiya tha work book ke liye path setting
OK G

9: How many constructor we can define in java?
We can define as many as we want but all should have either fifferent parameter or return type (constructor overloading)

10: Does Java provide constructor by its own or you have to write?
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


11: What is abstract class?

12: what is the abstract method?

13: What is the use of abstract class?

14: What is interface?

15: Why use interface over abstract class?

16: What is exception handling in java?

17: What is try and catch?

18: Write the general syntax for try and catch?

19: What is the exception name if file is not able to locate?

20: What is use of static?

21: What is Final and finally in java?

22: When we use super keyword in java?

23: Write an example of array list in java?

24.what is encapsulation
ecapsulation is cncept of wrapping of data and method in single unit. IN java we achive this  by defining class where all the variables and method resides in class

25.What is class
Class is unit which defines the bahviour of the object for example if we see an example a dog is an object bloonging to animal class
whihc can have its behavioru such as color, number of les kind of stuff
or for example bmw cars are object of class vehicle 
so class defines behaviour of vehicle
in java its an encapsulation concept where the bahvor is in form of data and method and wrappedin unitcalled class

27.what is object
object is the instance of a class. For example if we define object of the class BMW class like bmw_1 it is an instance of class which has its state and property.
