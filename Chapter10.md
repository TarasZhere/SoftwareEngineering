# The Class Diagram
When designing a program, you work from a requirements specification
> The designer's task is to discover structures that make it possible to implement the requirements.

Look for nouns in the prblem description. Any noun that we see it could be a potential **class name**. 
Next could be verbs are potential methonds. 
### Example: User Validation
**The user needs to validate it's account**
|User|Validate|
|-|-|
|User is the class name|Validate is a function of the class|

**It is a good idea to keep a list of the canditae classes.**
Not all classes can be discovered by the description. 

## CRC card
Class-Responsabilities Collaboration
Use an index card for each CRC

What if CRC card has the responsabilities? We can split it up to more detailed fetures. 
## Relationships between Classes (CRC)
Type of relationships:
- Dependency
- Aggregation
- Inheritance

## Dependency
> A class depend on another class if it uses objects of that class.
```
class CustomerView{
    ...
    void display(Customer C){...}
    ...
}
```
We pass a class inside another *(Customer C > CustomerView)* so we can use their property.
**Coupling** is the connection made between 2 classes. In this case is better to use as low as coupling as possible.

## Aggregation
> A class aggregates another class is its object contain objects of the other class. 
- has a relationship

Example: A **quiz class** aggregates a **question class**


## Inheritance
> A class that inherit functions from another class. A sub-class

Example: Every car is a vehicle.
car is a subclass of vehicle.

## Relationship Symbols

|Relationship|Symbol|LineStyle|ArrowTip|
|--|--|--|--|
|Inheritance|---->|Solid|Triangle|
|Interface Implementation|---->|Dootted|Triangle|
|Aggregation|---->|Solid|Diamond|
|Dependency|---->|Dotted|Open|

More detail on how many connection can be represented as folloing
|Symbol| Relationship|
|----|-----|
|*|zero or more|
|1..*| one or more|
|0..1|zero or more|
|1|Exactly one|

### Association
Association: more general relationship between classes
Use early in design
A class is associate to another if we can navigate objects from on class to another.

### Composition
Compositoin is one of the classes can not exist without another

### Application


### Manifestations of Analysis Classes
Analysis  classes manifest themseves in onw of the following ways:
- External enitities 
- things 
- Occurence or events
- Roles
- Organizational Units
- Places
- 

## Potential classes
- Retained informarion
- Needed serices
- Multiple attributes
- Common attributes
- Common operations, as base class for example
- Essential requirements, Entity that has an essential requirement could be something that needs a class

## Defining attributes.
**attributes** describe a class that has been seleceted 

## Defining Operation [8]

## Class types
Entity Classes: Some classes will be an entity class which also is called model or business classes.
Boundary classes: Used to create the interface


## Responsability 
System intelligence should be distributed across classes to best address the needs of the problem.
