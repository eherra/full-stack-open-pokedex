## Java CI/CD

The team decided to work with the new project with Java, specifically Java 11.

For their CI/CD setup they have to choose the tools for the pipeline for checking e.g. quality and building.

For quality assurance, they chose "Checkstyle" which is a static codeanalysis tool (like ESlint). Unit testing is handled by JUnit, and integration tests are done
with Robot framework which can be put on pipeline to be run whenever it's convenient. Building the project they decided to use Maven, which uses pom.xml file to 
e.g. set the libraries and versions of them and other meta data.

There's a range of other CI tools to consider than Jenkins or GitHub Actions for example Buddy, TeamCity, Travis CI, GitLab CI and Circle CI. From these the most used
and famous one is Jenkins which is really handy and has lot of features and flexibility.

The last thing for the team to decided either to use cloud-based enviroment or self-hosted one. 

The team is small (6 people) and the application needs to be released soon, so with these facts cloud-based enviroment is way to go. It's less hassle and can be setup 
quickly compared to own self-hosted server where lot of knowledge and possible problems may occur. Also the software build is not that large and no personal secret data
held which supports the cloud-based decision.
