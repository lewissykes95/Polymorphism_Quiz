# Polymorphism_Quiz

1. What does the word 'polymorphism' mean?

Polymorphism is when there are ‘many classes’ that are related to each other and perform a single task


2. What does it mean when we apply polymorphism to OO design? Give a simple Java example.

In Java we can use Polymorphism to relate classes together using Inheritance. This can be done for example with a super class and sub-classes of that super class.

3. What can we use to implement polymorphism in Java?

We can use Inheritance of classes or we can use Interfaces 

4. How many 'forms' can an object take when using polymorphism?

As 'many forms’ as we would like as there is endless amount of sub-classes we can create of the parent. 


5. Give an example of when you could use polymorphism.

	For example: 
  We could use an a Farm Program
	An Animal Class could act as a super class and Dog and Cat could be a sub-class of Animal. The constructor of Animal and the methods are extended to the   sub-classes.
  
  
  Composition and Aggregation
  
  6. What do we mean by 'composition' in reference to object-oriented programming?
  
  Composition is a design technique which uses an ’Is-Part-Of’ relationship. This is achieved by using instance variables of 	classes and can only be     used with the parent class. 
  
  7. When would you use composition? Provide a simple example in Java.
  
  We would use composition when we create a Parent class that holds sub classes as variables. 
	
  For example: 
	We could use a Car class that uses sub-classes Engine and GearBox as variables in the Car class. 
  
  
  8. Give a difference between composition and aggregation?
  
Composition uses sub-classes as part of the parent class and can only be used within an instance of the parent class. Aggregation uses classes with the ‘has-a’ relationship which can also be accessed outside the parent class and can live independently from the parent class. 

  9. What is/are the advantage(s) of using composition/aggregation?
	
  Advantages of Composition: 
	- re-use existing code
	- Easier to change the implementation of containing objects.
	- has a strong association
  
  
  Advantages of Aggregation: 
	- Loosely coupled
	- shorted software development time
	- re-use existing code
  
  
  
 10. When using composition, when an object is destroyed, what happens to all the objects it is composed of?
 
 In Java if the object is destroyed the objects that composes it are also removed as they are no longer in use. 
 
 
 11. When using aggregation, when an object is destroyed, what happens to all the objects it is composed of?
 
 As the objects are loosely coupled the remaining objects will not be removed as they are independent from the parent class. 
	
  
  
  
