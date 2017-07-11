---?image=media/onion-last.jpg
# Peeling the Onion
## Microservices One Layer at a Time
---
# What's in a Name?

1. Onions
2. Buzzwords
---?image=media/grass.jpg&size=auto
# What's in a Name?
`* 1927 (Gdańsk)
✝ 2015 (Lübeck)`
---
# How do we Build Software?
* Hexagonal Architecture/Ports and Adapters (Alistair Cockburn 2005)

* The Onion Architecture (Jeffrey Palermo 2008)

* Screaming Architecture (Robert Cecil Martin 2011)

* Data, Contexts, Integration: DCI Architecture (Reenskaug, Coplien 2009)

* Boundary/Control/Entity (Ivar Jacobson, 80s)

---
# Many Names, Similar Goals
* Independent of Frameworks

* Testable

* Independent of presentation layer/UI

* Independent of DB/Storage

* Independent of external agency

# Code Aware
```scala
def foo(a: Int): Double = 42
```
---?image=media/clean_architecture1.png&size=auto
---?image=media/self-portrait.png&size=auto
# What's In a Name?
---
# John De Goes Onion
---
# Abstraction
At each layer, rather than directly implementing our programs, we want to write a **specification** that we later **implement** or **interpret**

This allows us to:

 * swap out implementations
 *  test using mock implementations
 *  use notions of interpretation, e.g.
 	*  evaluation
 	*  pretty-printing
 	*  serialization

---
# Many Names, Similar Goals

* interface vs implementation
* syntax vs semantics
* DSL with multiple interpreters
* compiling a source language to a target language
---
# Abstractions, a Dime a Dozen

We don’t want to be penalised with:

* poorly performing code

* code that’s overly difficult to read or write.

---

