# Java101

### Der Ablauf beim Programmieren mit Java ist folgender:

Quelltext in Java programmieren
Umwandeln des Quelltextes in plattformunabhängigen Bytecode ("Zwischensprache")
Ausführen des Bytecodes mit Hilfe eines Interpreters ("Virtuelle Maschine")



### Editor / IDE
Notepad++, VS-Code, IntelliJ, Eclipse usw.








class HelloWorld{
    public static void main(String[] args){
        System.out.println("HelloWorld");

    }

}

1. /* eine Klasse ist ein abgeschlossener Code-Bereich, beginnt mit Schlüsselwort class, danach folgt der Name der Klasse (beginnt mit Großbuchstabe und wird in Camel-Case Schreibweise geschrieben), damit der Java-Compiler weiß, wo die Klasse beginnt und endet wird der gesamte Code in geschweifte Klammer {} gesetzt*/

class HelloWorld{
		
}


2. /* Der eigentliche Code einer Klasse besteht aus Methoden, Methoden bündeln mehrere Zeilen Code zu einer Einheit, unsere Methode heißt main, diese Methode ist der Startpunkt jedes Java-Programms!!!, die main-Methode hat 3 Eigenschaften und einen Parameter: 

public: die Methode ist von außen zugänglich

static: der Code der Methode kann ausgeführt werden, ohne das vorher ein Objekt der Klasse erzeugt werden muss
 
void: die Methode hat keinen Rückgabewert

String[] args: Übergabeparameter
*/

public static void main(String[] args){
		
}

3. 
/*
Gibt den Parametern in den runden Klammern auf dem Bildschirm aus. 
In unserem Fall handelt es sich um eine Zeichenkette (String), es können aber auch andere Datentypen ausgeben werden.
println ist eine in der Java-Bibliothek vordefinierte Methode, welche etwas auf der Konsole ausgibt
*/

System.out.println("Hello World");