# Code und Templates
Wir verwenden das Basis-Projekt `java-basics`.
`git clone https://github.com/K0NRAD/java-basics.git -b step1`{{execute}}

Das Projekct `java-basics` verendet MAVEN als Build Tool. Wir wechseln in das 
Projekt Verzeichnis.

`cd java-basics`{{execute}}

Wir öffnen die Klasse `java-basics/src/main/java/sit/learninghub/App.java`{{open}}
In der Klasse App.java fügen wir eine `main` Methode ein.

```java
    public static void main(String[] args){
        System.out.println("Hello World!");
    }
```{{copy}}

Wir kompilieren das Projekt.

`mvn clean compile package -f pom.xml`{{execute}}

Die Anwendung starten wir mit der

`java -jar target/java-basics-1.0.0.jar`{{execute}}

Wir verwenden das Basis-Projekt `java-basics`.

`git clone https://github.com/K0NRAD/java-basics.git`{{execute}}

Das Projekct `java-basics` verendet MAVEN als Build Tool. Wir wechseln in das 
Projekt Verzeichnis.

`cd java-basics`{{execute}}

In der Klasse App.java fügen wir eine `main` Methode ein.

```java
    public static void main(String[] args){
        System.out.println("Hello World!");
    }
```{{copy}}

Wir kompilieren das Projekt.

`mvn clean compile package -f pom.xml`{{execute}}

Die Anwendung starten wir mit der

`java -jar target/java-basics-1.0.0.jar`{{execute}}
