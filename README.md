# testing-gatling

## Begin
Create a new project in IDEA ( File > New Project ...)
Make sure you select a maven module
create project

Add the gatling archetype by clicking Add archetype... on the next screen (if you don't already have it)

Archetype working now:
```
GroupId: io.gatling.highcharts
ArtifactId: gatling-highcharts-maven-archetype
Version: 3.1.1
```
add archetype

Select the newly create archetype and click next
Click Finish button to complete project creation
finish project

If all goes well, the project will be set up and ready to use

Recorder.scala - run this to launch the gatling recorder to record simulations
Engine.scala - run this to execute existing simulations


## Run a Simulation with Maven
See https://gatling.io/docs/current/extensions/maven_plugin/#coexisting-with-scala-maven-plugin
the simulation at test phase
```
<phase>test</phase>
```
run
```
mvn gatling:test
```

## Reviewing the Result
Open the index.html 