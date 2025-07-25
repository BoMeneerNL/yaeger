> ⚠️ **Note:**  
> This is a **fork** of the Yaeger engine to play around.  
> If you are using the Yaeger engine for your school project, please use the original from [the original repo URL here.](https://github.com/han-yaeger/yaeger).  
> If you’re here just for the fun of it, check out the branch `'active-dev'`.


# Yaeger

[![Java CI](https://github.com/han-yaeger/yaeger/workflows/Java%20CI/badge.svg)](https://github.com/han-yaeger/yaeger/actions?query=workflow%3A%22Java+CI+with+Maven%22)
[![codebeat badge](https://codebeat.co/badges/e5806ed2-598a-4597-b85b-3940650927e3)](https://codebeat.co/projects/github-com-han-yaeger-yaeger-master)
[![CodeFactor](https://www.codefactor.io/repository/github/han-yaeger/yaeger/badge)](https://www.codefactor.io/repository/github/han-yaeger/yaeger)
[![Quality Gate Status](https://sonarcloud.io/api/project_badges/measure?project=han-yaeger_yaeger&metric=alert_status)](https://sonarcloud.io/dashboard?id=han-yaeger_yaeger)
[![Maven Central](https://maven-badges.herokuapp.com/maven-central/com.github.han-yaeger/yaeger/badge.svg)](https://maven-badges.herokuapp.com/maven-central/com.github.han-yaeger/yaeger)
[![License: GPL v3](https://img.shields.io/badge/License-GPLv3-blue.svg)](https://www.gnu.org/licenses/gpl-3.0)

Yaeger is Another Education Game Engine Runtime, and a fully functional 2D game-engine that
requires only a traditional Object-Oriented style of programming. It is based on JavaFX and
requires Java 21 or above to work.

## Documentation

* API: [https://han-yaeger.github.io/yaeger/](https://han-yaeger.github.io/yaeger/)
* Manual: [https://han-yaeger.github.io/yaeger/book/](https://han-yaeger.github.io/yaeger/book/)
* Tutorial: [Yaeger tutorial](https://github.com/han-yaeger/yaeger-tutorial)
* Showcase: [Yaeger showcase](https://github.com/han-yaeger/yaeger-showcase)
* Youtube: [Howto setup a new project with IntelliJ](https://www.youtube.com/watch?v=EvIrkw7VKO0)

## Usage
Yaeger requires JDK21, and is available through the Maven Central Repository.

```xml
<dependency>
  <groupId>com.github.han-yaeger</groupId>
  <artifactId>yaeger</artifactId>
  <version>2024.2025</version>
</dependency>
```

## Modern Java, but an API with only traditional Object Orientation?

Yaeger is to be used in a course that is part of the first year at the HAN University of applied sciences. Students
just learned to master Object Orientation in the traditional sense and therefore the API of Yaeger is only targeted
towards that use case. Fancy functional aspects (such as Streams and Lambda's) are used within Yaeger itself, but are not
exposed through its API.

## Versioning

Because Yaeger will be used in an educational context, versioning will be based on school years.
Thus version 2020.2021 will be used during the school year that start in September 2020 and ends in July 2021.

### Breaking changes

It is likely that the API will break between different versions. This is partially intended, since it is to
be used in an educational context and there is no shame in preventing students from using previous iterations.

## Contributions

Contributing to Yaeger is encouraged, and we would love to review your Pull Requests. Either
pick up one of the Issues or implement a feature you've been missing. Ensure that your feature does
not require modern Java features to be exposed through the API.

## License

The code and documentation in this project are released under the [GNU General Public License v3.0](LICENSE)
