# Lesson 6 : Object Oriented Programming and Libraries
### OOP Fundamentals

**Inheritance**

Example:

Dog inherits from  Animal and will pull down the behaviours, methods, properties

**Encapsulation**

- understanding where data is kind of protected, where it’s accessible
- Encapsulation sort of ties in with abstraction.

**The concept of Encapsulation is** 

- We are restricting giving direct access but rather we are allowing to do whatever logic we determine we want to to make sure the internal state of those things are always protected.
- We want to give some sort of access but only throw allowed means.
- One way to expose this access is via a concept called ***Properties***.

< Insert Image 1>

- Same name as the variable but using a different casing which is **CamelCase** instead of **snakeCase** 🙂

- Using **get {}** and **set{}** blocks within **Properties** you can return the existing value or write a new value to that variable.

> Important note to keep in mind is whenever you are allowing to write to an existing variable we should always have a sanity check to ensure incorrect/not allowed values are not being written incorrectly.
>

< Insert Image 2>

- Here in the above example we are checking for the value by this if else flow control statement which will throw an error if the value is negative.

### Libraries

< Insert Image 3>

- Other names for libraries: Packages, DLLs etc.

- Libraries in **dotNet** is managed via **NuGet** package manager.

