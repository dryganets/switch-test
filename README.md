# Switch performance micro-benchmark

The JMH micro benchmark to evaluate switch vs HashMap branching performance for Strings.
The test intentionally checks only the worst case scenario - access to the last item.

In order to compile the code you need to install Maven.

Building:
```sh
mvn clean install
```

Running:
```sh
java -jar target/benchmarks.jar
```
