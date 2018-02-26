# MultipleInheritance
Achieving multiple inheritance in java

Q. What is inheritance?
A. Inheritance is the one of the OOPS concept to reuse the code by extending the parent(super) class to child(sub) class, so all properties and behavior of super class will be inheritaed to subclass.

Q. Does java supports multiple inheritance?
A. NO, Java doesn't support multiple inheritance but as per document of Java we can achive multiple inheritance in java by using Interfaces.
That's fine when it is implementation level, we can define a parent(super) classes as Interfaces and then we can implement any no'of interfaces in the class. so we can achieve multiple inheritance by using interfaces.
But if you have already implemented classes and wanted to inherit to child class, Java doesn't support the multiple inheritance so we can't extend two or more classes in the child class.
For example you have two classes:
1. Horse.java
2. Eagle.java
Now, if you want to inherit these two classes in your child class to make 'FlyingHorse.java' you can't directly extend those two classes on FlyingHorse.java class.
So, what you can do is : Create objects for Horse and Eagle classes and then make use of them as shown in the FlyingHorse.java



