# Table of contents
- [TODO <a name="TODO"></a>](#todo--a-name--todo----a-)
- [Goal of this document](#goal-of-this-document)
- [Skills & Tools](#skills---tools)
  * [General](#general)
  * [Hard skills](#hard-skills)
    + [TDD](#tdd)
    + [Build tools](#build-tools)
    + [Java architecture |advanced|](#java-architecture--advanced-)
    + [Java api](#java-api)
    + [Enterprise application](#enterprise-application)
    + [Refactoring](#refactoring)
    + [Clean code](#clean-code)
    + [DDD |advanced|](#ddd--advanced-)
    + [Devops](#devops)
    + [Continuous integration](#continuous-integration)
    + [Enterprise integration patterns](#enterprise-integration-patterns)
    + [Design patterns](#design-patterns)
    + [Basic computer skills](#basic-computer-skills)
    + [Basic netwerking skills](#basic-netwerking-skills)
    + [Security](#security)
    + [Basic os skills](#basic-os-skills)
    + [REST](#rest)
    + [frontend javascript, angular](#frontend-javascript--angular)
    + [Basic database understanding](#basic-database-understanding)
    + [Spring](#spring)
    + [Visualisatie](#visualisatie)
    + [Design uitwerken voor een probleem op te lossen](#design-uitwerken-voor-een-probleem-op-te-lossen)
    + [Basic architectural skills](#basic-architectural-skills)
    + [Functional programming](#functional-programming)
    + [Planning](#planning)
    + [Working in a structured way](#working-in-a-structured-way)
    + [Being able to work in different abstraction levels](#being-able-to-work-in-different-abstraction-levels)
    + [Debugging skills](#debugging-skills)
    + [Presentation skills](#presentation-skills)
  * [Soft Skills](#soft-skills)
    + [Agile](#agile)
    + [Giving feedback](#giving-feedback)
    + [Accepting feedback](#accepting-feedback)
    + [Critical thinking](#critical-thinking)
    + [Courage](#courage)
    + [Contextual communication (adapting communication depending on who your talking to)](#contextual-communication--adapting-communication-depending-on-who-your-talking-to-)
    + [Taking Ownership](#taking-ownership)
    + [Leadership](#leadership)

# TODO <a name="TODO"></a>
- Rationale for each chapter
- Present this page to the java guild
- To people managers
- Table of contents
- PDF op portal zetten
- Mindmap maken van deze pagina

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

### Build tools
> Rationale : With todays complexity of software, building software by hand is almost impossible. Build tools help building your artifacts easier. Since continuous delivery and continuous deployment give you fast feedback, you depend daily several times on the build tools. Investing in knowledge buildup is a necessity to become a proficient developer.
- Dependency management
- Building artifacts
- Running tests
- Classpath management
- Automation
```
Course: Devops (internal) |advanced|
Tool: Gradle |basic|
```

### Java architecture |advanced|
> Rationale : Knowing how java gets executed and behaves at runtime helps a developer to design better applications. What are the problems you run into when doing too much recursion ? How can you solve garbage collection performance problems ?
```
Exercise: Create a memory leak and inspect with a profiler.
Website: Lookup java memory architecture online
Conference: Devoxx
Video: Devoxx talks
```
### Java api
> Rationale : This is the first layer on top of the syntax and the grammar of java. Suppose you're learning a new speaking language (e.g. spanish) you won't be proficient by learning only the grammar, you have to learn common words, common language structures. The java api is the equivalent of this : to become an efficient developer you have to study and exercise on the java api.
```
Website: Code wars |basic|
Website: Api reference website |basic|
Book: Effective java |basic|
```
### Enterprise application
> Rationale: Typical cross-cutting concerns like transactionality and security are (almost) always necessary when writing software for a customer. 

This includes
* Transactionality 
* Security
* Messaging
* Web tier
* Dependency injection
* AOP
* Persistence
```
Exercise: Create your own full stack spring boot application  |advanced|
Website: https://docs.oracle.com/javaee/7/tutorial/index.html |basic|
Website: getting started Spring |basic|
Course: spring course (pivotal) |basic| 
Book: Patterns of enterprise application architecture (Martin Fowler). |advanced|
```
### Refactoring
> Rationale : When writing software for complex business problems, you can assume that your model of the business won't be correct the first time. With refactoring you get a set of techniques and patterns to redesign your model safely and more efficiently.  
```
Book: Refactoring (Martin Fowler). |basic|
Book: Your code as a crime scene |basic|
Exercise: movierental (refactoring exercise), kata's |basic|
Course: Agile software engineering |basic|
Website: https://refactoring.guru/ |basic|
Tool: IDE (refactorings/shortcuts)
```
### Clean code
> Rationale : This is all about clear communication, again writing software that is read and modified by a lot of people over a period of many years requires the need for clear communication. Clean code gives good practices to ensure that code is well written and easier to maintain and understand. 
```
Book: clean code |basic|
Book: Code complete |basic|
Book: pragmatic programmer, extreme programming explained |basic|
```
### DDD |advanced|
> Rationale : When tackling a complex business domain, it can be beneficial to use the techniques of Domain driven design. This adds a cost to development but the gains are massive for every developer. DDD gives a set of patterns and techniques on different abstraction levels for tackling (business) complexity in the heart of software. 
```
Book: Blue book (https://www.amazon.com/dp/0321125215)
Book: DDD quickly (https://www.infoq.com/minibooks/domain-driven-design-quickly)
Book: Red book (https://www.amazon.com/Implementing-Domain-Driven-Design-Vaughn-Vernon/dp/0321834577)
Book: Green book (https://www.amazon.com/dp/0134434420/)
Book: Patterns, principles and practices of DDD
Book: CQRS journey guide (https://docs.microsoft.com/en-us/previous-versions/msp-n-p/jj554200(v=pandp.10))
Conference: DDDEU
Workshop: DDDEU workshop (see https://training.dddeurope.com/) 
Workshop: Greg Young's workshop
(to validate) Pluralsight path: https://www.pluralsight.com/paths/domain-driven-design
```
### Devops
> Rationale : When you want to run and operate rapidly-changing systems at scale, you need a cross-disciplanary community. This community uses a set of practices that promote systems-thinking (global vs local optimization), fast feedback and a culture of continual experimentation and learning.
```
Book: Continuous delivery |advanced|
Book: Phoenix Project |basic|
Book: Release it! |advanced|
Conference: Devops summit |?|
Course : Devops (internal) |advanced|
Book: The site reliability |?|
Tool: Docker
```
### Continuous integration
> Rationale : When building software in a team, you will want short feedback cycles. Maybe your changes are breaking with some other colleague's changes.  
```
Exercise: Installing your own jenkins |basic|
Research: [4 branching workflows for git](https://medium.com/@patrickporto/4-branching-workflows-for-git-30d0aaee7bf)
          [feature branch](https://martinfowler.com/bliki/FeatureBranch.html)
          [a successful git branching model](https://nvie.com/posts/a-successful-git-branching-model/)
          [gitflow is poor branching model hack](https://hackernoon.com/gitflow-is-a-poor-branching-model-hack-d46567a156e7)
          [gitflow considered harmful](https://www.endoflineblog.com/gitflow-considered-harmful) 
Book: Continuous delivery |advanced|
Tool: Git
Tool: Jenkins
```
### Enterprise integration patterns
> Rationale : When writing enterprise applications you often have to integrate with other applications or services. You'll have to deal with asynchronym partial failures, incompatible data models, ... Enterprise Integration patterns offers a pattern language for this problem space.
```
Book : [Enterprise Integration Patterns - Gregor Hohpe Bobby Woolf](https://www.enterpriseintegrationpatterns.com/) |advanced|
Book : [Camel in action - Claus Ibsen Jonathan Anstey](https://www.manning.com/books/camel-in-action-second-edition)  |advanced|
Website : https://www.enterpriseintegrationpatterns.com/patterns/messaging/ |advanced|
Website : https://spring.io/projects/spring-integration |?|
```
### Design patterns
> Rationale : Design patterns are formalized good practices that the programmer can use to solve common problems when designing an application or system. The keyword here is "formalized", in order to have a common vocabulary between developers, you'll have to learn the correct use of a design pattern by learning it, not just repeating it from other source code, then you'll have not enough profound knowledge on how a design pattern is a generalized solution.
```
Book: Head First Design Patterns, Design Patterns (Elements of Reusable Object-Oriented Software)
Website: https://refactoring.guru/design-patterns/catalog |basic|
```
### Basic computer skills
> Rationale : You don't have to become an expert on computer architecture, but having some basic knowledge on how a computer works can aid in become a better programmer.  
- Knowledge on how a computer functions: cpu - ram - disk
- Knowledge how programs work 
```
Website: https://gist.github.com/jboner/2841832 |?|
Presentatie: ???cegeka school???
```
### Basic networking skills
> Rationale : Todays computer programs communicate via networks to other programs. Whenever an application at runtime can't communicate with other programs, you'll have to be able to do some basic troubleshooting.
- basic knowledge on layered networking (TCP/IP) |basic|
- troubleshooting network problems |advanced|
- tcp handshaking procedure |advanced|
- application protocols : http, https, ftp |advanced|
- using networking tools : ssh, telnet, ss, netstat, ping, nslookup, ... |advanced|
### Security
> Rationale : Learn the basic concepts : identification, authentication, authorization. Learn the OWASP top ten vulnerabilities. Learn about social hacking. 
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
