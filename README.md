#TODO
- Translating to english
- Layout
- Description for each chapter
- Give every tool a difficulty rating (basic of advanced)
- Present this page to the java guild

# Goal of this document
Helping java developers grow by:
- making clear which skills we expect from developers
- giving them tools them can help them improve these skills

# Skills & Tools
## General
Cegeka has a license for [**pluralsight**](https://www.pluralsight.com/). Pluralsight is a web platform for online video courses.
Most things listed here can be found on pluralsight.
## Hard skills
### TDD
> Rationale : Test-driven-development is a core skill for the java developer. We write software in large teams with codebases that exist over many years. Tests serve as live documentation, as a safety net for refactoring, as a guide for writing cleaner code. 
```
Exercise: Do code kata's (website, sessions, meetups)
Exercise: Game of life
Exercise: TDD as if you meant it
Book: TDD (Kent Beck)
Course: Agile Software Engineering
```

### Java architecture
> Rationale : Knowing how java gets executed and behaves at runtime helps a developer to design better applications. What are the problems you run into when doing too much recursion ? How can you solve garbage collection performance problems ?
```
Exercise: Create a memory leak and inspect with a profiler.
Website: Lookup java memory architecture online
Book: Effective java --> TODO : not really java-architecture book
Conference: Devoxx
Video: Devoxx talks
```
### Java api
> Rationale : This is the first level on top of the syntax and the grammar of java. Suppose you're learning a new speaking language (e.g. spanish) you won't be proficient by learning only the grammar, you have to learn common words, common language structure. The java api is the equivalent of this : to become an efficient developer you have to study and exercise on the java api.
```
Website: Code wars
Website: Api reference website
Book: Effective java
```
### Enterprise application
This includes
* Transactionality 
* Security
* Messaging
* Web tier
* Dependency injection
* AOP
* Persistence
```
Exercise: Create your own full stack spring boot application  
Website: https://docs.oracle.com/javaee/7/tutorial/index.html
Website: getting started Spring  
Course: spring cursus (pivotal)  
Book: Patterns of enterprise application architecture (Martin Fowler).
```
### Refactoring
> Rationale : When writing software for complex business problems, you can assume that your model of the business won't be correct the first time. With refactoring you get a set of techniques and patterns, to redesign your model safely and more efficiently.  
```
Book: Refactoring 1 of 2  (Martin Fowler).
Exercise: movierental (refactoring exercise), kata's
Course: Agile software engineering
Website: https://refactoring.guru/
```
### Clean code
> Rationale : This is all about clear communication, again writing software that is read and modified by a lot of people over a period of many years requires the need for clear communication. Clean code gives good practices to ensure that code is well written and easier to maintain and understand. 
```
Book: clean code
Book: Code complete
Book: pragmatic programmer, extreme programming explained
```
### DDD
> Rationale :  
```
Book: Blue book
Book: DDD quickly (https://www.infoq.com/minibooks/domain-driven-design-quickly)
Book: Red book
Book: DDD distilled 
Book: Patterns, principles and practices of DDD
Book: CQRS journey guide (https://docs.microsoft.com/en-us/previous-versions/msp-n-p/jj554200(v=pandp.10))
Conference: DDDEU
Workshop: DDDEU workshop (see https://training.dddeurope.com/) 
Workshop: Greg Young's workshop
(to validate) Pluralsight path: https://www.pluralsight.com/paths/domain-driven-design
```
### Continuous delivery
> Rationale : TODO 
```
Book: Continuous delivery
Book: Phoenix Project
Book: Release it!
Conference: Devops summit
Course : Devops (internal)
Book: The site reliability
```
### Continuous integration
> Rationale : TODO 
```
Exercise: Installing your own jenkins
Research: (wim will look it up)
Book: Continuous delivery
```
### Enterprise integration patterns
> Rationale : TODO 
```
Book : [Enterprise Integration Patterns - Gregor Hohpe Bobby Woolf](https://www.enterpriseintegrationpatterns.com/)
Book : [Camel in action - Claus Ibsen Jonathan Anstey](https://www.manning.com/books/camel-in-action-second-edition)  
Website : https://www.enterpriseintegrationpatterns.com/patterns/messaging/
Website : https://spring.io/projects/spring-integration
```
### Design patterns
> Rationale : TODO 
```
Book: Head First Design Patterns, Design Patterns (Elements of Reusable Object-Oriented Software)
Website: https://refactoring.guru/design-patterns/catalog
```
### Basic computer skills
> Rationale : TODO 
- Knowledge on how a computer functions: cpu - ram - disk
- Knowledge how programs work
```
Website: https://gist.github.com/jboner/2841832
Presentatie: ???cegeka school???
```
### Basic netwerking skills
> Rationale : TODO 
- basic knowledge on layered networking (TCP/IP)
- troubleshooting network problems
- tcp handshaking procedure
- application protocols : http, https, ftp
- using networking tools : ssh, telnet, ss, netstat, ping, nslookup, ...
### Security
> Rationale : TODO 
- How do public/private keys work
- Working with certificates
- How does an ssl handshake work
```
Website: Search for explanations online, there's enough
```  
- How do I setup basic user authentication on my REST API's
```
Course: Security essentials for java developers (internal)  
Exercise: set up a client and a server and set up a secure connection between them + make it fail with own Certificate authority
Exercise: https://gist.github.com/Soarez/9688998
Book: Computer networks (Tanenbaum)
```    
### Basic os skills
> Rationale : TODO 
- user mgt
    - useradd
    - usermod
- network mgt
    - see basic netwerking skills
- process mgt
    - ps
    - (n)top
    - jobs
    - kill
- basic tooling
    - bash / zsh
    - vi
- troubleshooting
```
Website: https://dev.to/awwsmm/101-bash-commands-and-tips-for-beginners-to-experts-30je
Website: https://linuxjourney.com/
man bash
```
### REST
> Rationale : TODO 
```
Book:[Rest in Practice - Jim Webber]http://shop.oreilly.com/product/9780596805838.do](http://shop.oreilly.com/product/9780596805838.do)
```
### frontend javascript, angular
> Rationale : TODO 
```
Website : [angular tutorial](https://angular.io/tutorial)
Course : Javascript - Basic + advanced (internal), Angular 6 Master Class (external Thoughtram)
```
### Basic database understanding
> Rationale : TODO 
By which we mean:
- SQL
- NOSQL
- JDBC
- JPA
- ACID/BASE
```
Exercise: Create your own full stack application
```
### Spring
> Rationale : TODO 
```
Exercise: Create your own application
Book: Spring in action
```
### Visualisatie
> Rationale : TODO 
```
Course: Visualisation for Beginners (internal)
Learn about UML
```
### Design uitwerken voor een probleem op te lossen
> Rationale : TODO 
```
On the job
```
### Basic architectural skills
> Rationale : TODO 
By which we mean:
- C4 
- architectural patterns
- distributed systems
```
Book: Software architecture for developers (Simon Brown)
Book: Beautiful architecture
Book: Building microservices
Book: Microservice architecture
```
### Functional programming
> Rationale : TODO 
```
Exercise: Scalatron
Book: Structure and Interpretation of computer programs
```
### Planning
> Rationale : TODO 
### Working in a structured way
> Rationale : TODO 
### Being able to work in different abstraction levels
> Rationale : TODO 
```
See DDD
```
### Debugging skills
> Rationale : TODO 
Understanding tooling, Remote debug, ...
### Presentation skills
> Rationale : TODO 
```
Course: www.imboorling.be (external)
Book: Presentation Zen
```
## Soft Skills
### Agile
> Rationale : TODO 
```
Course: Agile Introduction (internal)
```
### Giving feedback
> Rationale : TODO 
```
Exercise: feedback kata (internal) (https://github.com/cegeka/feedback-exercise)
```
### Accepting feedback
> Rationale : TODO 
```
Exercises: Feedback exercise sessions (coach retreat?)
```
### Critical thinking
> Rationale : TODO 
### Courage
> Rationale : TODO 
```
Book: Feel the fear and do it anyway
```
### Contextual communication (adapting communication depending on who your talking to)
> Rationale : TODO 
Communicating to someone with different knowledge, e.g. explaining a stacktrace to a customer
Adapting communication depending on the person you are talking to.
```
Course: Insights discovery
Course: Communicatie met impactie (extern)
```
### Taking Ownership
> Rationale : TODO 
```
Website: The responsibility process: https://www.christopheravery.com/responsibility-process
Website: Getting things done: https://gettingthingsdone.com/
Book: Change your questions change your life
Book: Turn the ship around
```
### Leadership
> Rationale : TODO
```
Conference: Lead Dev
```
