# Vision Paper

* 10.01 Deadline for Vision Paper
* 13.01 Presentation of Milestone 1

## Group-B name and members:

Alex Hofer, Alex Wirth, Franziska Holauf, Fabian Oraze, Larissa Krainer

### Useful links:
* https://github.com/Mitschi/lecture-planner 
* https://rapidapi.com/collection/list-of-free-apis 
* https://rapidapi.com/wirefreethought/api/geodb-cities/ 



## Short project description (1 paragraph)

<p>This project is about an advanced person manager, where you can create relationships(friendships) between persons. You can add, delete, update persons and add relationships between them. Also some GeoData will be used, so that you will get a recommendation of persons which live next to you. Another idea is that there will be a reminder for birthday of your friends with an service where you will be able to send birthday whishes. And some more features, every feature is planned as a single service, and this services will interact with each other. </p>
<p><b>To sum up:</b><br>
Friendsify is for every Informatic person who has no friends. Because of the pandemic a lot of us feel lonely so we decided to create a tool to connect to other lonely people.<br>
Spring project, every group member implements a module („service“) and finally we put them together.<br>
Nice to have: deploy in Docker</p>

### Main goals/functionality (epics in Scrum; table)
* Birthday Service = Birthday reminder service + Birthday wishes send service (uses E-Mail Service) 
* Joke Service = to send a Joke to your friends (uses E-Mail Service)
* E-Mail service = send messsage(s) (like birthday wishes and Jokes)
* Person management service (add, delete, relationships, change/update information), like REST 
* Friends management service (add, delete, timeout/blocking, change/update information), likeREST
* Recommendation Service = recommendation of persons through GeoData API, Birthday ...
* Front-End-Service


### Technical plan (which tools/frameworks)

* Java for every service --> because of Spring and experience
* Git --> no alternative (most common versioning tool)
* Apache Maven --> experience
* GitHub Actions instead of TravisCI --> because GitHub Actions is better integrated in GitHub and its newer
* Spring Framework (Spring Core, Spring Data, Spring Boot,…) --> because it is more convenient/ the best fit for implementing REST similar projects
* PostgreSQL --> because its open source and experience
* JUnit --> because we have to test and in Java its the most common used 
* SonarCloud --> experience, we now this from other lectures
* Docker --> used in other lectures, no alternative for deployment
* JMeter --> proposed tool in ASE for performance tests
