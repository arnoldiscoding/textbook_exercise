# Review Exercise

## R10.1

a. The base class is **Employee** and the derived class should be **Manager** since Manager is a type of employee.

b. The base class is **Polygon** and the derived class should be **Triangle** since Triangle is a type of Polygon.

c. The base class is **Student** and the derived class should be **GraduateStudent** since GraduateStudent is a type of Student.

d. The base class is **Person** and the derived class should be **Student** since Student is a type of Person.

e. The base class is **Employee** and the derived class should be **Professor** since Professor is a type of Employee.

f. The base class is **BankAccount** and the derived class should be **CheckingAccount** since CheckingAccount is a type of BankAccount.

g. The base class is **Vehicle** and the derived class should be **Car** since Car is a type of Vehicle.

h. The base class is **Vehicle** and the derived class should be **Minivan** since Minivan is a type of Vehicle.

i. The base class is **Car** and the derived class should be **Minivan** since Minivan is a type of Car.

j. The base class is **Vehicle** and the derived class should be **Truck** since Truck is a type of Vehicle.

## R10.2

## R10.3

## R10.4

## R10.5

Having derived classes is over-engineered. Inheritance should model "is-a" relationships with behavioural differences. However when managing the inventory, we do not care about whether Toaster and CarVacuum are having a behaviourial difference, as we only concern about attributes like price and quantity, which are not item specific.

Also, new items appear frequently, which makes the system inflexible to scale.

## R10.6

## R10.7

## R10.8

## R10.9

## R10.10

1. You cannot convert base-class object to derived-class object. The reason being the two have fundamentally different memory allocations and it violates the design principle of OOP.

Since a derived class has additional data members than the base class, converting base-class object to derived-class object would result in access memory that is non-existent, causing error or undefined behaviour.

2. You can convert derived-class object to base-class object.

The derived class object contains everything that a base class object needs. Therefore the base class part is always accessible and valid.

Also from a memory stand point, the base class portion is always stored at the start, therefore we can reference the derived class with base pointers without problems.
