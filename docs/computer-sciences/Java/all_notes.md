---
title: All Java Chapters Notes 
sidebar_position: 1
description: Learn about java programming Objects and Classes easily by following this guide.
---

<center>Chapter 13</center>

#### Abstract Classes

+ It provides abstraction layer with the support of Abstract methods. 
+ it provides implementation layer with the support of concrete methods.  
+ Abstract class is the combination of abstract methods and concrete methods. 
+ Sometimes abstract methods contains only abstract methods, sometimes only concrete methods, sometimes both or containing nothing
+ In order to design a abstract class : 

abstract class abstract_className{

}

+ Before class keyword we need to declare the abstract keyword
+ Abstract class can extenders other abstract class, class and implement interface
+ Abstract class able to initialize and declare variables
+ In abstract class we can write static,non-static blocks and constructors 


+ In abstract class we can write private and protected variables while in interface we can't
+ By default abstract classes are whatever is written by the final
+ By default abstract methods are not if you want to write one you need to declare abstract void m1(); for example
+ We can compile and execute abstract class program individually by using main method 

+ We can't instantiate the abstract class. (ex: AC obj = new AC();) we can't do this
+ 

+ An abstract method cannot be contained in a nonabstract class.
+ An abstract class cannot be instantiated using the new operator, but you can still define its constructors, which are invoked in the constructors of its subclasses.

#### Interfaces

+ Interfaces only consist of all abstract methods
+ Interface can not contain Concrete methods
+ Interface can not contain private or protected variables
+ By default interface variables are public static final 
+ By default interface methods are public abstract


#### The Comparable Interface


#### The Cloneable Interface


#### Interfaces vs. Abstract Classes