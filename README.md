# Ap24thLittleOOP
- [ ] Java has two areas of memory we care about: The stack and the heap
- [ ] Instance variables are variables declared inside a class but outside any method 
- [ ] Local variables are variables declared inside a method or method parameter 
- [ ] All local variables live on the stack in the frame corresponding to the method where the variables are declared 
- [ ] Object reference variables work just like primitive variables if the reference is declared as a local variable it goes on the stack 
- [ ] All objects live in the heap regardless of weather the reference is a local or instance variable 
- [ ] Instance variables live within the object they belong to, on the Heap.
- [ ] If the instance variable is a reference to an object, both the reference and the object it refers to are on the Heap.
- [ ] A constructor is the code that runs when you say new on a class type.
- [ ] A constructor must have the same name as the class, and must not have a return type.
- [ ] You can use a constructor to initialize the state (i.e. the instance variables) of the object being constructed.
- [ ] If you don't put a constructor in your class, the compiler will put in a default constructor.
- [ ] The default constructor is always a no-arg constructor.
- [ ] If you put a constructor--any constructor-in your class, the compiler will not build the default constructor.
- [ ] if you want a no-arg constructor, and you've already put in a constructor with arguments, you'll have to build the no-arg constructor yourself.
- [ ] Always provide a no-arg constructor if you can, to make it easy for programmers to make a working object. Supply default values.
- [ ] Overloaded constructors means you have more than one constructor in your class.
- [ ] Overloaded constructors must have different argument lists.
- [ ] You cannot have two constructors with the same argument lists. An argument list includes the order and/or type of arguments.
- [ ] Instance variables are assigned a default value, even when you don't explicitly assign one. The default values are 0/0.0/false for primitives, and null for references.
- [ ] A static method should be called using the class name rather than an object reference variable:
- [ ] Math. random ) VS. myFoo.go ()
- [ ] A static method can be invoked without any instances of the method's class on the heap.
- [ ] A static method is good for a utility method that does not (and will never) depend on a particular instance variable value.
- [ ] A static method is not associated with a particular instance only the class- so it cannot access any instance variable values of its class. It wouldn't know which instance's values to use.
- [ ] A static method cannot access a non-static method, since non-static methods are usually associated with instance variable state.
- [ ] If you have a class with only static methods, and you do not want the class to be instantiated, you can mark the constructor private.
- [ ] A static variable is a variable shared by all members of a given class. There is only one copy of a static variable in a class, rather than one copy per each individual instance for instance variables.
- [ ] A static method can access a static variable.
* If you're only going to use a static member a few times, we think you should avoid static imports, to help keep the code more readable. if you're going to use a static member a lot, (like doing lots of Math calculations), then it's probably OK to use the static import.
* ﻿﻿Notice that you can use wildcards (.*), in your static import declaration.
* ﻿﻿A big issue with static imports is that it's not too hard to create naming conflicts.
