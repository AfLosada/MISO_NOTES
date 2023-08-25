In large systems, it is hard to jump directly from class diagrams to code. This is because it may be easier to model higher level abstractions of functionality that can be manageable, reusable and swappable.

It is composed by [[Component]]s

Component Diagrams are tied to [[interface]] notation. 
![[Pasted image 20230824224903.png]]

## Class Realization
Moreover, due to interface notation, you can specify which class is helping a component realize an interface.   
![[Pasted image 20230824225128.png]]
![[Pasted image 20230824225133.png]]
![[Pasted image 20230824225203.png]]

Component diagrams can also include [[Ports]], these serve to provide detail to the level of abstraction and componentization of your program.
You can also include [[delegation connectors]] to help specify what interface is realized by which class in your component
If you want to get even deeper you can also use [[assembly connectors]] between components. This one helps connect interfaces that are realized and provided by a couple of components.


