# Factory

The Factory Pattern is an implementation of several Factory Methods. It has the same drawbacks and benefits of
Factory Method, but in this case everything that instantiates other classes is inside the ConcreteFactory class, which
uses a singleton pattern because there's no reason to have several instances of the Factory going around.
