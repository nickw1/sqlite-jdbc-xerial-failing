# Maven xerial-sqlite-jdbc failing example

## To test

```
mvn clean install
mvn exec:java -Dexec.mainClass=Sample
```

## Result (on my system, Linux x64, Java 11)

```
No suitable driver found for jdbc:sqlite:sample.db
```

Simple compilation, and using Gradle, execute the sample successfully.
