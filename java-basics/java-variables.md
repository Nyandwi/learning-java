
## Java Variables

A variable is a location in memory that store data. A variable is given a name and it is assigned values to it. 

Here is an example of variable in Java:

```
int num = 3;
```

From the above variable definition, `num` is the variable name and its type is `int` and we assigned the value `3` to it.

Generally, the type of variable can be: 

* `int` that stores integers(or definite numbers) without decimals such as 1,2,3,4,5, 10,130,...
* `String` that stores text such as `"Hello World"`. String values are inside the double quotes`(" This is a string")`...No single quote like Python that accept both. 
* `float` that decimal numbers, such as 1.2, 3.4, 3.0, etc...
* `char` that stores single characters such as `'x'` or `'X'`. Char must be surrounded by single quotes. 
* `boolean` that stores binary values: `true` or `false`.


### Creating or Declaring a Variable

***Format***

```
variable_type variable_name = value;
```
Like we saw above, variable type can be a `String` or `int` or `float` or `boolean`. 

Le's create a string variable.

```
String product = "Laptop";
```

We can also use `System.out.println(product)` to print the value of the variable. 

```
System.out.println(product);
```

*OUTPUT*
```
Laptop
```

We can also customize the println output
```

System.out.println("The name of the product is " + product);
```

*OUTPUT*
```
The name of the product is Laptop
```

In the above example, you can replace the `"The name of the product is " ` with any variable name but it must be a string type since you are adding it to the string. Same thing is true for integers. 

```
int x = 1;
int y = 2;
System.out.println(x + y); // Print the value of x + y
```

### Overwriting Variables and Final Variables

A variable in Java can be overwritten. So if you defined any variable earlier, you can assign it again any value. The first value will be replaced with the new assigned value. 

If you want to declare a variable that can't overwritten, you can use `final` keyword. Such variable defined with final keyword is immutable(ie. read only).

```
final int number = 10;
// number is a constant/final variable. Changing it will cause error. You don't want that!
number = 20; //ERROR
```

So far, we have only declared integers and texts. We can also declare booleans or floats in the same way. 

```
boolean myBool = true;
float decimalVal = 10.3;
char letter = 'F';
```

You can also declare many variables at once.

```
int x = 5; y = 10; z = 45;
```


