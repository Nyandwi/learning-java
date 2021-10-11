
### Java Data Types

Data types denotes the type of the data that can be stored in a given variable. 

Every variable should be created before use, and should specify its type. That is the reason why Java is referred to as statically-typed programming language. 

Take an example: 

```
int num;
```
`int` is the type of the variable `num`. 

In Java, there are two main types of data types: 
* Primitive data types that are: `byte`, `short`, `int`, `long`, `float`, `double`, `boolean`, `char`.
* No primitive data types such as `String`, `Arrays`, `Classes`.


### Primitive Data types

Primitive data types are the most data types in Java and are the building block of data manipulation. They specify the size and type of a given variables. 

Below is a quick overview of the basic or primitive data types in Java. 

| Data Type      | Default Value | Default Size | Description | 
| ----------- | ----------- |  ----------- | ----------- |
| `byte`      | 0       |  1 byte       | Stores whole numbers from -128 to 127      |
| `short`   | 0        |  2 bytes        | Stores whole numbers from -32,768 to 32,767      |
| `int`   | 0        |  4 bytes        | Stores whole numbers from -2,147,483,648 to 2,147,483,647      |
| `long`   | 0L       |  8 bytes        | Stores whole numbers from -9,223,372,036,854,775,808 to 9,223,372,036,854,775,807      |
| `float`   | 0.0f        |  4 bytes        | Stores fractional numbers. Sufficient for storing 6 to 7 decimal digits      |
| `boolean`   | false        |  1 bit       | Stores true or false      |
| `char`   | '\u0000'        |   2 bytes       | Stores a single character/letter or ASCII values      |
| `double`   | 0.0d        |   8 bytes      | Stores fractional numbers. Sufficient for storing 15 decimal digits  |


Here are some examples: 

```
int myNum = 100000; // integer or whole number
char myLetter = 'F' // Character..Must be in single quote
boolean myBool = true; // Boolean
byte myByte = 100; // Byte
short myNum = 5000; // Short
long myNum = 15000000000L; // Long
float floatNum = 5.4f; // Floating point number
double myNum = 19.99d; // Double...Safe to use double than floats because it has precision of about 15 digits, the precision of float is 6 to 7 digits. 
String message = "Hello, Sam"; // String is non primitive type....must be in double quote.
```

You can perform mathematical operations on numbers. More on operations later. 
Below is how to declare a variable name with its appropriate type and assign it a value. 

```
char myLetter = 'A';
boolean isJavaFun = true;
System.out.println(myLetter); // OUTPUT: 'A'
System.out.println(isJavaFun); // OUTPUT: true
```

References: 

* [W3schools.com](https://www.w3schools.com/java/java_data_types.asp)
* [javapoint.com](https://www.javatpoint.com/java-data-types)
