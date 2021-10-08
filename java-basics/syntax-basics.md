## Java Syntanx Basics

Let's use a Hello World program to learn about the basics of Java syntaxes. 

```
public class Main {
  public static void main(String[] args) {
    System.out.println("Hello World");
  }
}
```
*OUTPUT*
```
Hello World
``

Here are some key notes about Java syntaxes:

* Java is class oriented language. Every single line of code in a Java program must be inside a `class`. 
* In the above example, the name of the class is `Main`. 
* The name of the class should start with upper case letter.
* Java is case sensitive. `Main` is different to `main`. 
* The name of the class name must be similar to the name of the file. 
* The extension for the java files is `.java`, and so the name of the above hello world can be `Main.java`. 
* Every Java program must have `main()` method. Here is what it looks like: 


``
public static void main(String[] args)
```

* Any statement inside the `main()` method must be executed. More on methods later. 
* In our example, we used the statement `println()` to display `Hello World` on the screen.

```
public static void main(String[] args) {
  System.out.println("Hello World");
}
```

* The statement starts and ends with the curly braces `{statements...}`
* Each statement must end with semicolon`(;)`. 
* You can add comment by // or /*....*/


```
// This is a comment
*/This is a comment and it will not be executed! */
```

That's it for Java basics. 

You can learn more at[W3schools.com](https://www.w3schools.com/java/java_syntax.asp). 
