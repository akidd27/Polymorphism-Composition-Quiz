# Polymorphism & Composition Homework - Quiz
​
# Polymorphism
​
1. What does the ___word___ 'polymorphism' mean?
The notion that objects can be of many different types; from "poly" - many, and the mathematical concept of morphism - translation of types/structures.
​
2. What does it mean when we apply polymorphism to OO design? Give a simple Java example.
An object could be created as an instance of a particular class (1 type), but through interfaces and/or inheritance, be referenced as other types.
​
3. What can we use to implement polymorphism in Java?
Interfaces and inheritance.
​
4. How many 'forms' can an object take when using polymorphism?
Infinitely many forms.
​
5. Give an example of when you could use polymorphism.
A car could be modelled as an instance of class Car, but through inheritance, be referenced as parent-type Vehicle in a list of Vehicle objects.
​
​
# Composition and Aggregation
​
6. What do we mean by 'composition' in reference to object-oriented programming?
Composition is when one object is composed of other objects, e.g. a Car could be composed of Wheels, Engine etc.

7. When would you use composition? Provide a simple example in Java.
To separate concerns and allow flexibility. E.g. one Car object may use one type of Wheel object, while another Car object may have different Wheels.
​
8. Give a difference between composition and aggregation?
With composition, the children exist independently of the parent.
​
9. What is/are the advantage(s) of using composition/aggregation?
​
10. When using composition, when an object is destroyed, what happens to all the objects it is composed of?
They no longer exist.

11. When using aggregation, when an object is destroyed, what happens to all the objects it is composed of?
The composing objects still exist.
