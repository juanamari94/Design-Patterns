# Strategy

Strategy is a pattern that that has several classes implement an interface, and the Context class which in this case
is Account makes use of them to vary its behavior according to the type of account it is (accountType property).

Strategy is one of the most commonly used patterns because it allows a very clean encapsulation, allowing the
context class to implement the different behaviors. Think of it as a class that can use sorting algorithms on a whim,
and add more and more without using a context class.

In the TemplateMethod project it was mentioned that TemplateMethod is a lot more effectively and less time consuming
than Strategy for this specific problem. Why is this so? Because Strategy is more fitting for implementations
that have very different behaviors, whilst TemplateMethod accomodates implementations with very similar functionalities.
