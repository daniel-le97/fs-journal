# C# Fundamentals


**1.** What is the purpose of a `namespace`?
<!-- enter you answer in the space below -->
```
a namespace is used to organize code and declare related code
```
**2.** What is the difference between a `class` and a `struct`?
<!-- enter you answer in the space below -->
```
structures are public in nature and classes are by default private

```
**3.** What is the method that returns an instance of a class, yet it has no return type?
<!-- enter you answer in the space below -->
```
void method
```
## Example 1
```c#
abstract class Car
{
  ...
  public virtual string Start()
  {
    return "Vroooom";
  }
}
```
**5.** In the example what is the access modifier of the `Start()` method?
<!-- enter you answer in the space below -->
```
public

```
**6.** In the example what is `string` an indication of?
<!-- enter you answer in the space below -->
```
the type of the return
```
**7.** In the example what is `abstract` preventing?
<!-- enter you answer in the space below -->
```
its preventing class car to not be an actual full class but rather a base class that will be inherited

```
**8.** In the example what is the purpose of `virtual`?
<!-- enter you answer in the space below -->
```
indicates that it can be overridden by a class that inherits it

```
**9.** Name four access modifiers:
<!-- enter you answer in the space below -->
```
public,
internal,
private,
async,
virtual


```
**10.** If you set a class or method to private, what can access it?
<!-- enter you answer in the space below -->
```
only the class or other methods within the class can access it

```