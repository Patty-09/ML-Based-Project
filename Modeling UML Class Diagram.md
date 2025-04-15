
Practical No :06
Aim: Modelling UML Class Diagram
Problem Statement: Prediction Of Personality trait based on Handwriting Analysis.

Structural and Behavioural aspects
Developing a software system in object-oriented approach is very much dependent on understanding the problem. Some aspects and the respective models are used to describe problems and in context of those aspects the respective models give a clear idea regarding the problem to a designer. For developer, structural and behavioural aspects are two key aspects to see through a problem to design a solution for the same.

Class diagram
It is a graphical representation for describing a system in context of its static construction.
Elements in class diagram
Class diagram contains the system classes with its data members, operations and relationships between classes.

Class
A set of objects containing similar data members and member functions is described by a class. In UML syntax, class is identified by solid outline rectangle with three compartments which contain
•	Class name A class is uniquely identified in a system by its name. A textual string is taken as class name. It lies in the first compartment in class rectangle.
•	Attributes Property shared by all instances of a class. It lies in the second compartment in class rectangle.
•	Operations An execution of an action can be performed for any object of a class. It lies in the last compartment in class rectangle.
Example
To build a structural model for an Educational Organization, ‘Course’ can be treated as a class which contains attributes ‘course Name’ & ‘coursed’ with the operations ‘addCourse()’ & ‘removeCourse()’ allowed to be performed for any object to that class.
 
Figure - 1
•	Generalization/Specialization It describes how one class is derived from another class. Derived class inherits the properties of its parent class.
Example
 

Geometric_Shapes is the class that describes how many sides a particular shape has. Triangle, Quadrilateral and Pentagon are the classes that inherit the property of the Geometric_Shapes class. So the relations among these classes are generalization. Now Equilateral_Triangle, Isosceles_Triangle and Scalene_Triangle, all these three classes inherit the properties of Triangle class as each one of them has three sides. So, these are specialization of Triangle class.
Relationships
Existing relationships in a system describe legitimate connections between the classes in that system.
•	Association It is an instance level relationship[i] that allows exchanging messages among the objects of both ends of association. A simple straight line connecting two class boxes represent an association. We can give a name to association and also at the both end we may indicate role names and multiplicity of the adjacent classes. Association may be uni-directional.
Example
In structure model for a system of an organization an employee (instance of ‘Employee’ class) is always assigned to a particular department (instance of ‘Department’ class) and the association can be shown by a line connecting the respective classes.
 
•	Aggregation It is a special form of association which describes a part-whole[i] relationship between a pair of classes. It means, in a relationship, when a class holds some instances of related class, then that relationship can be designed as an aggregation.
Example
For a supermarket in a city, each branch runs some of the departments they have. So, the relation among the classes ‘Branch’ and ‘Department’ can be designed as an aggregation. In UML, it can be shown as in the fig. below
 

-Composition
It is a strong from of aggregation which describes that whole is completely owns its part. Life cycle of the part depends on the whole.
Example
Let consider a shopping mall has several branches in different locations in a city. The existence of branches completely depends on the shopping mall as if it is not exist any branch of it will no longer exists in the city. This relation can be described as composition and can be shown as below
 
-**Multiplicity **
It describes how many numbers of instances of one class is related to the number of instances of another class in an association.
Notation for different types of multiplicity:
Instance	Multiplicity
Single instance	1
Zero or one instance	0..1
Zero or more instance	0..*
One or more instance	1..*
Particular range (two to six)	2..6
Example
One vehicle may have two or more wheels

