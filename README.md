# Hamcrest Result Set Matcher.

[![Build Status](https://travis-ci.com/exasol/hamcrest-resultset-matcher.svg?branch=master)](https://travis-ci.org/exasol/hamcrest-resultset-matcher)
[![Maven Central](https://img.shields.io/maven-central/v/com.exasol/hamcrest-resultset-matcher)](https://search.maven.org/artifact/com.exasol/hamcrest-resultset-matcher)

SonarCloud results:

[![Quality Gate Status](https://sonarcloud.io/api/project_badges/measure?project=com.exasol%3Ahamcrest-resultset-matcher&metric=alert_status)](https://sonarcloud.io/dashboard?id=com.exasol%3Ahamcrest-resultset-matcher)

[![Security Rating](https://sonarcloud.io/api/project_badges/measure?project=com.exasol%3Ahamcrest-resultset-matcher&metric=security_rating)](https://sonarcloud.io/dashboard?id=com.exasol%3Ahamcrest-resultset-matcher)
[![Reliability Rating](https://sonarcloud.io/api/project_badges/measure?project=com.exasol%3Ahamcrest-resultset-matcher&metric=reliability_rating)](https://sonarcloud.io/dashboard?id=com.exasol%3Ahamcrest-resultset-matcher)
[![Maintainability Rating](https://sonarcloud.io/api/project_badges/measure?project=com.exasol%3Ahamcrest-resultset-matcher&metric=sqale_rating)](https://sonarcloud.io/dashboard?id=com.exasol%3Ahamcrest-resultset-matcher)
[![Technical Debt](https://sonarcloud.io/api/project_badges/measure?project=com.exasol%3Ahamcrest-resultset-matcher&metric=sqale_index)](https://sonarcloud.io/dashboard?id=com.exasol%3Ahamcrest-resultset-matcher)

[![Code Smells](https://sonarcloud.io/api/project_badges/measure?project=com.exasol%3Ahamcrest-resultset-matcher&metric=code_smells)](https://sonarcloud.io/dashboard?id=com.exasol%3Ahamcrest-resultset-matcher)
[![Coverage](https://sonarcloud.io/api/project_badges/measure?project=com.exasol%3Ahamcrest-resultset-matcher&metric=coverage)](https://sonarcloud.io/dashboard?id=com.exasol%3Ahamcrest-resultset-matcher)
[![Duplicated Lines (%)](https://sonarcloud.io/api/project_badges/measure?project=com.exasol%3Ahamcrest-resultset-matcher&metric=duplicated_lines_density)](https://sonarcloud.io/dashboard?id=com.exasol%3Ahamcrest-resultset-matcher)
[![Lines of Code](https://sonarcloud.io/api/project_badges/measure?project=com.exasol%3Ahamcrest-resultset-matcher&metric=ncloc)](https://sonarcloud.io/dashboard?id=com.exasol%3Ahamcrest-resultset-matcher)

# Overview

This project provides [Hamcrest matcher](http://hamcrest.org/JavaHamcrest/) that compares JDBC result set (`java.sql.ResultSet`) against each other or against Java structures.

## Features

* Match two JDBC result sets
* Match a JDBC result set against an object structure

## Customer Support

This is an open source project which is written by enthusiasts at Exasol and not officially supported. We will still try to help you as much as possible. So please create GitHub issue tickets when you want to request features or report bugs.

# Table of Contents

## Information for Users

* [User Guide](doc/user_guide/user_guide.md)

## Dependencies

### Run Time Dependencies

Running the Hamcrest ResultSet Matcher requires a Java Runtime version 11 or later.

### Build Time Dependencies

| Dependency                                                                          | Purpose                                                | License                       |
|-------------------------------------------------------------------------------------|--------------------------------------------------------|-------------------------------|
| [Java Hamcrest](http://hamcrest.org/JavaHamcrest/)                                  | Checking for conditions in code via matchers           | BSD License                   |


### Test Dependencies

| Dependency                                                                          | Purpose                                                | License                       |
|-------------------------------------------------------------------------------------|--------------------------------------------------------|-------------------------------|
| [Apache Derby](https://db.apache.org/derby/)                                        | Integration tests against real JDBC result sets        | Apache License 2.0            |
| [JUnit](https://junit.org/junit5)                                                   | Unit testing framework                                 | Eclipse Public License 1.0    |

# License

This software is licensed under the [MIT license](LICENSE).