# Spring Boot RESTful Quickstart Maven Archetype

- Notification : The project is currently unfinished.

Summary
-------
The project is a Maven archetype for Spring Boot RESTful application.

Install archetype locally
-------------------------

To install the archetype in your local repository execute the following commands:

```bash
    git clone https://github.com/LawrenceAhn/spring-boot-restful-quickstart-archetype.git
    cd spring-boot-restful-quickstart-archetype
    mvn clean install
```

Create a project from a local repository
----------------------------------------

Create a new empty directory for your project and navigate into it and then run:

```bash
    mvn -DarchetypeCatalog=local archetype:generate \
      -DarchetypeGroupId=com.zuperztarahn \
      -DarchetypeArtifactId=spring-boot-restful-quickstart-archetype \
      -DarchetypeVersion=0.0.1 \
      -DgroupId={my.groupId} \
      -DartifactId={my.artifactId}
```