# C# Fundamentals


**1.** What is the purpose of a `namespace`?
<!-- enter you answer in the space below -->
```
THe place where the names of types functuions and variables get put
```
**2.** What is the difference between a `class` and a `struct`?
<!-- enter you answer in the space below -->
```
Structure doesn't support inheritance and but a class does
```
**3.** What is the method that returns an instance of a class, yet it has no return type?
<!-- enter you answer in the space below -->
```
Constructor???  Not sure.

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
The fact that it is stated as "public" makes it accessible to the user

p.s. I am not seeing a ? #4

```
**6.** In the example what is `string` an indication of?
<!-- enter you answer in the space below -->
```
That that start() is going to bring back a sting object
```
**7.** In the example what is `abstract` preventing?
<!-- enter you answer in the space below -->
```
hies the internal details and show only the functionality
```
**8.** In the example what is the purpose of `virtual`?
<!-- enter you answer in the space below -->
```
Overides the base class member 

```
**9.** Name four access modifiers:
<!-- enter you answer in the space below -->
```

Private  -  public  -  Protected  -  Internal

```
**10.** If you set a class or method to private, what can access it?
<!-- enter you answer in the space below -->
```
Only the code in the same class 
```