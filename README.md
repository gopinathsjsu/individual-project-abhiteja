# individual-project-abhiteja

## Name: Abhiteja Mandava

## SJSU ID: 015786550

## Project Description

The purpose of this project is to create a Java application that will maintain a static database on its own. The changes to the data would not persist if we ran the software again. This application should allow users to purchase inventory items, with amounts limited per item type. User can buy the items among three different categories. They are:

Essentials,
Luxury,
Misc

When the user input criterion is met, a bill amount should be calculated; otherwise, an error notice should be displayed, indicating the products with wrong values.

## Instructions

Requirements: Eclipse IDE

- Go to repo abhiteja and clone the repository or download the zip file.
- Open the zipped folder or the entire folder in eclipse by navigating to File -> Open.
- After opening the project go to Billing.java and run the project.
- Make sure the java version used is compatible.
- Enter the input file.
- Once the code is executed, you can check the output in Output.csv file which is created and if an error is occurred, you can check it in Error.txt.

## Design Patterns

Singleton Design Pattern: This Design Pattern belongs to the creational design pattern category and limits the instantiation of a class to a single object. This pattern helps in the formation of the application's database. A singleton InMemoryDB object is constructed and saved as a static member that all other classes can access without having to instantiate it every time.

Composite Design Pattern: Composite pattern is a partitioning design pattern and describes a group of objects that is treated the same way as a single instance of the same type of object. The intent of a composite is to “compose” objects into tree structures to represent part-whole hierarchies. It allows you to have a tree structure and ask each node in the tree structure to perform a task.

The composite pattern refers to a collection of objects that are considered in the same way as a single instance of the same type. We can retrieve individual OrderItems from the List of OrderItems in the Order.

Adapter Pattern: The adapter pattern convert the interface of a class into another interface clients expect. Adapter lets classes work together that couldn’t otherwise because of incompatible interfaces.

The FileUtility class is designed to read input files into Inventory and Order.

UML Class Diagram :

![202_ClassDiagram drawio](https://user-images.githubusercontent.com/90536339/167563113-69133ee6-4ea2-40d0-85fd-42748fd911c9.png)
