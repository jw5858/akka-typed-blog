# Sample Code for Introducing Akka Typed Blog Posts

## Akka Typed Version

Use `akka-typed` **`2.5.99-TYPED-M1`** in snapshot repository [http://repo.akka.io/snapshots/](http://repo.akka.io/snapshots/).

To use this version you need to add sbt resolver, maven or gradle repository as described in the [documentation](http://doc.akka.io/docs/akka/2.5/intro/getting-started.html#Using_a_build_tool) to you build, or use this example project as template.

## Blog Posts

Blog Posts and their main classes that can be run with sbt or maven:

* **[Akka Typed: Hello World in the new API](http://blog.akka.io/typed/2017/05/05/typed-intro)**
  * Java
    * blog.classic.javadsl.HelloWorldApp1
    * blog.typed.javadsl.HelloWorldApp1
    * blog.classic.javadsl.HelloWorldApp2
    * blog.typed.javadsl.HelloWorldApp2
  * Scala
    * blog.classic.scaladsl.HelloWorldApp1
    * blog.typed.scaladsl.HelloWorldApp1
    * blog.classic.scaladsl.HelloWorldApp2
    * blog.typed.scaladsl.HelloWorldApp2
* **[Akka Typed: Coexistence](http://blog.akka.io/typed/2017/05/06/typed-coexistence)**
  * Java
    * blog.typed.javadsl.CoexistenceApp1
    * blog.typed.javadsl.CoexistenceApp2
  * Scala
    * blog.typed.scaladsl.CoexistenceApp1
    * blog.typed.scaladsl.CoexistenceApp2
* **[Akka Typed: Mutable vs. Immutable](http://blog.akka.io/typed/2017/05/08/typed-mutable-vs-immutable)**
  * Java
    * blog.typed.javadsl.MutableRoundRobinApp
    * blog.typed.javadsl.ImmutableRoundRobinApp
  * Scala
    * blog.typed.scaladsl.MutableRoundRobinApp
    * blog.typed.scaladsl.ImmutableRoundRobinApp
* **[Akka Typed: Supervision](http://blog.akka.io/typed/2017/05/16/supervision)**
  * Java
    * blog.typed.javadsl.FlakyWorkerApp
  * Scala
    * blog.typed.scaladsl.FlakyWorkerApp
* **[Akka Typed: Signal](http://blog.akka.io/typed/2017/05/19/signals)**
  * Java
    * blog.typed.javadsl.FlakyWorkerApp2
  * Scala
    * blog.typed.scaladsl.FlakyWorkerApp2
    

## How to Run with sbt

```
sbt run
```

Select the main class to run.
Press ENTER to exit the system

## How to Run with maven

```
mvn exec:java -Dexec.mainClass="blog.classic.javadsl.HelloWorldApp1"
```

Press ENTER to exit the system
 
