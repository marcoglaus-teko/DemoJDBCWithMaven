# Build the jar

## plugin maven-assembly-plugin
https://stackoverflow.com/questions/574594/how-can-i-create-an-executable-jar-with-dependencies-using-maven

Damit keine ClassNotFoundException auftritt beim Aufruf des JAR's und die Dependency richtig paketiert wird, verwenden wir das Plugin maven-assembly-plugin

## build aufruf
in der Konsole:
- mvn clean compile assembly-single

dann nach target navigieren und das JAR ist mit:
- java -jar "jarName".jar ausführbar
