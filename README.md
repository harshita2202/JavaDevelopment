-> src/main/java  → code Spring Boot RUNS
src/main/resources → config Spring Boot READS
src/test/java → code Spring Boot TESTS
target → code Maven GENERATES

-> 
 to compile = mvn compile
 to run = mvn spring-boot: run

 ->
 parent
  ├─ manages versions & plugins
dependencies
  ├─ libraries your code uses
plugins
  ├─ tools Maven uses
lifecycle
  ├─ order of execution
scopes
  ├─ when dependencies are visible
profiles
  ├─ environment-specific configs

->
plugies are use to generate FAT JAR file , which includes all the dependencies and help the app to run.
first - mvn clean
second - mvn package
third - java -jar target\maven-lab-1.0.0.jar
 

