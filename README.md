# docker-maven
Docker images with Maven

This is a fork from official https://hub.docker.com/_/maven

# Supported tags and respective Dockerfile links

See [Docker Hub](https://hub.docker.com/_/maven) for updated list of tags

* [pauloneves/maven-azulzulu-11-alpine](https://github.com/paulozagaloneves/docker-maven/blob/master/azulzulu-11-alpine/Dockerfile)

# What is Maven?

[Apache Maven](http://maven.apache.org) is a software project management and comprehension tool.
Based on the concept of a project object model (POM),
Maven can manage a project's build,
reporting and documentation from a central piece of information.


# How to use this image

You can run a Maven project by using the Maven Docker image directly,
passing a Maven command to `docker run`:

### Linux

    docker run -it pauloneves/maven-azulzulu-11-alpine:3.6.3 mvn --version

# License

View [license information](https://www.apache.org/licenses/) for the software contained in this image.


# User Feedback

## Issues

If you have any problems with or questions about this image, please contact us
through a [GitHub issue](https://github.com/paulozagaloneves/docker-maven/issues).


