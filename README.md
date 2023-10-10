# java-cli-millbuild-ssl-postgresql-simple

## Description
A java gradle build, that connects to postgresql database.

Uses self-sign ssl.

## Tech stack
- java
- millbuild
  - 6.8.2

## Docker stack
- alpine:edge
- postgresql:alpine
- nightscape/scala-mill

## To run
`sudo ./install.sh -u`

## To stop
`sudo ./install.sh -d`

## For help
`sudo ./install.sh -h`
