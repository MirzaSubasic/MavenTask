# MavenTask

https://www.tutorialspoint.com/maven/maven_plugins.htm - maven tutorial

Task 7

    a.  build project using: mvn install
    b.  to run all test type: mvn test
    c.  jar file for child 1 is in: C:\Users\smirza\.m2\repository\org\example\child1\1.0-SNAPSHOT
        jar file for child 2 is in: C:\Users\smirza\.m2\repository\org\example\child2\1.0-SNAPSHOT


Task 8 - update version

    1. mvn release:update-versions
    2. mvn install
    
Task 9 - jars are now called

    1. child1-1.1-SNAPSHOT.jar
    2. child2-1.1-SNAPSHOT.jar


Created webhook which will notify jenkins about all events in this repository
