# Debian Maven Image

Based on 
- DockerHub, [kemixkoo/debian-git-svn](https://hub.docker.com/r/kemixkoo/debian-git-svn/) 
- GitHub, [kemixkoo/docker-debian-git-svn](https://github.com/kemixkoo/docker-debian-git-svn)


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
