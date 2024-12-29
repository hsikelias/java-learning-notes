# The Way Java Works

1.) Source: Create a source doc, use an established protocol( java lang)
2.) Compiler: This runs your document, checks for errors and compiles only if everything is correct
3.) Output(code): The compiler creates a new doc, coded into Java **bytecode**
4.) Virtual Machines : Physical machines, virtual machine reads and run the bytecode.

# Code structure in Java

![image](https://github.com/user-attachments/assets/244533df-2d36-4bee-9a31-f4827cd0cd9d

A **source code file**( with the .java extension) holds on class. The class represents a piece of your program. The class must go within a pair of curly braces.

**class** : 
```
public class Dog {
}
```
A class has one or more **methods**.Your methods must be declared inside a class

**method** : 
```
public class Dog {
  void bark() {
 }
}
```
Within the curly braces of a method, you write instructions for how that method should be perfomed.
So its basically a set of statements😛
**statements**
```
public class Dog {
  void bark() {
 }
}
```

![image](https://github.com/user-attachments/assets/081bb15a-098f-4a6b-8181-a1ba30d27dfe)

The main() method is where your program starts running.

**1. do something** : declarations, assignments, method calls, etc.
**2. do something again and again** : Loops: for and while.
**3. do something under this condition** : if/else tests.


# Conditional branching

```
class IfTest {
public static void main (String [] args) {
   int x = 3;
   if (x ==3) {
        System.out.println("x must be 3");
     }
   System .out.println( " This runs no matter what");
 }
} ## Output: x must be 3
              This runs no matter what
```

So the above code runs only if the x is 3, if u cange the value of x.. the condition( x ==3) becomes false. So it all depends on the value of x. The only thing that wont change is the "runs no matter what thing".

But we can add an **else** to our condition, to give ourself more options.

```
class IfTest2 {
public static void main (String [] args) {
   int x = 2;
   if (x ==3) {
        System.out.println("x must be 3");
     } else {
   System.out.println( "x is NOT 3");
    }
      System.out.println("This runs no matter what");
 }
}
     ## Output: x is NOT 3
        This runs no matter what
```







