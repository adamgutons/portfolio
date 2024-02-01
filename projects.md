---
layout: default
---

[Projects](./projects.html).
[About](./about-me.html).
[Github](https://github.com/adamgutons/){:target="_blank"}.
[Resume](./assets/resume/resume.pdf){:target="_blank"}.


# Projects

### Python

#### [geotransform-tools](https://github.com/adamgutons/geotransform-tools){:target="_blank"}

>A python application that provides an interface for transforming geospatial coordinates from one spatial reference system 
to another based on a user provided EPSG value or PROJ string (the [PROJ](https://proj.org/en/9.3/) engine powers the 
transformation functions).  The application also provides python wrapper classes based on OGR Point, Line, and Polygon functionality.
The wrapper classes use attribute getters to mimic the ESRI geometry classes, and allow for similar attribute retrieval,

+ i.e. `geometry.points, geometry.firstPoint, geometry.X, geometry.spatialReference`

### Java

#### [filegdb-web-builder](https://github.com/adamgutons/filegdb-web-builder){:target="_blank"}

>A simple Spring Boot application that allows users to configure a [file geodatabase](https://pro.arcgis.com/en/pro-app/latest/help/data/geodatabases/manage-file-gdb/file-geodatabases.htm)
template from a web browser or with the provided API.  The API will return a base64 string representation of the zipped
file .gdb that can be unpacked and used with other geospatial workflows.  Eventual updates to include:

+ Saving template .gdb and template configuration information (datasets, feature classes, fields) to a relational database
+ Allowing users to populate the template with spatial and tabular data
+ Saving data entry to a relational database


#### [taco-cloud](https://github.com/adamgutons/taco-cloud){:target="_blank"}

>This is a simple CRUD application based on [Spring In Action](https://livebook.manning.com/book/spring-in-action-sixth-edition/spring-in-action/)
from Manning. I have used this app mostly as a Java and Spring Boot playground and most recently:

+ Implemented service patterns for handling business logic and repository interaction
+ Implemented Lombok annotations to favor constructor injection over parameter injection
+ Replaced logic with streams where applicable


[back](./)
