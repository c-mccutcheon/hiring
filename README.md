# General Concepts
-- **General**

Explain S.O.L.I.D to me?

Why would the Single Responsibility Principle be important?

What is Inversion of Control? How does it relate to Dependency Injection?

What are some of the common design patterns? Where might they be applicable?

Name the three main principles of Object oriented design?

Explain stateful vs stateless applications to me?

What is a process?

What is the difference between an abstract class and an interface?

-- **Testing (All developers should be aware of this)**

Difference between mocks and stubs?

What types of testing should you undetake?

How are you able to affect the functionality of dependencies when writing functional tests?

Why are Interfaces important in testing?

-- **Source Control**

What source control systems have you used before?

Compare distributed to centralized version control systems to me?

What is a Pull Request?

What are some common branching strategies seen in the wild, compare some for me?

-- **Continuous Improvement**

What is refactoring? Why is it a good practice?

Tell me about a time you failed? What happened next?

What value do Peer reviews, automated builds, and automated testing add to a software product?

How would you deal with a code review that went against your organisations rules?

# Programming Theory

-- **Types & Memory Management**

What is a value type? How does it differ to a reference type?

Where would the value of a value type be typically stored?

Can a value type value be null?

Where are reference types typically stored?

Explain what is meant by passing by value, and passing by reference?

What is the volatile keyword?

-- **Data Structures**

What are typical types of collection available in .NET? (Answer: List, HashTable, Stack, LinkedList, Dictionary, etc)

What collection type would you use for FIFO? (Answer: Queue, or Queue<T>)

What collection type is the most efficient for re-ordering items? (Answer: HashTable)

What collection type provides the fastest lookup when less than 10 items are present? (Answer: ListDictionary)

When might you choose to use an Array, over a Collection? (Answer: Low-level code, where item count is fixed, in order to reduce memory overhead)

-- **Threading and Parallelism**

T.B.D

# API Related Questions (For hires with significant amount of API work)

-- **REST**

What is REST?

What is a resource? How should their state be manipulated?

Explain Coarse vs Fine grained resource definitions?

What would be the outcome of CRUD domain logic spilling over into the client?

How do you authorize against a REST API? (Note: Authorize, not Authenticate - different things)

How should we inform consuming clients of how to navigate available, or related resources?

What importance does the Accept header have in communicating to a REST API?

What is meant by a JSON formatted payload?

What is the correct way to version REST APIs? (Answer: there is **no** correct way, only three approaches, bit of a trick question but anyone whom has done serious API work would have come across this. **URL**, **Media-Type**, **Custom Header**)

Where might a SOAP based service be more applicable than REST? (Answer: When there are specific security requirements, or reliable messaging is required)

-- **WCF**

What does A.B.C mean in the context of WCF?

How do clients implement a WCF service?

How is versioning deal with in WCF?

# Web related questions (For hires with a significant amount of web work)

-- **MVC & Web**

What is the MVC framework? Explain the major constituent parts?

What is meant by routing?

What is the Razor view engine?

What are controller actions?

What is ViewData?

What is an S.P.A? how do they differ from a traditional web application?

What are some common web attack vectors? How can we mitigate them? (Answer: Look for Cross-Site Scripting, Cross-site request forgery)

What is JavaScript used for? (Answer: This can be in-depth if they go into Node, web frameworks, etc - over and above the usual)
