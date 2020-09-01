# Polymorphism & Composition Homework - Quiz

# Polymorphism

1. What does the ___word___ 'polymorphism' mean?
##### A. The word 'polymorphism' means 'many forms'.

2. What does it mean when we apply polymorphism to OO design? Give a simple Java example.
##### A. In Java, an example would be using a related parent or abstract class to create an instance of another class (Vehicle vehicle = new Car()).

3. What can we use to implement polymorphism in Java?
##### A. Abstract classes could be used as you wouldn't initialise an abstract class itself, but with one of it's sub-classes.

4. How many 'forms' can an object take when using polymorphism?
##### A. 2, that of it's own class and also the class/interface it extends or implements from.

5. Give an example of when you could use polymorphism.
##### A. You could use polymorphism if you wanted to populate an array or ArrayList with related objects (ArrayList< Vehicle > vehicles (cars, motorbikes etc.)).



# Composition and Aggregation

6. What do we mean by 'composition' in reference to object-oriented programming?
##### A. Composition in OOP is when an object of a class is initialised as a property of a class and does not exist outside it.

7. When would you use composition? Provide a simple example in Java.
##### A. If you had a class called House, it would likely be made up of other class objects that wouldn't exist without the House class, such as Window or Door (House(ArrayList< Window >,ArrayList< Door >) ).

8. Give a difference between composition and aggregation?
##### A. A Difference in an aggregation example could be when the class objects used in another class can exist outside that class as well.

9. What is/are the advantage(s) of using composition/aggregation?
##### A. The advantages include more flexibility between classes and less reliance on each other, not having to inherit unused props or methods and will be less likely to be severly effected by future changes.

10. When using composition, when an object is destroyed, what happens to all the objects it is composed of?
##### A. The objects it was composed of are also destroyed.

11. When using aggregation, when an object is destroyed, what happens to all the objects it is composed of?
##### A. The objects it was composed of will still exist outside of the destroyed object.
