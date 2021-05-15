# reimagined-design-patterns

Give a summary description of Four design patterns that you choose from the following design patterns: **Adapter,  Builder, Composite, Decorator, Observer, Interpreter, State, Mediator, Memento, Prototype, Proxy**. In your summaries say:

- what kind of problem(s) you can solve with that pattern and when you use it, maybe with a short example
- how the pattern works, what the basic idea of the pattern is
- what the main advantage and what the the main disadvantage is of using this pattern
- Write a short summary for each of the four patterns, about half a page for each pattern (rather less than more). 

> Do not add diagrams, and do not try to give a complete description of the patterns as found in the books. Rather think of how you would explain the essential ideas of these patterns in a few sentences to a colleague while drinking coffee.

# **Adapter Design Pattern**
Adapter pattern works as a bridge between two incompatible interfaces and acts as a software design pattern that allows the interface of an existing class to be used as another interface.

**Example/Usecase :** Consider Charging your mobile phone, You need to connect one end to mobile Type C or Type B and other other end to Power Supply via adapter, Charger directly can not be connected to power supply without an adapter.

**Advantages :** Flexibility in design (New adapters can be added without disturbing the existing code)

**Disadvantage :** Increases the complexity of code when more number of interfaces are added.


# **Mediator Design Pattern**
Mediator design pattern defines an object that encapsulates how a set of objects interact. It allows multiple objects to communicate with each without knowing each other's structure.

**Example/Usecase :** Traffic control room at airpots, all flights will have to interact with each other for finding which flight is going to land next that is possible only through mediator (Traffic control room)

**Advantages :** Reusable codes and easy maintenance (Adding new mediators can be done without changing the existing code)

**Disadvantage :** Complexity in Mediator.


# **Composite Design Pattern**
Composite is a structural design pattern that lets you compose objects into tree structures and then work with these structures as if they were individual objects.

**Example/Usecase :** Traffic control room at airpots, all flights will have to interact with each other for finding which flight is going to land next that is possible only through mediator (Traffic control room)

**Advantages :** 1. The proxy works even if the service object isn’t ready or is not available.
                 2. Open/Closed Principle. You can introduce new proxies without changing the service or clients.

**Disadvantage :** 1. The code may become more complicated since you need to introduce a lot of new classes.
                   2. The response from the service might get delayed.


# **Proxy Design Pattern**
Proxy is a structural design pattern that lets you provide a substitute or placeholder for another object. A proxy controls access to the original object, allowing you to perform something either before or after the request gets through to the original object.

**Example/Usecase :** In an organization, It have general managers and under general managers, there can be managers and under managers there can be developers. Now you can set a tree structure and ask each node to perform common operations
**Advantages :** 1. You can work with complex tree structures more conveniently: use polymorphism and recursion to your advantage.
                 2. Open/Closed Principle. You can introduce new element types into the app without breaking the existing code, which now works with the object tree.
                 
**Disadvantage :** 1. It might be difficult to provide a common interface for classes whose functionality differs too much. In certain scenarios, you’d need to overgeneralize                      the component interface, making it harder to comprehend.

