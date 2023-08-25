
`<<component>>`

A component is an encapsulated, reusable and replaceable part of your software.
EX: Loggers, JSON parsers or shopping carts.

Components tend to be higher level abstractions that are reusable and replaceable. This means that they tend to use other classes or components to do its job. 

Components are typically accessed through interfaces.
When components are actually a very large system they can be understood as `<<[[subsystem]]>>` [[subsystem]]s.

Components **need** to be loosely coupled, meaning that they are interact with others through [[provided interfaces]] and [[required interfaces]].