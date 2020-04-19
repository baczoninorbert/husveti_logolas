### Exercise for university project.

How to use:
```
mvn compile exec:java -Dexec.mainClass="pkg.Main" -Dexec.args="number"
```
Example:
```
mvn compile exec:java -Dexec.mainClass="pkg.Main" -Dexec.args="1"
mvn compile exec:java -Dexec.mainClass="pkg.Main" -Dexec.args="10"
mvn compile exec:java -Dexec.mainClass="pkg.Main" -Dexec.args="5000"
```