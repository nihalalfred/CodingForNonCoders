# Lesson 5 : A Bit More About Code

### Namespaces

Name spaces gives us a way to organise things both:

- logically
- physically

within our codebase.

< Insert Image 1>

< Insert Image 2>

< Insert Image 3>

### Types and variables

**Type** is a logical construct, it’s a thing.

It is similar to class but much more fundamental.

There are different kinds of types.

- Primitive types: Basic to the complier or the language you are dealing with.

**Variables** are buckets/places where you store information of a type.

**Example**: If Brittany Spaniel is a Type, MyDogGus would be a Variable of a type Brittany Spaniel

< Insert Image 4>

### Visibility/Accessibility

- Generally speaking we want to only expose things that are very critical.

If expose everything we could run into significant quality issues.

< Insert Image 5>

< Insert Image 6>

- You would only need to declare the visibility/accessibility of a variable at the class level, however if you are declaring a variable within a method you don’t need to state explicitly whether it is private like the example above for int count.

- Also we need to keep in mind that any variable we declare within a code of block can’t be accessed outside it. For example int index is throwing an error when we were trying to access it outside the for loop.

***If statement*** → Allows you to branch program behaviour based on a condition.

***Condition*** → A test or a state.

< Insert Image 7>


< Insert Image 8>

```
// = is assignment

// == is equivalency test

```

< Insert Image 8>

***Switch statements***: → Helps you write multiple if-else statements in a more concise fashion. 

***Loops***: → Repeat actions based on conditions

< Insert Image 9>

**Off-by-one error** → Most notorious bug in software development.

< Insert Image 10>

https://www.goodreads.com/book/show/4268826-growing-object-oriented-software-guided-by-tests