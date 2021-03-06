## Java Images

[![](https://badge.imagelayers.io/felipemsantos/docker-java:latest.svg)](https://imagelayers.io/?images=felipemsantos/docker-java:latest)

Basic [Docker](https://www.docker.com/) image to run [Java](https://www.java.com/) applications.
This image is based on [AlpineLinux](http://alpinelinux.org/) to keep the size dow, yet smaller images do exist.  
Includes BASH, since many Java applications like to have convoluted BASH start-up scripts.

### Versions

**JRE8/JDK8 Version**: `8u74-b02`  
**JRE7/JDK7 Version**: `7u80-b15`

### Tags

| Java version      | tags                    | Size |
| ----------------- | ----------------------- | ---- |
| Oracle Java 8 JRE | latest / jre8 | [![](https://badge.imagelayers.io/felipemsantos/docker-java:jre8.svg)](https://imagelayers.io/?images=felipemsantos/docker-java:jre8) |
| Oracle Java 8 JDK | jdk8              | [![](https://badge.imagelayers.io/felipemsantos/docker-java:jdk8.svg)](https://imagelayers.io/?images=felipemsantos/docker-java:jdk8) |
| Oracle Java 7 JRE | jre7                | [![](https://badge.imagelayers.io/felipemsantos/docker-java:jre8.svg)](https://imagelayers.io/?images=felipemsantos/docker-java:jre7) |
| Oracle Java 7 JDK | jdk7                    | [![](https://badge.imagelayers.io/felipemsantos/docker-java:jdk7.svg)](https://imagelayers.io/?images=felipemsantos/docker-java:jdk7) |


### Usage

Example: 

    docker run -it --rm felipemsantos/docker-java java -version
