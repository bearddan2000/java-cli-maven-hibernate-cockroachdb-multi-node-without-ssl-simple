# java-cli-maven-hibernate-cockroachdb-multi-node-without-ssl-simple

## Description
Creates a small database table
called `dog` and populates with
hql.
A java maven build, that connects to single node
cockroach database without ssl.

## Tech stack
- java
- maven
  - hibernate
  - hql
  - log4j
  - postgres drivers

## Docker stack
- cockroachdb/cockroach:v19.2.2
- maven:3-openjdk-17

## To run
`sudo ./install.sh -u`
- [Master node webui](http://localhost:8000)
- [Slave node 1 webui](http://localhost:8001)
- [Slave node 2 webui](http://localhost:8002)

## To stop
`sudo ./install.sh -d`

## For help
`sudo ./install.sh -h`

## Credit
- [HQL code based on](https://www.journaldev.com/2954/hibernate-query-language-hql-example-tutorial)
- [Hibernate config based on](https://www.theserverside.com/blog/Coffee-Talk-Java-News-Stories-and-Opinions/An-example-hibernatecfgxml-for-MySQL-8-and-Hibernate-5)
- [Hibernate code based on](https://github.com/lokeshgupta1981/hibernate/tree/master/hibernate-hello-world)
