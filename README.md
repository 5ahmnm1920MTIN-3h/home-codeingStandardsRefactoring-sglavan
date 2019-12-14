# Santa Run

### Project description: 
This is a simple 2D side-scroll game. The Santa runs from left to right and has to avoid some obstacles by jumping over them.
The game ends when the Santa hits an obstacle.  The goal is to avoid as many obstacles as possible.

### Development platform: 
Windows 10, Unity version 2019.1.14f1, Visual Studio Community 2017, Scripting Runtime Version: .NET 4.0

### Target platform: 
WebGl and Standalone, RefRes: 1920 * 1080


### Visuals: 
<div>
<img src = "./Screenshots/sketch-SantaRun.JPG" width = "500">
</div>

[![SANTA RUN](https://i9.ytimg.com/vi/2C74XxBkFfI/mq1.jpg?sqp=CNWnze8F&rs=AOn4CLBrmO-tJ3gQ2BNeMxvrmQcsIhhcgQ)](https://www.youtube.com/embed/2C74XxBkFfI "Santa RUN")

https://www.youtube.com/embed/2C74XxBkFfI

### Necessary setup/execution steps: 
For playing the game go to: 
* WebGL: https://hs-teaching.github.io/WegGL-SantaRun/
* Standalone (.exe): Clone project and publish as Standalone

For development: Clone this project. 

### Third party material: 
* This game is based on the game Santa Run developed by Raja Biswas in the Udemy-course Unity 2018 Game Developmen by Example 
[Unity 2018 Game Development by Example](https://www.udemy.com/course/unity-2d-game-development-by-example/).
* Sprites are used from https://www.gameart2d.com/santa-claus-free-sprites.html


### Project state: 
Program is working correctly, no errors, refactoring is needed.
Refactoring needed: 
* del not used namespaces
* del unused variables
* del needless debugs
* del needless comments
* del unused methods
* rename variables (coding standards)
* rename methods (coding standards)
* fix poor conditional clauses
* fix poor formating
* replace magic string
* replace magic number

## Project state Sarah:
* Tried to refactor bulletpoints mentioned above; but I'm bad at it. gave my best tho.

### Limitations: 
Only one level is implemented. 

### Lessons Learned: 
* Create 2D Scenes
* Use Quads for moving Backgrounds (Textures instead of Sprites)
* Use Particle System for snowing effect.
* Use Scene Management for switching between Scenes
* Create and control Animations (Animation, Animator and Scripts)
* Use the singelton pattern
* Spawn objects
* Use UI elements and manipulate UI elements with scrips


Copyright by smeerws

### Ausarbeitung Refactoring:

### Was ist Refactoring Definition in eigenen Worten?
Ein Code wird überarbeitet aber sein Verhalten ändert sich dadurch nicht. Der Code soll übersichtlicher und klarer strukturiert werden und somit der Wartungsaufwand minimiert werden.

### Welche Vorteile/Nachteile birgt Refactoring?
* Vorteile:
Die Struktur ist besser verständlich, überschaubarer, lesbarer und besser testbar.
* Nachteile:
Man muss mehr Zeit ins Projekt stecken

### Was sind die Refactoring-Schritte?

* Umbenennen von Variablen und Methoden.
* Einkapseln von Feldern.
* Einführung einer neuen abstrakten Oberklasse.
* Entfernen und Neuordnen von Parametern.
* Umformatieren von Programmcode.
* Extraktion von Methoden, Klassen, Paketen und Schnittstellen.
* Verbesserung der Datenkapselung.


### Prinzipien von guten Code?
- Andere Entwicklern können ihn leicht lesen und verstehen
- Er kann gut getestet werden
- Er ist so kurz wie möglich geschrieben
- Es wiederholt sich nichts

### Was versteht man unter Code Smell?
Funktionierender, aber schlecht strukturierter Quellcode.

### Recherche von 10 Code Smells die Eure Projekt betreffen können, inkl. Beschreibung und Beispiel.


- Code-Duplikate:
Quellcode der mehrfach verwendet wird (in identischer oder ähnlicher Form)

- Lange Methoden: 
Je länger eine Methode ist, desto fehleranfälliger ist sie. Zusätzlich erschweren lange Methoden die Wiederverwendung.

- Umfangreiche Parameterlisten: 
Sie erschweren das Verständnis von Methodenaufrufen, da Attribute von Objekten als Parameterliste übergeben werden, anstatt das Objekt an die Methode zu übergeben.

- Temporäre Felder: 
Felder einer Klasse beschreiben die Zustände ihrer Objekte, wobei ein Objekt ein Feld nur unter bestimmten Umständen bzw. temporär verwendet, so dass der Code schwer zu verstehen ist.

- Wiederholende Switch-Anweisungen: 
Sie werden an mehreren Codestellen verwendet, obwohl es besser wäre, sie als eigene Methode zu extrahieren.

- Große Klassen: 
Eine Klasse ist zu umfangreich, umfasst zu viele Instanzvariablen und duplizierten Code.

- Datenklasse: 
Klassen mit Feldern und Zugriffsmethoden ohne Funktionalität.

- Datenklumpen: 
Eine Gruppe von Objekten, welche häufig zusammen vorkommen.

- Unangebrachte Intimität: 
Zwei Klassen haben zu enge Verflechtungen miteinander.

- Faule Klasse: 
Eine Klasse leistet zu wenig, um ihre Existenz zu rechtfertigen.

- Middle Man (Vermittler): 
Eine Klasse delegiert alle Methodenaufrufe an eine andere Klasse.


