# Car
Java program that creates a car, owner, and carDemo class. User is prompted to provide information about 2 vehicles. Both vehicles accelerate twice, and brake 4 times. 
Provided with this assignment is the class definition for a class named Owner.  I have provided the interface for this class.  You MUST use the class I have provided and not create your own.

Q1 Create a class called Car based on the information given below.  Create appropriate constructors, accessors and mutator methods.

The class has the following attributes:
•	carName:  This is a String field that stores a name given to the car
•	yearModel: This is an int field that stores the Car’s year of manufacture
•	make: This is a String object that holds the make of the car
•	speed:  This is an int field that holds the car’s current speed
•	mileage:  This is an int field that holds the car mileage
•	owner: This is an object of the Owner class 
•	totalMileage – This is a int value that represents the total mileage for ALL  Car objects together
In addition to the accessor and mutator methods, the class has the following additional methods:
•	accelerate:  If the owner of the Car object is a safe driver, then this method should add 5 to the speed each time it is called.  If the owner of the Car object is a rash driver, then this method should add 10 to the speed each time it is called.  The ownType attribute of the Owner class indicates whether a Owner object is “safe” or “rash”.
•	brake:  This method should reduce the speed by 5 each time it is called regardless of the owner type.  If the speed is already zero, an appropriate message should be displayed.
•	compare: This method accepts another Car object as input, compares their speeds and displays one of the following messages as appropriate:
o	Car1 is faster than Car2
o	Car1 is slower than Car2
o	Car1 and Car2 are both the same speed
Replace Car1 and Car2 with the names of the first and the second car. 
•	toString: a method that prints out all Car data including owner name.

Finally write a program that tests the class. Your driver program must allow the user to provide input for two Car objects.  After each Car object is created, the program must print the Car object data and also display the totalMileage value.  Call the accelerate method on each car two times displaying the speed of the car after each method call.  Then call the compare method of the first Car object.  Finally call the brake method a four times on each Car object displaying the speed after each call. Then call the compare method of the first Car object.  
