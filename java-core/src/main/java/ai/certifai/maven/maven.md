# Gist of Java with Apache Maven

## Chapter 1 Introduction of Apache Maven

### 1.1 Installation of Apache Maven 

Download and install Apache Maven from [here](https://maven.apache.org/download.cgi).  

Verify the installation through 
```
mvn -version
```
<p align="center">
  <img width="700" height="500" src="metadata/maven_0.png">
</p>  

### 1.2 What is Apache Maven

- Apache Maven is a **project management tool** primarily for Java projects. 



- Apache Maven manage a project's build, reporting and documentation from a central piece of information 


## Chapter 2 Dive in Java with Apache Maven

- The fundamental component to manage dependencies is by using pom.xml - project object model (POM). 

### Single-Module Project

- With pom.xml, dependency management is easy in defining, creating and maintaining reproducible environments with well-defined classpaths and library versions.

<p align="center">
  <img width="700" height="500" src="metadata/pom_1.png">
</p>  

### repository and dependency download

- root pom.xml


### group id and name and dependency


### Multi-Modules Project

<p align="center">
  <img width="700" height="500" src="metadata/pom_2.png">
</p>  


  - root and sub pom.xml
  
### Chapter 3 Useful hacks of Apache Maven with Intellij


### import by pom.xml

### .m2

- what is .m2
- how to find jar files

### invalidate cache and restart

### Reimport project after change of pom.xml

  