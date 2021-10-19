## Java Strings

Strings are used for storing text or sequence of characters. In Java, `A String` must be inside double quotes(`"..."`). 

Here is an example of a `String` variable.

```
String type = "This is a string";
```

A more elaborated example: 

```
class Main {
    public static void main(String[]args) {

        // creating strings 

        String first = "Java";
        string second = "Python";
        String third = "JavaScript";

        // Printing the above strings

        System.out.println(first); //Java
        System.out.println(second); //Python
        System.out.println(third); // JavaScript

    }
}
```
Different to other primitive data types like `int`, `char`, `float`, `double`, etc..., `String` is an object of predefined class and all strings variables are the instances of the `String` class.


### String Methods

Java offers various methods to perform different operations on strings. Let's discuss them. 


#### String Length

Since `String` is an object, we can perform some operations around it such as finding the length of the string. 

Here is an example of what we are talking about.

```
String greetings = "Hello Jean";
int len = greetings.length();
System.out.println("The length of string is: " + len)
```

OUTPUT
```
The length of string is: 9
```

#### Converting String to Upper and Lower Case

We can use the method `toUpperCase()` and `toLowerCase()` to convert the strings to upper and lower case respectively. 

```
String text = "Hello"
String lower = text.toLowercase();
String upper = text.toUppercase();
System.out.println(lower);
System.out.println(upper);
```
OUTPUT
```
hello
HELLO
```

#### Getting the Index of Text in String

We can use `indexOf()` to get the position or index of the first occcurence of text in a String. Whitespace is counted too. 

```
String text = "This is Java";
String index = text.indexOf();
System.out.println(index) OUTPUT: 4
//Count starts from 0 in Java.
```

#### Concatenating Strings

```
String firstName = "Jean ";
String lastName = "De";
System.out.println(firstName.concat(lastName)); //OUTPUT: Jean De
```

Below tables summarizes more String methods.  

| Methods      | Description | 
| ----------- | ----------- |
| contains()  | checks whether the string contains a substring       |
| substring()   | returns the substring of the string        |
| join()   | join the given strings using the delimiter        |
| replace()   | replaces the specified old character with the specified new character        |
| replaceAll()   | replaces all substrings matching the regex pattern        |
| replaceFirst()   | replace the first matching substring        |
| charAt()   | returns the character present in the specified location substring        |
| getBytes()   | converts the string to an array of bytes        |
| compareTo()   | compares two strings in the dictionary order        |
| compareToIgnoreCase()   | compares two strings ignoring case differences        |
| trim()   | removes any leading and trailing whitespaces        |
| format()   | returns a formatted string        |
| split()   | breaks the string into an array of strings        |
| valueOf()   | returns the string representation of the specified argument        |
| toCharArray()   | converts the string to a char array
| matches()   | checks whether the string matches the given regex        |
| startsWith()   | checks if the string begins with the given string        |
| endsWith()   | checks if the string ends with the given string        |
| isEmpty()   | checks whether a string is empty of not        |
| intern()    | returns the canonical representation of the string        |
| contentEquals()   | checks whether the string is equal to charSequence        |
| hashCode()   | returns a hash code for the string        |
| subSequence()   | returns a subsequence from the string        |

* Table source: [Programmiz](https://www.programiz.com/java-programming/string)