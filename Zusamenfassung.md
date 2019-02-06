# Tag 1

## Kommentare
Werden vom Compiler ignoriert.
### Einzeilig
Eingeleitet mit zwei Schrägstrichen <br>
// Das ist ein Kommentar
### Mehrzeilige
Eingeleitet durch Schrägstrich und Sternchen, beendet durch Sternchen und Schrägstich <br>
/*  Das ist ein mehrzeiliger Kommentar <br>
    Das gehört noch dazu <br>
    Ende des Kommentars */
    
## Ausgaben auf der Konsole
### Mit Zeilenumbruch
System.out.println("Hello World");

### Ohne Zeilenumbruch
System.out.print("Hello World ohne Zeilenumbruch");

### Fehlermeldungen
Fehlermeldungen werden auf der Konsole rot dargestellt. <br>
System.err.print("Fehlermeldung ohne Zeilenumbruch"); <br>
System.err.println("Fehlermeldung mit Zeilenumbruch"); <br>

#Tag 2
## Sonderzeichen auf der Konsole
### Backslash
Um einen \ auszugeben, müssen wir zwei Backslashes ("\\\\") eintragen. <br>
System.out.print("Ein Backslash wird ausgegeben: \\\\"); <br>
Ausgabe: Ein Backslash wird ausgegeben \ <br>
### Neue Zeile
Um eine neue Zeile auszugeben, können wir zusätzlich zu println() auch \\n verwenden. <br>
System.out.print("Neue Zeile \\n"); <br>
System.out.print("Test"); <br>
Ausgabe: Neue Zeile <br>
Test<br><br>
\\n kann jederzeit in einem print() Statement genutzt werden.<br>
System.out.print("Das soll in eine Zeile... \\nDas in die andere.");<br>
Das soll in eine Zeile...<br>
Das in die andere.<br>

### Unicode Zeichen
https://unicode-table.com/de/ <br>
Unicode Zeichen können in einem eigenen String mit \\u gefolgt von der Unicode Codierung eingegeben werden. <br>
System.out.print("Preis: 239" + "\u20ac"); <br>
Ausgabe: Preis: 239€

## Verzweigungen
### if(Bedingung) {Anweisung}
Die Anweisung wird ausgeführt, wenn die Bedingung erfüllt ist. <br>
Es können beliebig viele if Blöcke vor einem Else Block stehen. 

### else if(Bedingung) {Anweisung}
Die Bedingung wird geprüft, wenn die vorangehende Bedingung nicht erfüllt war. <br>
Die Anweisung wir ausgeführt, wenn die aktuelle Bedingung erfüllt ist. <br>
Es können beliebig viele else if Blöcke zwischen einem if und einem else Block stehen.

### else {Anweisung}
Die Anweisung wird ausgeführt, wenn die Bedingung nicht erfüllt ist. <br>
Else kann nie alleine stehen.

## Operatoren
### \> Größer
if(alter > 17)<br>
Alles, was größer 17 ist erfüllt die Bedingung.
 
### \< Kleiner
if(alter < 16) <br>
Alles, was kleiner 16 ist erfüllt die Bedingung.
### \>= Größer-gleich
if(alter >= 18) <br>
18 und alles, was größer 18 ist erfüllt die Bedingung.
### \<= Kleiner-gleich
if(alter <= 10) <br>
10 und alles was, kleiner 10 ist erfüll die Bedingung. 
### == Gleich
if(alter == 21) <br>
NUR 21 erfüllt die Bedingung
### != Ungleich
if(alter != 21) <br>
ALLES AUßER 21 erfüllt die Bedingung

    