Polymorphism

Q1: What does the word 'polymorphism' mean?
A1: The ability to have different objects (sub-classes) from a parent object(superclass) with different underlying implementations.

Q2: What does it mean when we apply polymorphism to OO design? Give a simple Java example.
A2: For example a Customer, Teacher, Pilot could all be children of a parent class Person, which means a Person object can have "many forms".

Q3: What can we use to implement polymorphism in Java?
A3: Inheritance or interfaces if possible.

Q4: How many 'forms' can an object take when using polymorphism?
A4: There is no set number of subclasses that can be created from a parent/superclass. As many as the memory can take.

Q5: Give an example of when you could use polymorphism.
A5: You can have a Car class, with subclasses such as PassengerCar, PoliceCar, Taxi, SafetyCar etc.

Composition and Aggregation

Q6: What do we mean by 'composition' in reference to object-oriented programming?
A6: An object is made by other "component" objects whose existence depends entirely on the existence of the main object.

Q7: When would you use composition? Provide a simple example in Java.
A7: Person "SuperMario" may come with a "DriverLicense" object. Such document is SuperMario's meaning its existence depends on a "SuperMario" Person object.

Q8: Give a difference between composition and aggregation?
A8: In aggregation, objects are completely independent from other objects they may be part of (Cars in a Dealership), while in composition we have a main object composed by other objects that make the main object (the Walls of a House).

Q9: What is/are the advantage(s) of using composition/aggregation?
A9: This enables a program to work with properties/methods that come with the components that make an object (an Office may come with a Computer, and such Computer has its properties and methods). This is what the SOLID principle "Single-responsibility" is about, and leads to having reusable and easier-to-read code.

Q10: When using composition, when an object is destroyed, what happens to all the objects it is composed of?
A10: The instances of the "components" objects are destroyed with the main/composite object.

Q11: When using aggregation, when an object is destroyed, what happens to all the objects it is composed of?
A11: The existence of instances of the "components" objects is independent from the existence of an object they may be part of (Singers would still exist if a MusicFestival is cancelled).