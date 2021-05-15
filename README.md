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


# **Proxy Design Pattern**
Proxy is a structural design pattern that lets you provide a substitute or placeholder for another object. A proxy controls access to the original object, allowing you to perform something either before or after the request gets through to the original object.

**Example/Usecase :** Consider a cheque or credit card is a proxy for what is in our bank account. It can be used in place of cash, and provides a means of accessing that cash when required
**Advantages :** 1. The proxy works even if the service object isn’t ready or is not available.
                 2. Open/Closed Principle. You can introduce new proxies without changing the service or clients.

**Disadvantage :** 1. The code may become more complicated since you need to introduce a lot of new classes.
                   2. The response from the service might get delayed.

