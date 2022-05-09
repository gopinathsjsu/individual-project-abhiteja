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

* Go to repo abhiteja and clone the repository or download the zip file.
* Open the zipped folder or the entire folder in eclipse by navigating to File -> Open.
* After opening the project go to Billing.java and run the project.
* Make sure the java version used is compatible.
* Enter the input file.
* Once the code is executed, you can check the output in Output.csv file which is created and if an error is occurred, you can check it in Error.txt.


## Design Patterns 

Singleton Design Pattern: This Design Pattern belongs to the creational design pattern category and limits the instantiation of a class to a single object. This pattern helps in the formation of the application's database. A singleton InMemoryDB object is constructed and saved as a static member that all other classes can access without having to instantiate it every time.




