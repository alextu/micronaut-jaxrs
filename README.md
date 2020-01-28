# Micronaut JAX-RS

[![Maven Central](https://img.shields.io/maven-central/v/io.micronaut.jaxrs/micronaut-jaxrs-runtime.svg?label=Maven%20Central)](https://search.maven.org/search?q=g:%22io.micronaut.jaxrs%22%20AND%20a:%22micronaut-jaxrs-runtime%22)
[![Build Status](https://github.com/micronaut-projects/micronaut-jaxrs/workflows/Java%20CI/badge.svg)](https://github.com/micronaut-projects/micronaut-jaxrs/actions)

Micronaut JAX-RS adds the ability to use common JAX-RS annotations types and annotations to a Micronaut application.

This project is not an implementation of the JAX-RS specification and is designed to allow users familiar with the JAX-RS API to use the most common parts of the API within the context of a Micronaut application. 

## Documentation

See the [Documentation](https://micronaut-projects.github.io/micronaut-jaxrs/latest/guide/) for more information. 

See the [Snapshot Documentation](https://micronaut-projects.github.io/micronaut-jaxrs/snapshot/guide/) for the current development docs.

## Examples

Examples can be found in the [examples](https://github.com/micronaut-projects/micronaut-jaxrs/tree/master/examples) directory.

## Snapshots and Releases

Snaphots are automatically published to JFrog OSS using [Github Actions](https://github.com/micronaut-projects/micronaut-jaxrs/actions).

See the documentation in the [Micronaut Docs](https://docs.micronaut.io/latest/guide/index.html#usingsnapshots) for how to configure your build to use snapshots.

Releases are published to JCenter and Maven Central via [Github Actions](https://github.com/micronaut-projects/micronaut-jaxrs/actions).

A release is performed with the following steps:

* Change the version specified by `projectVersion` in `gradle.properties` to a semantic, unreleased version. Example `1.0.0`
* Commit the change. Example: `git commit -m "Release Version 1.0.0"`
* Tag the release where the tag starts with `v`. Example: `git tag v1.0.0`
* Push the commit and the tag: `git push && git push --tags`