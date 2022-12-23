# Building a REST API in Scala with Play Framework

For building simple, CRUD-style REST APIs in Scala, the Play Framework is a good solution. 
It has an uncomplicated API that doesn’t require us to write too much code.

In this project we will build a todo list application. Rather than use a database, 
we’ll store the todo list items in memory. The application will provide several endpoints, to perform CRUD operations

>>  Reference

https://www.baeldung.com/scala/play-rest-api


>>	Requirements
*	[Java]
*	[IDE] IntelliJ IDEA
*	[SBT] can install using https://www.scala-sbt.org/download.html

    SBT is an open-source build tool for Scala and Java projects, similar to Apache's Maven and Gradle.
    
    Its main features are:
    * Native support for compiling Scala code and integrating with many Scala test frameworks
    * Continuous compilation, testing, and deployment
    * Incremental testing and compilation, meaning only changed sources are re-compiled, only affected tests are re-run
    * Build descriptions written in Scala using a DSL
    * Dependency management using Coursier, which supports Maven-format repositories
    * Integration with the Scala REPL for rapid iteration and debugging
    * Support for mixed Scala/Java projects


*   [Giter8]


    Giter8 is a command line tool to generate files and directories from templates published on GitHub or any other git repository. 
    It’s implemented in Scala and runs through the sbt launcher, but it can produce output for any purpose.
    Choose from community-maintained Giter8 templates to jump start your project:
    $ sbt new scala/scala-seed.g8
    $ sbt new playframework/play-scala-seed.g8
    $ sbt new akka/akka-http-quickstart-scala.g8
    $ sbt new http4s/http4s.g8
    $ sbt new holdenk/sparkProjectTemplate.g8	

>	Once the project template is downloaded we can start the project server by going into the project directory
*	sbt update
*	sbt run
>   Our project server is live in localhost:9000 port
		
