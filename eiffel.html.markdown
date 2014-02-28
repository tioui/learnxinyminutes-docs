---

language: Eiffel
contributors:
    - ["Louis Marchand", "http://github.com/tioui"]
filename: LearnEiffel.e

---

Eiffel is an object-oriented programming language designed by Bertrand Meyer. The key characteristics of the Eiffel language include:

- An object-oriented program structure in which a class serves as the basic unit of decomposition.
- Design by contract tightly integrated with other language constructs.
- Automatic memory management, typically implemented by garbage collection.
- Inheritance, including multiple inheritance, renaming, redefinition, "select", non-conforming inheritance, and other mechanisms intended to make inheritance safe.
- Constrained and unconstrained generic programming
- A uniform type system handling both value and reference semantics in which all types, including basic types such as INTEGER, are class-based.
- Static typing
- Void safety, or static protection against calls on null references, through the attached-types mechanism.
- Agents, or objects that wrap computations, closely connected with closures and lambda calculus.
- Once routines, or routines evaluated only once, for object sharing and decentralized initialization.
- Keyword-based syntax in the ALGOL/Pascal tradition but separator-free, insofar as semicolons are optional, with operator syntax available for routines.
- Case insensitivity
- Simple Concurrent Object-Oriented Programming (SCOOP) facilitates creation of multiple, concurrently active execution vehicles at a level of abstraction above the specific details of these vehicles (e.g. multiple threads without specific mutex management).

```eiffel
note
	description : "project application root class"
	date        : "$Date$"
	revision    : "$Revision$"

class
	APPLICATION

inherit
	ARGUMENTS

create
	make

feature {NONE} -- Initialization

	make
			-- Run application.
		do
			--| Add your code here
			print ("Hello Eiffel World!%N")
		end

end

```

## Further Reading

The links provided here below are just to get an understanding of the topic, feel free to Google and find specific examples.

Other Topics To Research:

* [Java Tutorial Trail from Sun / Oracle](http://docs.oracle.com/javase/tutorial/index.html)

* [Java Access level modifiers](http://docs.oracle.com/javase/tutorial/java/javaOO/accesscontrol.html)

* [Object-Oriented Programming Concepts](http://docs.oracle.com/javase/tutorial/java/concepts/index.html):
    * [Inheritance](http://docs.oracle.com/javase/tutorial/java/IandI/subclasses.html)
    * [Polymorphism](http://docs.oracle.com/javase/tutorial/java/IandI/polymorphism.html)
    * [Abstraction](http://docs.oracle.com/javase/tutorial/java/IandI/abstract.html)

* [Exceptions](http://docs.oracle.com/javase/tutorial/essential/exceptions/index.html)

* [Interfaces](http://docs.oracle.com/javase/tutorial/java/IandI/createinterface.html)

* [Generics](http://docs.oracle.com/javase/tutorial/java/generics/index.html)

* [Java Code Conventions](http://www.oracle.com/technetwork/java/codeconv-138413.html)
