# Application Architecture, MVC Design Pattern

**1.** What are the Pillars of Object Oriented Programming (`OOP`)?
<!-- enter you answer in the space below -->
```
Abstraction
Encapsulation
Inheritance
Polymorphism

```
**2.** How would you access the `name` of the below object using the `property` variable?
```js
let staff = {
  name: "Tim",
  age: 26,
  job: "Code Monkey"
  }
let property = 'name'
```
<!-- enter you answer in the space below -->
```
let property = staff.name

```
**3.** What is Encapsulation?
<!-- enter you answer in the space below -->
```
hiding internal entities of an object

```
**4.** What does the S stand for in the `SOLID` principles?
<!-- enter you answer in the space below -->
```
single responsibility

```
**5.** What the difference between a `class` and an instance of a `class`?
<!-- enter you answer in the space below -->
```
an instance of a class is the class but with its base values or or paramaters hidden, allows you to customize the class without changing the actual values of the original class

```
**6.** What is a `Proxy` object?
<!-- enter you answer in the space below -->
```
a proxy object is kind of like a new instance of an object, it allows us to redefine operations of an object without having to have mutliple of the same objects doing the same thing

```

**7.** What is the purpose of the `MVC` pattern?
<!-- enter you answer in the space below -->
```
adheres to the solid principles, it lets us seperate the view and the logic, giving each component their own tasks

this also allows us to update the views and the logic separate from one another

```
**8.** What is the job of the `Controller` in the `MVC` Pattern?
<!-- enter you answer in the space below -->
```
it is the intermediary of the model and the view, handles user interaction, and changes for the model and view
can also be thought of as a waiter

```

**9.** What is the job of the `Service` in `MVC`?
<!-- enter you answer in the space below -->
```
handles the logic
can be thought of as a cook
```
**10.** What is the job of the `Model` in `MVC`?
<!-- enter you answer in the space below -->
```
the model houses the data of the "recipes" we are making

```
