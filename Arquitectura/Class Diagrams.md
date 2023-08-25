These are notes for [Learning UML 2.0. Chapter 4.](https://learning.oreilly.com/library/view/learning-uml-2-0/0596009828/ch04.html#learnuml2-CHP-4-SECT-4.1)

Classes are the most common UML diagram, as it is strictly tied to how we model [[Object Oriented Programming]]. Classes are similar to [[Objects]], but the main difference is that an [[object]] can be understood as the instance of a class. This means that objects are unique things with their respective states and characteristics, meanwhile classes serve as their blueprints.

Classes tend to have at least:
1. [[State]] infomation for each [[object]]
2. Behavior of the [[object]]
Classes are linked to [[state]] and behavior in [[O.O.P.]]
## [[Abstraction]]
Classes also represent a certain level of [[abstraction]]. This level of abstraction depends on the context. Guitar example: The class of a guitar for a factory requires simple things like strings, and tuning. Meanwhile, the class of a guitar for a repair shop might need the scratches that the guitar has.
## [[Encapsulation]]
In O.O.P., an [[object]] is something that contains both [[state]] and behavior, meaning that it contains data ([[Attributes]]) and instructions ([[Operations]]). It encapsulates both, meaning that it shouldn't have [[operations]] or [[attributes]] that are related to each other.
## [[Visibility]]
A class can and must selectively reveal its [[operations]] and data to other classes, as this facilitates abstraction. 

## Static [[Attributes]] or [[Operations]]
Sometimes you want all instances of the same class (objects) to share the same attribute or operation. In this case this should be static.
Static attributes or operations are shown in UML by underlining them.
![[Pasted image 20230824215947.png]]
