# primefaces-starter
You don't just create a `pom.xml` with packaging `war`, add the jetty plugin
and a JSF implementation as a dependency, plus primefaces, and do
`mvn jetty:run`. Nonononono. You'll be trapped in an endless succession
of exceptions, until you finally give up, use the wildfly plugin, and let
it download half of the Internet. But in the end it works.

This repository is the result of that journey.

## Usage
```
mvn clean verify wildfly:run
```

Then browse to http://localhost:8080/example and enjoy.
