
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
String product = "Laptop"
```

We can also use `System.out.println(product)` to print the value of the variable. 

```
System.out.println(name)
```

*OUTPUT*
```
Laptop
```
