# multiple kjars

Small demo of one drools kjar including another kjar as a dependency. 

Implementation of https://access.redhat.com/solutions/966573

Kjars adapted from maven drools archetype project.

## To run:

```
cd drools-project-b
mvn clean install
cd ../drools-project-a
mvn clean test
```

## Interesting parts

### drools-project-a/pom.xml
### drools-project-a kmodule.xml
### drools-project-b kmodule.xml
### drools-project-a rulesA.drl
### drools-project-b rulesB.drl
### drools-project-a RulesTest.java
