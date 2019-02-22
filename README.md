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
Exercise: Do code kata's (website, sessions, meetups) |basic|
Exercise: Game of life |basic|
Exercise: TDD as if you meant it |basic|
Book: TDD (Kent Beck) |basic|
Course: Agile Software Engineering |basic|
```

### Java architecture
> Rationale : Knowing how java gets executed and behaves at runtime helps a developer to design better applications. What are the problems you run into when doing too much recursion ? How can you solve garbage collection performance problems ?
```
Exercise: Create a memory leak and inspect with a profiler. |basic|
Website: Lookup java memory architecture online |basic|
Book: Effective java --> TODO : not really java-architecture book |basic|
Conference: Devoxx |basic|
Video: Devoxx talks |basic|
```
### Java api
> Rationale : This is the first level on top of the syntax and the grammar of java. Suppose you're learning a new speaking language (e.g. spanish) you won't be proficient by learning only the grammar, you have to learn common words, common language structure. The java api is the equivalent of this : to become an efficient developer you have to study and exercise on the java api.
```
Website: Code wars |basic|
Website: Api reference website |basic|
Book: Effective java |basic|
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
Exercise: Create your own full stack spring boot application  |advanced?|
Website: https://docs.oracle.com/javaee/7/tutorial/index.html |basic|
Website: getting started Spring |basic|
Course: spring cursus (pivotal) |basic| 
Book: Patterns of enterprise application architecture (Martin Fowler). |advanced|
```
### Refactoring
> Rationale : When writing software for complex business problems, you can assume that your model of the business won't be correct the first time. With refactoring you get a set of techniques and patterns, to redesign your model safely and more efficiently.  
```
Book: Refactoring 1 of 2  (Martin Fowler). |basic|
Exercise: movierental (refactoring exercise), kata's |basic|
Course: Agile software engineering |basic|
Website: https://refactoring.guru/ |basic|
```
### Clean code
> Rationale : This is all about clear communication, again writing software that is read and modified by a lot of people over a period of many years requires the need for clear communication. Clean code gives good practices to ensure that code is well written and easier to maintain and understand. 
```
Book: clean code |basic|
Book: Code complete |basic|
Book: pragmatic programmer, extreme programming explained |basic|
```
### DDD
> Rationale :  
```
Book: Blue book |advanced|
Book: DDD quickly (https://www.infoq.com/minibooks/domain-driven-design-quickly) |advanced|
Book: Red book |advanced|
Book: DDD distilled |advanced|
Book: Patterns, principles and practices of DDD |advanced|
Book: CQRS journey guide (https://docs.microsoft.com/en-us/previous-versions/msp-n-p/jj554200(v=pandp.10)) |advanced|
Conference: DDDEU |advanced|
Workshop: DDDEU workshop (see https://training.dddeurope.com/)  |advanced|
Workshop: Greg Young's workshop |advanced|
(to validate) Pluralsight path: https://www.pluralsight.com/paths/domain-driven-design |advanced?|
```
### Continuous delivery
> Rationale : TODO 
```
Book: Continuous delivery |advanced|
Book: Phoenix Project |basic|
Book: Release it! |advanced|
Conference: Devops summit |?|
Course : Devops (internal) |advanced|
Book: The site reliability |?|
```
### Continuous integration
> Rationale : TODO 
```
Exercise: Installing your own jenkins |basic|
Research: (wim will look it up) 
Book: Continuous delivery |advanced|
```
### Enterprise integration patterns
> Rationale : TODO 
```
Book : [Enterprise Integration Patterns - Gregor Hohpe Bobby Woolf](https://www.enterpriseintegrationpatterns.com/) |advanced|
Book : [Camel in action - Claus Ibsen Jonathan Anstey](https://www.manning.com/books/camel-in-action-second-edition)  |advanced|
Website : https://www.enterpriseintegrationpatterns.com/patterns/messaging/ |advanced|
Website : https://spring.io/projects/spring-integration |?|
```
### Design patterns
> Rationale : TODO 
```
Book: Head First Design Patterns, Design Patterns (Elements of Reusable Object-Oriented Software)
Website: https://refactoring.guru/design-patterns/catalog |basic|
```
### Basic computer skills
> Rationale : TODO 
- Knowledge on how a computer functions: cpu - ram - disk
- Knowledge how programs work 
```
Website: https://gist.github.com/jboner/2841832 |?|
Presentatie: ???cegeka school???
```
### Basic netwerking skills
> Rationale : TODO 
- basic knowledge on layered networking (TCP/IP) |basic|
- troubleshooting network problems |advanced|
- tcp handshaking procedure |advanced|
- application protocols : http, https, ftp |advanced|
- using networking tools : ssh, telnet, ss, netstat, ping, nslookup, ... |advanced|
### Security
> Rationale : TODO 
- How do public/private keys work |advanced|
- Working with certificates |advanced|
- How does an ssl handshake work |advanced|
```
Website: Search for explanations online, there's enough
```  
- How do I setup basic user authentication on my REST API's
```
Course: Security essentials for java developers (internal) |basic|
Exercise: set up a client and a server and set up a secure connection between them + make it fail with own Certificate authority |advanced|
Exercise: https://gist.github.com/Soarez/9688998 |?|
Book: Computer networks (Tanenbaum) |advanced|
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
Website: https://dev.to/awwsmm/101-bash-commands-and-tips-for-beginners-to-experts-30je |?|
Website: https://linuxjourney.com/ |?|
man bash
```
### REST
> Rationale : TODO 
```
Book:[Rest in Practice - Jim Webber]http://shop.oreilly.com/product/9780596805838.do](http://shop.oreilly.com/product/9780596805838.do) |basic|
```
### frontend javascript, angular
> Rationale : TODO 
```
Website : [angular tutorial](https://angular.io/tutorial) |basic?|
Course : Javascript - Basic + advanced (internal), Angular 6 Master Class (external Thoughtram) |basic + advanced|
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
Exercise: Create your own full stack application |advanced?|
```
### Spring
> Rationale : TODO 
```
Exercise: Create your own application |basic|
Book: Spring in action |basic|
```
### Visualisatie
> Rationale : TODO 
```
Course: Visualisation for Beginners (internal) |basic|
Learn about UML |basic|
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
Book: Software architecture for developers (Simon Brown) |advanced|
Book: Beautiful architecture |?|
Book: Building microservices |advanced|
Book: Microservice architecture |?|
```
### Functional programming
> Rationale : TODO 
```
Exercise: Scalatron |basic|
Book: Structure and Interpretation of computer programs |?|
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
Course: www.imboorling.be (external) |?|
Book: Presentation Zen |?|
```
## Soft Skills
### Agile
> Rationale : TODO 
```
Course: Agile Introduction (internal) |basic|
```
### Giving feedback
> Rationale : TODO 
```
Exercise: feedback kata (internal) (https://github.com/cegeka/feedback-exercise) |basic|
```
### Accepting feedback
> Rationale : TODO 
```
Exercises: Feedback exercise sessions (coach retreat?) |basic|
```
### Critical thinking
> Rationale : TODO 
### Courage
> Rationale : TODO 
```
Book: Feel the fear and do it anyway |?|
```
### Contextual communication (adapting communication depending on who your talking to)
> Rationale : TODO 
Communicating to someone with different knowledge, e.g. explaining a stacktrace to a customer
Adapting communication depending on the person you are talking to.
```
Course: Insights discovery |basic|
Course: Communicatie met impactie (extern) |basic|
```
### Taking Ownership
> Rationale : TODO 
```
Website: The responsibility process: https://www.christopheravery.com/responsibility-process |basic|
Website: Getting things done: https://gettingthingsdone.com/ |basic|
Book: Change your questions change your life |?|
Book: Turn the ship around |?|
```
### Leadership
> Rationale : TODO
```
Conference: Lead Dev |advanced|
```
