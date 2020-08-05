# Abstraction 
Knowing high level charachteristics without getting bogged down in the details

### Data Abstraction
We know what data can do  
We dont worry how it does that

# Abstract Data Type(ADT)
Defines a particular data structure in terms of data and operations 
Offers an interdace of the objects(instances of ADT)

### ADT consists of
- Declaration of data
- Declaration oof operations
- Encapsulation of data and operations: data is hidden from users and can be manipulated only by means of operations

> eg. if int is a data structure it can have add and substract as the methods. (Python libraries are implemented in C++)

### Why Abstract

- Specify the operations of the data structures and leave the implemetation details later
- many many different ADTs
- High level languages often provide built in ADTs

> Get your data structures correct first and the rest of the program will write itself  
~ Davids Johnson

#### Benifits of ADT

- Manufacturer Benifits
	- easy to modify, maintain
	- profitable
	- reusable (reusability is one of the most important part of code)
- CLient Benifits
	- simple to use, understand
	- familier
	- cheap
	- component\-based

> How well are ADTs supported in C?
The C language dosen't enforces the use of the ADTs interface and the hiding of its implementation.

#### C++ and OOP

C++ is a superset of C with added futures to support object oriented programming

C++ offers STL (Standard Templates Library) providing a st generic data structures which allow programmers to easily implement standard data structures like queues, stacks

#### ADT vs OOP

- ADTs are not a part of a programming language  
- They are implemented by a programmer to solve a particular problem or some class of problem  
- In OOP, an ADT can be easily modeled as a class  
- ADT is not the same as OOP  
- Classes in OOP offer more features than ADTs:  

```java
import java.util.ArrayList;
public class MyClass{
	public static void main(String[] args) {
		ArrayList <Integer> myNumbers = new ArrayList<Integer>();

		myNumbers.add(10);
		myNumbers.add(15);
		myNumbers.add(20);
		myNumbers.add(25);

		System.out.println(myNumbers);
		// this will print outour array [10,15,20,25]
	}
}
```
Such data type is not in C language
