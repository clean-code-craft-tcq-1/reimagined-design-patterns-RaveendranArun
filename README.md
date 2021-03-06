# reimagined-design-patterns

Give a summary description of Four design patterns that you choose from the following design patterns: **Adapter,  Builder, Composite, Decorator, Observer, Interpreter, State, Mediator, Memento, Prototype, Proxy**. In your summaries say:

- what kind of problem(s) you can solve with that pattern and when you use it, maybe with a short example
- how the pattern works, what the basic idea of the pattern is
- what the main advantage and what the the main disadvantage is of using this pattern
- Write a short summary for each of the four patterns, about half a page for each pattern (rather less than more). 

> Do not add diagrams, and do not try to give a complete description of the patterns as found in the books. Rather think of how you would explain the essential ideas of these patterns in a few sentences to a colleague while drinking coffee.

1. Observer Pattern

> This is one of the behavioral pattern. This pattern has a publisher subscriber model.Suppose we wish to subscibe a magazine/newspaper 
  from a particular publisher. So we can call the agent and order for the subscription. 
  After the subscription, the agent will send the each copy once the new edition is available. And if are wish to unscribe, they will stop sending the newspaper or magazine.
  Thus we dont need to go for each and every edition.
  
  Advantages: This pattern helps to observe the state of object. If the state the object changes, the object itself will send the notification.
  
2. Adapter Pattern

> This pattern comes under structural pattern. A simple example to describe this pattern is, imagine a Car need to drive over a railway line. This is not posbile directly(otherwise the driver should be more skillfull). This can be possible if a railtruck carrying the Car. The Car's tyres are incompitable with railwy line. But the car adapted to the railway interface via an adapter that is "railtruck".

Advantages: This pattern helps to communicate between two independent processes.

3. Decorator

> The decorator pattern acts as a wrapper to existing class, it is used to add new functionality to an existing object without altering its structure.
  The Coffee Ordering System has multiple types of Coffees, a new flavour of coffee can be added to the system without altering the existing feature.
  
4. Prototype pattern
> This pattern involves implementing a prototype interface which tells to create a clone of the current object.??
  The state pattern allows to change its behavior, when its internal state change. When ever program having multiple states, instead of using switch case
  we can go to state design pattern(abstract class)



