#TODO
- Naar het engels vertalen
- Layout
- Omschrijving bij elk hoofdstuk
- Moeilijkheidsgraad toevoegen (basic of advanced)
- Voorstellen in gilde meeting

# Doel van dit document
Developers helpen te groeien, door:
- duidelijk te maken welke vaardigheden we verwachten van een developer
- materiaal aan te bieden dat kan helpen deze vaardigheden te verbeteren

# Vaardigheden en hoe ze te verbeteren
## Algemeen
 Cegeka heeft een licentie van [**pluralsight**](https://www.pluralsight.com/) een onlineplatform met videocursussen.
 
 Als je in iets wil bijleren kan je altijd daar kijken.
## Hard skills
### TDD
    Oefeningen: Code kata's doen (website, sessie), game of life, TDD as if you meant it
    Boeken: TDD (Kent Beck)
    Cursus: Agile Software Engineering
### Java architectuur
	Oefeningen: Maak een memory leak en hang er een profiler aan.
	Website: Java memory architectuur online opzoeken
	Boeken: Effective java
	Conferentie: Devoxx
	Video's: Devoxx talks
### Java api
	Website: Code wars, api reference website
	Boeken: Effective java
### Enterprise application
Hiermee bedoelen onderwerpen zoals:
* Transactionaliteit 
* Security
* Messaging
* Web tier
* Dependency injection
* AOP
* Persistence
    >Oefeningen: Zelf spring boot opzetten met alles hierboven  
    Website: https://docs.oracle.com/javaee/7/tutorial/index.html, getting started van spring  
    Cursus: spring cursus (pivotal)  
    Boeken: Patterns of enterprise application architecture (Martin Fowler).
### Refactoring
	Boeken: Refactoring 1 of 2  (Martin Fowler).
	Oefening: movierental (oefening van refactoring), kata's
	Cursus: Agile software engineering
### Clean code
	Boeken: clean code, Code complete, pragmatic programmer, extreme programming explained
### DDD
	Boeken: Blauwe boek, DDD quickly (https://www.infoq.com/minibooks/domain-driven-design-quickly), Rode boek, DDD distilled; Patterns, principles and practices of DDD; CQRS journey guide (https://docs.microsoft.com/en-us/previous-versions/msp-n-p/jj554200(v=pandp.10))
	Conference: DDDEU
	Workshops: georganiseerd door DDDEU (zie hun website), Greg Young's workshop
	(to validate) Pluralsight path: https://www.pluralsight.com/paths/domain-driven-design
### Continuous delivery
	Boeken: Continuous delivery, Phoenix Project, Release it!
	Conference: Devops summit
    Cursus : Devops (internal)
    Book: The site reliability
### Continuous integration
    Oefening: Zelf een jenkins opzetten
    Opzoeken: (wim zoekt het op)
    Boeken: Continuous delivery
### Enterprise integration patterns
>Boeken : 
[Enterprise Integration Patterns - Gregor Hohpe Bobby Woolf](https://www.enterpriseintegrationpatterns.com/)
[Camel in action - Claus Ibsen Jonathan Anstey](https://www.manning.com/books/camel-in-action-second-edition)  
>Website : https://www.enterpriseintegrationpatterns.com/patterns/messaging/
>Website : https://spring.io/projects/spring-integration

### Design patterns
	Boeken: Head First Design Patterns, Design Patterns (Elements of Reusable Object-Oriented Software)
	Website: https://refactoring.guru/design-patterns/catalog
### Basic computer skills
    Weten hoe een computer werkt : cpu - ram - disk 
    kennis over hoe computerprogramma's werken
    Website: https://gist.github.com/jboner/2841832
    Presentatie: ???cegeka school???
### Basic netwerking skills
    basiskennis layered networking (TCP/IP)
    in staat zijn te troubleshooten bij netwerkproblemen
    tcp handshaking procedure
    application protocols : http, https, ftp
    netwerking tools kunnen gebruiken : ssh, telnet, ss, netstat, ping, nslookup, ...
### Security
    - How do public/private keys work
    - Working with certificates
    - How does an ssl handshake work
        > Website: Search for explanations online, there's enough  
    - How do I setup basic user authentication on my REST API's
    > Cursus: Security essentials for java developers (internal)  
      Exercise: set up a client and a server and set up a secure connection between them + make it fail with own Certificate authority
      Exercise: https://gist.github.com/Soarez/9688998
      Book: Computer networks Tanenbaum
### Basic os skills
    user mgt
        useradd
        usermod
    network mgt
        zie basic netwerking skills
    process mgt
        ps
        (n)top
        jobs
        kill
    basic tooling
        bash / zsh
        vi
    troubleshooting
    >Website: https://dev.to/awwsmm/101-bash-commands-and-tips-for-beginners-to-experts-30je
    >Website: https://linuxjourney.com/
    >man bash
### REST
    Boeken:[Rest in Practice - Jim Webber]http://shop.oreilly.com/product/9780596805838.do](http://shop.oreilly.com/product/9780596805838.do)
### frontend javascript, angular
    Website : [angular tutorial](https://angular.io/tutorial)
    Cursus : Javascript - Basic + advanced (internal), Angular 6 Master Class (external Thoughtram)
### Basic database understanding
Hiermee bedoelen we onderwerpen zoals:
- SQL
- NOSQL
- JDBC
- JPA
- ACID/BASE
    >Oefening: Zet sample applicatie op
### Spring
>Oefening: Zelf applicatie opzetten
Boeken: Spring in action
### Visualisatie
	Cursus: Visualisation for Beginners (internal)
	Learn about UML
### Design uitwerken voor een probleem op te lossen
    On the job
### Basic architectural skills
Hiermee bedoelen we onderwerpen zoals:
- C4 
- architectural patterns
- gedistribueerde systemen
    >Book: Software architecture for developers (Simon Brown)
    >Book: Beautiful architecture
    >Book: Building microservices
    >Book: Microservice architecture 
### Functional programming
    Exercise: Scalatron
    Book: Structure and Interpretation of computer programs
### Planning
### Gestructureerd werken
### Abstraheren
    See DDD
### Debugging skills
Understanding tooling, Remote debug, ...
### Presentation skills
	Externe cursus: www.imboorling.be
	Book: Presentation Zen
## Soft Skills
### Agile
	Cursus: Agile Introduction (internal)
### Feedback geven
    Oefening: feedback kata (internal) *nog beschikbaar stellen*
### Feedback accepteren
    Exercises: Feedback exercise sessions (coach retreat?)
### Kritische geest
### Courage
    Book: Feel the fear and do it anyway
### Contextuele communicatie (uitleg aanpassen aan uw doelpubliek, aan uw doel)
Taal aanpassen aan kennis van doel bijvoorbeeld geen stacktrace uitleggen aan klant
Taal aanpassen aan persoon van doel
    Cursus: Insights discovery
    Cursus: Communicatie met impactie (extern)
### Ownership nemen
    The responsibility process: https://www.christopheravery.com/responsibility-process
    Getting things done: https://gettingthingsdone.com/
    Book: Change your questions change your life
    Book: Turn the ship around