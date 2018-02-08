# Debian Maven Image

Based on 
- DockerHub, [kemixkoo/jenkins-git-svn](https://hub.docker.com/r/kemixkoo/jenkins-git-svn/) 
- GitHub, [kemixkoo/docker-jenkins-git-svn](https://github.com/kemixkoo/docker-jenkins-git-svn)


# Usage

```
docker run --rm kemixkoo/debian-maven
```
By default, will display the maven version.


# Custom Maven Home

```
docker run -d -v /path/to/maven_home:/opt/maven -it kemixkoo/debian-maven /bin/bash
```
Will be in deamon mode with custom Maven home


# Building

```
docker build -t kemixkoo/debian-maven .
```
