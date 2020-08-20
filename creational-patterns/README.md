# Creational Design Patterns

## Benefits 

- Creational patterns make design become more flexible. They provide different ways to remove explicit references in the concrete classes from the code that needs to instantiate them. In other words, they create independency for objects and classes.

- Creational patterns try to give ready-to-use objects to users instead of asking for their input, which, in some cases, could be complex and will couple your code with the concrete implementations of the functionality that should be defined in an interface.



## Singleton Pattern

This pattern guarantees a single instance of an object and avoids duplicates.

### Application of the Singleton pattern
- Using the same connection to the database to perform queries
- Limit access to some variable 