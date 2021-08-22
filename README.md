# Design-Patterns-Examples
Hands On Different Design Patterns Code in Java


## Strategy 
Strategy is a behavioral design pattern that turns a set of behaviors into objects and makes them interchangeable inside original context object.

The original object, called context, holds a reference to a strategy object and delegates it executing the behavior. In order to change the way the context performs its work, other objects may replace the currently linked strategy object with another one.

![image](https://user-images.githubusercontent.com/49389693/130185335-853f0e75-c37f-4d0e-bf6a-10272fa89f7f.png)

___


## State
State is a behavioral design pattern that lets an object alter its behavior when its internal state changes. It appears as if the object changed its class.

The State pattern suggests that you create new classes for all possible states of an object and extract all state-specific behaviors into these classes.

Instead of implementing all behaviors on its own, the original object, called context, stores a reference to one of the state objects that represents its current state, and delegates all the state-related work to that object.

![image](https://user-images.githubusercontent.com/49389693/130337850-f03786c4-652c-4721-9136-9ec8223453d8.png)

----
