Constructor(){}
    - Made fields of object for object.

init {}
    - init method always run when created any class object.
    - init method always runs first

### Encapsulation 
    - if we want access to object fields we use to encapsulation. 
    - getter and setter method

example : 
var name : String? = name
    private set
    get
this means we can't change the name but we can only see the name

### Inheritance
    - If we want to inherit a class from another class, 
    - we must prefix the name of the inheritance class with open

example:
class SpecialArtist(name: String, age: Int, job: String) : Artist(name, age, job) {}

### Polymorphism
    - Accually it's a kind of like overwriting the methods
    - so, we want use same methods but different shape.

### Abstraction
    - Abstract class is cannot a create new object from itself
    - so, why use to abstract class ?

example:
Imagine we have many different class : artist, nurses, doctors ..
We know that all of this class is human. So if we want any change about humanity
and we're not use to abstract class we have to change one by one all class
but if we use abstract class we only change to abstract class.

### Interface
    - we can take only one inherit class
    - but we can take many interface class
    - interface class cannot a create new object from itself too 



    