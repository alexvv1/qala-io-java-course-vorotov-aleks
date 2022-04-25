# qala-io-java-course


### Maven
Step 3 - Debugging
https://maven.apache.org/surefire/maven-surefire-plugin/examples/debugging.html
- mvn -Dmaven.surefire.debug test
- mvn -Dmaven.surefire.debug="-agentlib:jdwp=transport=dt_socket,server=y,suspend=y,address=localhost:8000" test
- mvnDebug -DforkCount=0 test

Step 4 - Inheritance and Aggregation

mvn flags

- -pl - Specifies the modules to include or exclude from a build.  mvn -pl '!core,app1' clean install
- -am - Builds the specified modules, and any of their dependencies in the reactor.
- -amd - Builds the specified modules, and any that depend on them.