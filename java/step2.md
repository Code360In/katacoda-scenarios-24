# Wir fangen bei EVA an

EVA ist ein Synonym und steht für `E`ingabe, `V`erarbeitung und `A`usgabe. 

Wir verwenden das Basis-Projekt `java-basics` als Playground.

`git clone https://github.com/K0NRAD/java-basics.git -b main`{{execute}}




Wir verwenden das Basis-Projekt `java-basics`.

`git clone https://github.com/K0NRAD/java-basics.git -b step2`{{execute}}

**Aufgabe**

Schreibe ein Programm das als Eingabe die Integer Werte `numberA` und `numberB` über die Kommandozeile einliest, die beiden Werte addiert und die Summe auf
der Konsole ausgibt.

**Tip**

Für die Eingabe von der Konsole verwende dir Klasse Scanner und deren Funktion nextInt() um die Werte einzulesen.

```java
Scanner scanner = new Scanner(System.in);
int numberA = scanner.nextInt();

```

Um Text auf der Konsole auszugeben verwende die Funktion println() der Klasse Syste.out

```java
System.out.println(result);
```