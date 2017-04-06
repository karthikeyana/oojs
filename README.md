# Object-Oriented-JavaScript

## Programming (OOP):

*	 Object, method, and property
*	 Class
*	 Encapsulation
*	 Aggregation
*	 Reusability/inheritance
*	 Polymorphism

### Object:

  An object is a representation of a "thing" (someone or something), and this representation is
expressed with the help of a programming language. Another name for "object" is "instance".

#### ex:
*	 Objects are most often named using nouns (book, person, and so on)
*	 Methods are verbs (read, run, and so on)
*	 Values of the properties are adjectives

### Classes:

In real life, similar objects can be grouped based on some criteria.You can create different objects using the same class, because a class is just a template, while the objects are concrete instances based on the template.

#### ex:
  A hummingbird and an eagle are both birds, so they can be classified as belonging to some made up
Birds class.

### Encapsulation:

An encapsulation is information hiding. Aspect of information hiding is the visibility of methods and properties.In some languages, objects can have public , private , and protected methods
and properties. In JavaScript, all methods and properties are public.

#### ex:
  The same thing happens in OOP when your code uses an object by calling its methods. It doesn't
matter if you coded the object yourself or it came from some third-party library; your code doesn't need to know how the methods work internally.

### Aggregation:

   Combining several objects into a new one is known as aggregation or composition. It's a powerful way to separate a problem into smaller and more manageable parts (divide and conquer).

#### ex:
  A Book object can contain (aggregate) one or more Author objects, a Publisher object, several Chapter objects, a TOC (table of contents), and so on.

### Inheritance:

Inheritance is an elegant way to reuse existing code. classes inherit from other classes, but in JavaScript, since there are no classes, objects inherit from other objects.

#### ex:
  You can have a generic object, Person , which has properties such as name and date_of_birth , and
which also implements the functionality walk , talk , sleep , and eat . Then, you figure out that you need another object called Programmer . You could re-implement all the methods and properties that Person has, but it would be smarter to just say that Programmer inherits Person , and save yourself some work. The Programmer object only needs to implement more-specific functionality, such as the writeCode method, while reusing all of the Person object's functionality.

### Interface:

The method name is the same, but when called on the new object, the method behaves differently. This way of redefining how an inherited method works is known as overriding.

### Polymorphism:

  This ability to call the same method on different objects and have each of them
respond in their own way is called polymorphism.

#### ex:
  A Programmer object inherited all of the methods of the parent Person object. This means that both objects provide a talk method, among others. Now imagine that somewhere in your code there's a variable called Bob , and it just so happens that you don't know if Bob is a Person object or a Programmer object. You can still call the talk method on the Bob object and the code will work.
