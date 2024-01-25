---
layout: default
---

[Projects](./projects.html).
[About](./about-me.html).
[Github](https://github.com/adamgutons/){:target="_blank"}.
[Resume](./assets/resume/resume.pdf){:target="_blank"}.


# Projects

### [filegdb-web-builder](https://github.com/adamgutons/filegdb-web-builder)

A simple Spring Boot application that allows users to configure a [file geodatabase](https://pro.arcgis.com/en/pro-app/latest/help/data/geodatabases/manage-file-gdb/file-geodatabases.htm)
template from a web browser or with the provided API.  The API will return a base64 string representation of the zipped
file .gdb that can be unpacked and used geospatial workflows.  Eventual updates to include:

+ Saving template .gdb and template configuration information (datasets, feature classes, fields) to a relational database
+ Allowing users to populate the template with spatial and tabular data
+ Saving data entry to a relational database

### [taco-cloud](https://github.com/adamgutons/taco-cloud)

This is a simple CRUD application based on [Spring In Action](https://livebook.manning.com/book/spring-in-action-sixth-edition/spring-in-action/)
from Manning. I have used this app mostly as a Java and Spring Boot playground and most recently:

+ Implemented service patterns for handling business logic and repository interaction
+ Implemented Lombok annotations to favor constructor injection over parameter injection
+ Replaced logic with streams where applicable


[back](./)
