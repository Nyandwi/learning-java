## The Difference Between Java Platforms: JDK, JRE, JVM

One of the Java advantages is that its programs can run everywhere. A program writtem for the Java platform can run well on other hardwares and operating systems. 


### Java Virtual Machine (JVM)

A virtual machine is a software implementation of a given physical machine. There are numerous softwares that allow people to use a given operating system or other machines virtually. Example of virtual machines include [VirtualBox](https://www.virtualbox.org/wiki/VirtualBox) Virtual PC, Parallels Desktop for Mac, etc...

JVM is a kind of virtual machine that allow a computer to run a Java program. JMV is an abstract machine that provides a runtime environment for executing Java programs. JVMs are available for many hardwares and softwares platforms, which means it does not depend on platform. 

When you execute a Java program, Java compiler convert the Java code to `bytecode`. JVM convert the `bytecode` to machine code(set of binary instructions that can be executed directly by CPU). 

![Image](https://github.com/Nyandwi/learning-java/blob/main/images/javaflow.png)

*Image: The execution flow of Java progrms. Credit: Programmiz*

To learn more about JVM, check this [article.](https://dzone.com/articles/jvm-architecture-explained) and [this](https://en.wikipedia.org/wiki/Java_virtual_machine). 


### Java Runtime Environment(JRE)

JRE is a software package that provides class libraries, JVM, and other components required to run Java programs. If you only to run Java programs but not develop them, you need JRE. 

JVM is an abstract machine, but JRE exist physically. Simply, JRE is an implementation of JVM that provides the runtime environment for Java programs.


### Java Development Kit(JDK)

JDK is a software development kit required to develop java programs. JDK contains JRE and other development tools like compilers, debuggers, JavaDoc, etc...

For developing Java programs, you need to download JDK. You can download it [here](oracle.com/java/technologies/downloads/#jdk17-mac). 


### Combining JVM, JRE, JDK

![image](https://github.com/Nyandwi/learning-java/blob/main/images/jvm-jre-jdk.png)

Image credit: Programmiz
