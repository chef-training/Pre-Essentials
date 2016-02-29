# Just a Little Bit of Ruby

* Introduction

Chef is built on top of Ruby. For good reason. Ruby is a dynamic programming language that makes it easy to design Domain Specific Languages (DSL)

What part of a recipe is Ruby and what part of it is Chef?
What does it mean that Chef is built on top of Ruby?
What is a Domain Specific Language?
Do I need to know Ruby to write Chef?
How much Ruby do I need to know?

Let's dissect the resources that we used in the previous section.

* Strings

Things in quotes are generally called Strings. Strings means a string of characters like connected together that can be a single letter to an entire story.

> The reason its called a String is because before modern programming languages developers had to choose between a Character or a sequence of characters. The name stuck around

String is really just a bad name to describe what most of us would call Text.

Let's play with Strings in an activity

Single Quotes and Double Quotes are probably the most common approaches to defining text. There are many ways that you can define a String. The most important thing is that what you use to start a String is how you end that String.

We can do more that create Strings. We can ask them to do things. Strings can be asked to capitalize or reverse themselves. That's because Strings are these things called Objects.

* Objects

What are Objects?

When someone says Object and Ruby is all Objects or Ruby is an Object-Oriented what we means is that you can ask them to do something. You can ask details about them. Instead of the String being on a the text you see between the quotes. It has metadata, characteristics, and character.

* Method Invocation

Asking an Object, like a String, to do something requires you to specify the message you want to send it by placing a period between the object and the message. Because if it was not there it might be hard to distinguish from the String and the message you are sending to it. It could have been any symbol. The period is popular in a lot of other languages.

* Numbers (Integers & Floats)

Text is not all you can define. Ruby has numbers. They work like you would expect. You can define numbers with decimal points or without decimal points. We call the ones without the decimal points Integers. The ones with the decimal points Floats, a cute nick name for floating point numbers.

> For those run screaming from math classes this really means numbers without and decimal place that can be positive or negative.

> Floating point numbers can also be positive or negative.

Let's play with Numbers in an activity

* Method Invocation - Method Missing

What would happen if we send a message that an object can't handle? ("Me".truth - I can't handle the truth)

Sending the message to the object doesn't mean the Object has to comply. It only complies if it defines a method that matches the name of the message. Without that defined method it responds back with "I don't know. That method you asked for is missing."

Let's play with Objects receiving methods they do not have

There is one last Object that you should know about. This object is called a Symbol.

#### Remaining Items in this Section Not in the Above Narrative

* Symbols

> NOTE: Introducing them instead of Numbers might be the right thing to do as they will come in contact with them. Numbers are another easy example to grasp onto but Symbols are used more often.

Symbols are like Strings in some ways and not in other ways. They start with a colon. The difference there is only one of them. Well I mean you can use them more than once but you are using the same one over again.

What I didn't tell you is that all the objects get an ID. You might think of it as their name. Each String created has a new name that is automatically given to them at birth. That's not the case. With Symbols its more like you are cloning the same way.

This has some benefits. Like when you wan to compare them together. It is easier to write as you do not need to use quotes. They often are used to represent states. It is often the choice when developers define a limited set of responses even if they are not limited in what you can express with them.

* Using a method with parameters

Some of those messages that we send to objects can take parameters. This is like asking someone to go shopping and giving them the list. Or telling someone you want a sandwich and this is what you want on it (sudo make me a sandwich joke).

* Method with block as a parameter

Oh boy! Blocks are a way to pass a piece of code. Some instructions to another method. This is like giving a person a set of instructions in an envelope. This envelope can be opened and actions can be taken based on the instructions.

* Context

The purpose here is to make sure they understand that resources in recipes are the same methods that we have been playing.

This one is hard to explain. What I want to do here is say that these methods that we have been talking about are on the object. But really we are all in an object. I guess maybe we could talk about the World. You are in the world. When you are the context of the world you can write out 'age' and not `world.age`.

We could also use the idea of the person. You don't have to say `me.age` you simply ask yourself 'age' and that value is returned to you as opposed to asking someone else `you.age`.

Let's play with some exercises with executing methods in different contexts.

* Ruby file extension

Files have extensions to make it clearer to computer what the file type is. Sometimes it is also for people. All Ruby files  end with it.`.rb`
