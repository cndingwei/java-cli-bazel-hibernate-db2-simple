# java-cli-bazel-hibernate-db2-simple

## Description
Creates a small database table
called `dog` and populates with
hql.

## Tech stack
- java
- bazel
  - hibernate
  - hql
  - log4j
  - db2 driver

## Docker stack
- maven:3-openjdk-17
- ibmcom/db2

## To run
`sudo ./install.sh -u`

## To stop
`sudo ./install.sh -d`

## For help
`sudo ./install.sh -h`

## Credit
- [HQL code based on](https://www.journaldev.com/2954/hibernate-query-language-hql-example-tutorial)
- [Hibernate config based on](https://www.theserverside.com/blog/Coffee-Talk-Java-News-Stories-and-Opinions/An-example-hibernatecfgxml-for-MySQL-8-and-Hibernate-5)
- [Hibernate code based on](https://github.com/lokeshgupta1981/hibernate/tree/master/hibernate-hello-world)
