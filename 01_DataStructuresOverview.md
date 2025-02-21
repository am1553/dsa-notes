# Data Structures Overview

> "Data structures is a particular way of storing and organizing data in a computer so that it can be used efficiently."
> — _Narasimha Karumanchi, Data Structures and Algorithms Made Easy in Java, Page 16_

### Some General Data Structure Types:

- Arrays
- Files
- Linked Lists
- Stacks
- Queues
- Trees
- Graphs

There are two categories of data types, one where it's system defined known as primitive data type which is not an object and holds simple value directly in memory, and another where it's an abstract data types which is an object with operations that can be used on a data type.

```java
int number = 42; // A primitive data type that stores the value 42 directly in memory
LinkedList<Integer> lists = new LinkedList<>(); // // An abstract data type which includes operations
```

Additionally, users can also define their own data type, for example:

```java
class Person { // User defined data type
    String name;
    int age;

    public Person(String name, int age) {
        this.name = name;
        this.age = age;
    }

    public void display() {
        System.out.println(name + " is " + age + " years old.")
    }
}
```
