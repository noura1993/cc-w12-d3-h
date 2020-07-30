# Polymorphism & Composition Homework - Quiz

# Polymorphism

1. What does the ___word___ 'polymorphism' mean?
- Is a concept by which we can perform a single action in different ways.


2. What does it mean when we apply polymorphism to OO design? Give a simple Java example.
-It means that when we have more than one class inherets from one parent.
for example:
if we have Person class and 3 child classes inherets from this class like doctor, engineer and webDeveloper, so when we make a new instance from a child class we will make it with type Person and in the implementation when we call a method from parent it should call the correct class.  


3. What can we use to implement polymorphism in Java?
-We can implement polymorphism by two types 
compile-time polymorphism and runtime polymorphism. We can perform polymorphism in java by method overloading and method overriding.


4. How many 'forms' can an object take when using polymorphism?
-Polymorphism is a method in which a class can exist in multiple forms.


5. Give an example of when you could use polymorphism.
-smae answer for Q.2.



# Composition

6. What do we mean by 'composition' in reference to object-oriented programming?
-Composition is one of the fundamental concepts in object-oriented programming. It describes a class that references one or more objects of other classes in instance variables. This allows you to model a has-a association between objects. You can find such relationships quite regularly in the real world
  

7. When would you use composition? Provide a simple example in Java.
-For ex: Zoo has list of animals, animal can be abstract class implemented by cat, tigger, etc.. 

8. What is/are the advantage(s) of using composition?
-make us use same class with different implementations.

9. When an object is destroyed, what happens to all the objects it is composed of?
-wouldn't destroy. except the instance is created inside this class.