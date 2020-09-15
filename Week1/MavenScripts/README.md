## Maven SCripts / Commands

### To List out all available goals

`mvn help:describe –Dplugin=eclipse`

### To leverage local maven repository within a project

`mvn -Dmaven.repo.local=$HOME/.m2 clean install`

#### Advantages of local repository

- Single central reference repository for all dependent software libraries rather than several independent local libraries.
- Fasten the clean build process while using local repositories.


### To extract and save build logs to a file

`mvn clean build > maven.log`

### make maven work offline

`mvn –o clean package`