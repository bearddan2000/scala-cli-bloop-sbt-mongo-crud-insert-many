# scala-cli-bloop-sbt-mongo-crud-insert-many

## Description
Creates a user with credentials
and lists collection `test`.

Compiled and ran from build server `bloop`.

# Build note
Dependencies must be compatable with jdk8 or less.

## Tech stack
- bloop
- scala
- bloop-sbt
  - mongo connector
- mongo

## Docker stack
- mongodb:latest
- openjdk:8-jdk-alpine

## To run
`sudo ./install.sh -u`

## To stop
`sudo ./install.sh -d`

## For help
`sudo ./install.sh -h`

## Credit
- https://www.tutorialspoint.com/mongodb/mongodb_java.htm
