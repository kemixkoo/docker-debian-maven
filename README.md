# Debian Maven Image

Based on [kemixkoo/debian-git-svn:buster-slim](https://hub.docker.com/r/kemixkoo/debian-git-svn/)


# Usage

```
docker run --rm kemixkoo/debian-maven
```
By default, will display the maven version.


# Custom Maven Home

```
docker run -v /path/to/maven_home:/opt/maven kemixkoo/debian-maven
```


# Building

```
docker build -t kemixkoo/debian-maven .
```
