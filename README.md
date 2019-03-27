
# Spektrometer - Stundenprotokoll 
 von Tim Wähner und David Rettmann 

## Inhalt

## Dezember

<details>
 <summary>Genauer</summary>

### [Montag, der 17.12.2018](#1)
### [Dienstag, der 18.12.2018](#2)
### [Mittwoch, der 19.12.2018](#a)
### [Montag, den 24.12.2018](#b)
### [Freitag, der 28.12.2018](#3)
 </details> <hr>

## Januar

<details>
 <summary>Genauer</summary>
 
### [Dienstag, der 08.01.2019](#4)
### [Samstag, der 12.01.2019](#c)
### [Montag, der 14.01.2019](#5) 
### [Dienstag, der 15.01.2019](#6)
### [Freitag, der 18.01.2019](#d)
### [Samstag, der 19.01.2019](#7)
### [Sonntag, der 20.01.2019](#e)
### [Montag, der 21.01.2019](#8)
 </details> <hr>

## Februar

<details>
 <summary>Genauer</summary>
 
### [Samstag, der 02.02.2019](#11)
### [Sonntag, der 03.02.2019](#f)
### [Montag, der 04.02.2019](#12)
### [Dienstag, der 05.02.2019](#13)
### [Samstag, der 09.02.2019](#g)
### [Montag, der 11.02.2019](#14)
### [Dienstag, der 12.02.2019](#15)
### [Montag, der 18.02.2019](#16)
### [Dienstag, der 19.02.2019](#17)
### [Montag, der 25.02.2019](#18)
### [Dienstag, der 26.02.2019](#19)
 </details> <hr>

## März

<details>
 <summary>Genauer</summary>

### [Montag, der 04.03.2019](#20)
### [Dienstag, der 05.03.2019](#21)
### [Samstag, der 09.03.2019](#h)
### [Montag, der 11.03.2019](#22)
### [Dienstag, der 12.03.2019](#i)
### [Montag, der 18.03.2019](#23)
### [Dienstag, der 19.03.2019](#24)
### [Montag, der 25.03.2019](#25)
### [Dienstag, der 26.03.2019](#26)
</details> <hr>

## Montag, der 17.12.2018<a name="1"></a>

In der heutigen Stunde begannen wir mit dem neuen Projekt im Fach Informatik. Wir haben uns bereits zuvor Gedanken gemacht wie unser nächstes Projekt aussehen soll und sind beide der Meinung, dass wir gerne Physical Computing machen würden. Der Zufall hat gewollt, dass Herr Buhl in den letzten Physikstunden viel mit dem Spektrometer gearbeitet hat und uns als "freiwillige Arbeit" die Möglichkeit gegeben hat ein solches selber zu bauen. So kamen wir auf die Idee Physik und Informatik zu verbinden und ein halbautomatisches Spektrometer zu bauen und zu programmieren. Wir stellten unsere Idee Herrn Buhl vor und dieser wirkte keineswegs abgeneigt.

## Dienstag, der 18.12.2018<a name="2"></a>

Heute haben wir uns dafür entschieden, mit dem Arduino zu arbeiten. Zum einen soll die Arbeit mit dem Arduino deutlich einfacher zum Anfangen sein als zum Beispiel „Rasberry Pie“, was uns als Anfängern natürlich zugute kommt. Zum anderen haben wir außerdem durch meinen Bruder bereits einen Arduino Uno samt Starterkit. Nach der Entscheidung haben wir mit den ersten Schritten angefangen. Dafür haben wir den Arduino das erste Mal an den Computer angeschlossen. Nach einiger Recherche im Internet haben wir uns für den Arduino Webeditor entschieden, um auch getrennt arbeiten zu können. Dafür haben wir ein Konto bei Arduino Create erstellt und das nötige Plugin installiert. Der Arduino konnte nun per USB an den Computer angeschlossen werden und war einsatzbereit. Als erstes Experiment haben wir eine LED mit dem Arduino angesteuert. Dafür haben wir uns über den nötigen Widerstand informiert, damit die Lampe nicht durchbrennt. Im Internet haben wir Anleitungen für den Anschluss an den Arduino und die richtigen Codes gefunden. Der erste einfacheVersuch bestand darin, eine rote LED, die über das Steckbrett angeschlossen ist, zum Leuchten zu bringen Nachdem dies (erstaunlich) schnell und gut funktioniert hat, war unser zweiter Test, ein Blinken der LED zu erreichen. Dies war auch ohne Probleme zu lösen.

<img src="https://github.com/BohrisNaturalisRettner/Informatikprojekt-Spektrometer-Stundenprotokoll/blob/master/Ledh.png" alt="image" width="1500">

## Mittwoch, der 19.12.2018<a name="a"></a>

Einer der wichtigsten Faktoren für unser Projekt wird die Erkennung der Maxima sein. Dafür haben wir den Fotosensor, den wir für unser Projekt brauchen, bei Herrn Buhl „in Auftrag“ gegeben. Dieser hat drei verschiedene Sensoren bestellt. Da wir, bis die Sensoren angekommen sind, nicht an dem Projekt an sich weiterarbeiten können, haben wir uns nach den ersten erfolgreichen Experimenten mit der LED gestern an die zweite wichtige Komponente (den Motor) gewagt. Wir haben uns für den Servo entschieden, da dieser am leichtesten zu verbinden und zu bedienen zu sein scheint und den voraussichtlich benötigten Bewegungsradius abdeckt. Den Servo haben wir über ein Potentiometer so angeschlossen, dass dieser sich bei Drehen des Potentiometers im gleichen Winkel mitdreht.  

<img src="https://github.com/BohrisNaturalisRettner/Informatikprojekt-Spektrometer-Stundenprotokoll/blob/master/Servo%20Potentiometerh.png" alt="image" width="1500">

## Montag, der 24.12.2018<a name="b"></a>

Heute habe ich (David) mich mit Herrn Buhl getroffen und die photo Sensoren bekommen. Natürlich konnten wir nicht abwarten, erste Experimente mit den Sensoren zu beginnen. Den simpelsten Sensor haben wir nach einer im Internet gefundenen Skizze an den analogen Anschluss des Arduino und  den Strom angeschlossen und den richtigen Widerstand gefunden. Den Wert des Sensors haben wir uns im Monitor des Arduino Editors anzeigen lassen. Nachdem wir ein Signal empfangen haben, haben wir auch den zweiten Teil der Skizze, die Kopplung an eine LED, umgesetzt und dafür den Code des Sensors mit dem der Led verknüpft. Hierbei leuchtet die LED, wenn der von dem Sensor gemessene Wert eine bestimmte Zahl überschreitet.

<img src="https://github.com/BohrisNaturalisRettner/Informatikprojekt-Spektrometer-Stundenprotokoll/blob/master/fotosensor%20LED.JPG" alt="image" width="1500">

## Freitag, der 28.12.2018<a name="3"></a>

Im Skiurlaub haben wir unser Konzept besprochen und unsere Vorgehensweise festgelegt. Wir haben entschieden, erst die Funktionsweise der einzelnen Komponenten zu überprüfen und so die besten Lösungen für alle Probleme zu finden, bevor wir die finale Konstruktion beginnen. Zwar ist uns klar, dass wir so Gefahr laufen, am Ende keine „Reinfassung“ des Projektes zu haben, jedoch sind die Einzelergebnisse allein schon viel wert und wir tasten uns lieber langsam, aber sicher zur optimalen Konstruktion vor und sind am Ende nicht enttäuscht, wenn etwas nicht funktioniert, sondern können schon vorher variabel darauf reagieren.

## Dienstag, der 08.01.2019<a name="4"></a>

Heute haben wir uns ein weiteres Mal mit dem Fotosensor und dem Servo Motor beschäftigt. Jedem Signal des Photosensors haben wir eine Gradzahl des Servomotors zugeordnet. Je nach Lichtsignal hat sich dieser Servomotor nun also gedreht und so die Helligkeit angezeigt. Grundsätzlich hat dies funktioniert, jedoch war das Ergebnis teilweise sehr ungenau. Der Servo ist gesprungen oder hat verzögert reagiert. Dies passierte auch, als wir wieder den alten Aufbau mit dem Potentiometer probiert haben. Wir sind also zu dem Schluss gekommen, dass ein Servo nicht für unser Projekt geeignet ist, da das Projekt eine hohe Präzision erfordert und der Servo ohnehin zu schwach wäre. Es bleibt also eine offene Frage, was unser Motor sein wird.

<img src="https://github.com/BohrisNaturalisRettner/Informatikprojekt-Spektrometer-Stundenprotokoll/blob/master/Servo%20Lichtsensorh.png" alt="image" width="1500">

## Samstag, der 12.01.2019<a name="c"></a>

Bei der Beschäftigung mit Motoren sind wir nach Empfehlung von Herrn Buhl auf den Stepper Motor gestoßen. Dieser scheint perfekt zu sein, da er zwar nicht so schnell wie ein Servo arbeiten kann, dafür aber sehr präzise ist und ein deutlich stärkeres Haltemoment hat. Außerdem haben wir einen Steppermotor in dem Arduino Kit und müssen daher nicht einmal einen Motor kaufen. Bei der Beschäftigung mit dem Steppermotor hat uns vor allem das youtube video von „DroneBot Workshop“ geholfen, das die Funktionsweise der Stepper erklärt, auf viele andere Fragen, wie den Anschluss an den Arduino, eingeht und in der Niederschrift für genau unseren Stepper eine Vorlage für den Code zu Verfügung stellt. Der Link zu dem Youtube Video lautet: https://youtu.be/0qwrnUeSpYQ. Dieses Videos hat uns noch mehr von Stepper Motoren als die für uns optimale Lösung überzeugt. Ein Punkt, der in dem Video jedoch angesprochen wurde, war, dass der Stepper im Gegensatz zu dem Servomotor eine externe Stromversorgung benötigt. Da wir diese noch nicht haben, ist für uns die Arbeit mit dem Steppermotor erstmal aufgeschoben.

## Montag, der 14.01.2019<a name="5"></a>

Heute haben wir eine weitere Funktionsweise unseres Projektes überprüft. Wir wollten anders als bisher keine direkte Reaktion von LEDs, Servos etc. bewirken, sondern erreichen, dass sich die Informationen gemerkt und erst am Ende addiert ausgelesen werden. Dabei haben wir uns von unserem ersten Projekt auf Code.org inspirieren lassen. Dort haben wir vermehrt mit Variablen gearbeitet, die bei bestimmten Aktionen hochgehen und sich so Informationen „merken“. Um dies praktisch in einem Versuch umzusetzen, haben wir zwei Lichtsensoren an eine Led gekoppelt. Diese soll nur leuchten, wenn der eine Lichtsensor ein sehr helles und der andere ein sehr dunkles Licht wahrnimmt. Dabei ist die zeitliche Abfolge egal, da bei Erreichen eines bestimmten Wertes eines Sensors eine Variable (hier: Counter genannt) auf 1 gesetzt wird. Nachdem das 2. Ereignis eintritt, sind nun beide Counter auf 1 und die LED leuchtet somit. 

<img src="https://github.com/BohrisNaturalisRettner/Informatikprojekt-Spektrometer-Stundenprotokoll/blob/master/2%20Sensoren%20%2B%20LED%20Setuph.png" alt="image" width="1500">

<img src="https://github.com/BohrisNaturalisRettner/Informatikprojekt-Spektrometer-Stundenprotokoll/blob/master/2%20Sensoren%20%2B%20LEDh.png" alt="image" width="1500">

<img src="https://github.com/BohrisNaturalisRettner/Informatikprojekt-Spektrometer-Stundenprotokoll/blob/master/IMG_2708.jpg" alt="image" width="1500">

## Dienstag, der 15.01.2019<a name="6"></a>

Nachdem der Fotosensor und die Counter funktionieren, ist nun der Motor als letzte große Komponente an der Reihe. Für die Stromversorgung haben wir ein altes Handykabel, dessen Stecker vorne nicht mehr funktioniert hat, genommen und den Stecker abgetrennt. Das Kabel haben wir dann abisoliert und mit Hilfe einer Lüsterklemme mit Kabeln aus dem Starterkit verbunden, die in den Anschluss beim Controller Panel des Steppers passen. Die Stromversorgung stand also. Anschließend haben wir aus dem DroneBot Workshop weitere Codes übernommen und so verschiedene Geschwindigkeiten und Drehungen getestet. Nach einigem Probieren wurde uns klar, welche Teile der Befehle welche Konsequenzen bewirken und der ersten Version unseres Spektrometers steht jetzt nichts mehr im Wege. 

<img src="https://github.com/BohrisNaturalisRettner/Informatikprojekt-Spektrometer-Stundenprotokoll/blob/master/dronebot1.png" alt="image" width="1500">

<img src="https://github.com/BohrisNaturalisRettner/Informatikprojekt-Spektrometer-Stundenprotokoll/blob/master/droneBot%202.png" alt="image" width="1500">

<img src="https://github.com/BohrisNaturalisRettner/Informatikprojekt-Spektrometer-Stundenprotokoll/blob/master/handykabel.jpg" alt="image" width="1500">

## Freitag, der 18.01.2019<a name="d"></a>

Heute haben wir das Konzept für den Bau erstellt. Der Aufbau soll in eine Kiste integriert werden, die den ganzen Aufbau verdunkelt und die Messergebnisse damit optimiert. Außerdem muss so nicht immer der ganze Raum verdunkelt werden und das Spektrometer ist universeller einsetzbar. Des weiteren ist es wichtig, das Gitter zentral über dem Drehpunkt aufzustellen. Dafür planen wir einen Tisch, auf dem Gitter und Lichtquelle sitzen und der über den Motor ragt. Der restliche Teil ist von dem Spektrometer in der Schule inspiriert. Gemessen wird durch einen Schwenkarm, an dem sich ein Rohr befindet, um den Winkel zu präzisieren. Jedoch gucken wir nicht durch das Ende der Röhre wie in der Schule, sondern an seinem Ende befindet sich der Photosensor. Ein weiterer Entschluss ist, dass wir montags nicht für eine Stunde Unterricht alle Materialien den ganzen Tag durch die Schule tragen, sondern wir in dieser Stunde an Github und dienstags an dem Projekt selber arbeiten, wodurch in Zukunft auch kaum Einträge zu Montagen kommen werden.

## Samstag, der 19.01.2019<a name="7"></a>

Heute haben wir Besorgungen für den ersten Bau gemacht. Im Baumarkt haben wir für uns nützlich aussehende Komponenten gekauft. Dazu gehörte eine Gardinenstange samt Halterung als Rohr, Lautsprecherkabel als weitere Kabelverbindungen, ein Lötkolben mit Lötzinn, eine Kabelbox, in der der Lichtsensor nochmal extra abgedunkelt ist, Schrauben, Schrumpfkabel, Kabelverbinder und das Holz für den Untergrund der Konstruktion und die Box am Ende.

## Sonntag, der 20.01.2019<a name="e"></a>

Heute haben wir eine erste Konstruktion aufgebaut. Wir haben den Arduino sowie zwei Holzblöcke (aus dem Keller) auf die Holzplatte geschraubt. Zwischen den Holzblöcken haben wir den Stepper befestigt. Dieser konnte sich nun drehen. Außerdem haben wir einige der Verbindungen gelötet und den Photosensor in die Kabelbox gesteckt. An der einen Seite haben wir ein kleines Loch in die Box gebohrt, damit der Sensor „herausgucken“ kann, aber von den anderen Seiten fest sitzt und abgedunkelt ist. Aufgefallen ist uns, dass der Motor und die Konstruktion im allgemeinen den Schwenkarm nicht auf einer Höhe halten können werden. Es fehlt also noch ein Schwenkarm und die Befestigung desselben. 

<img src="https://github.com/BohrisNaturalisRettner/Informatikprojekt-Spektrometer-Stundenprotokoll/blob/master/IMG_2769.jpg" width="1500">

<img src="https://github.com/BohrisNaturalisRettner/Informatikprojekt-Spektrometer-Stundenprotokoll/blob/master/IMG_2770.jpg" alt="image" width="1500">

## Montag, der 21.01.2019<a name="8"></a>

Nachdem wir uns in der Informatikstunde näher mit Github auseinandergesetzt haben, sind wir für diese Besorgungen heute ein weiteres Mal in den Baumarkt gefahren. Dort haben wir eine kleine Metallplatte mit Löchern als Schwenkarm besorgt und ein kleines Teil, um den Arm an der Welle des Motors zu befestigen. Zuhause haben wir dann versucht, die Verbindung herzustellen, jedoch hat dies weder mit noch ohne Kleber noch auf irgendwelche anderen Wege funktioniert. Wir werden deshalb erneut in den Baumarkt fahren, um ein besseres Teil zu besorgen.

## Samstag, der 02.02.2019<a name="11"></a>

Im Baumarkt haben wir viel gefunden, aber auch auf Nachfrage bei Mitarbeitern kein passendes Teil zum Verbinden. Das ist schon sehr frustrierend, da ohne diese Verbindung nicht mal erste Testläufe möglich sind. 

## Sonntag, der 03.02.2019<a name="f"></a>

Um die Funktionsweise nochmal genauer zu überprüfen, haben wir heute die finale (?) Version unseres Codes geschrieben. Da es sich um eine konstante Geschwindigkeit des Steppers handelt, gibt es einen Zusammenhang zwischen der Zeit und den steps, die der Motor geht. Die Variablen gehen auf 1, wenn in dem jeweiligen zeitlichen Intervall (step-Bereich) das Signal des Sensors eine bestimmte Zahl überschreitet. Um dies zu testen, haben wir uns im Monitor die steps, das Signal des Lichtsensors und die Counter untereinander anzeigen lassen und haben bei verschiedenen Step-Anzahlen Licht auf den Sensor gelassen und überprüft, ob der Counter steigt. Anschließend haben wir 2 LEDs (eine grüne, eine rote) angeschlossen, die jeweils für einen bestimmten Counter, also Bereich standen. Leuchten sollten diese aber erst, wenn der Motor die 90° gedreht hat. Daher haben wir auch dies als Bedingung in unseren Code aufgenommen, damit nach Ablauf der 90° entweder eine der beiden, beide oder gar keine leuchtet, jedoch keine vorher leuchtet und auch keine wieder ausgeht. Dies hat einwandfrei funktioniert, was unsere Laune bezogen auf das Projekt wenigstens ein bisschen gebessert hat.

<img src="https://github.com/BohrisNaturalisRettner/Informatikprojekt-Spektrometer-Stundenprotokoll/blob/master/IMG_2771.jpg" width="1500">

<img src="https://github.com/BohrisNaturalisRettner/Informatikprojekt-Spektrometer-Stundenprotokoll/blob/master/2ledh.png" width="1500">

## Montag, der 04.02.2019<a name="12"></a>

Heute haben wir uns auf Github erneut mit dem Stundenprotokoll auseinandergesetzt, damit dieses auf dem neuesten Stand bleibt. 

## Dienstag, der 05.02.2019<a name="13"></a>

In der heutigen Doppelstunde haben wir alle Materialen mitgenommen, konnten aber ohne die fehlende Verbindung nicht an der Konstruktion weiterarbeiten. Wir haben gegoogelt (wie in den Tagen zuvor) und überlegt, bestimmte Teile im Internet zu bestellen. Bis unser Blick auf eine Zange gefallen ist. Diese kann die Welle des Motors festhalten und an den Schwenkarm befestigt diesen bewegen. Das hat uns so begeistert, endlich einen Versuch starten zu können, dass wir alle Befestigungen provisorisch mit Kabelbindern gemacht haben. Für den Testlauf haben wir aus der Gesamtzahl der Steps für eine Umdrehung die Steps für 90 Grad ausgerechnet (128) und diese in 9 Bereiche eingeteilt. Die Zange halten wir mit einem Kabelbinder zusammen. Weitere Kabelbinder halten die Zange an dem Arm fest und den Lichtsensor am Ende des Arms in der Position. Dieser ist für die ersten Versuche ohne Rohr nach außen gekehrt. Wir haben mehrere Leute wie Torben und Teda dazu geholt und das Program gestartet. Der Motor drehte sich und der Arm sich mit! Wir haben dann mit Handytaschenlampen die Maxima simuliert. Da wir das Licht bündeln mussten, um einigermaßen genaue Bereiche zu haben, haben wir Teile der Gardinenstange vor das Licht gehalten. Und tatsächlich: Es wurden an den Bereichen, in denen wir geleuchtet hatten, Ausschläge wahrgenommen. Um ein besseres Ergebnis zu erzielen, haben wir das Ende der Röhre mit Tape abgeklebt, sodass nur ein kleiner Schlitz frei war. So konnten wir die Bereiche provisorisch minimieren.

<img src="https://github.com/BohrisNaturalisRettner/Informatikprojekt-Spektrometer-Stundenprotokoll/blob/master/zange.jpg" width="1500">

<img src="https://github.com/BohrisNaturalisRettner/Informatikprojekt-Spektrometer-Stundenprotokoll/blob/master/schlitz.jpg" width="1500">

## Samstag, der 09.02.2019<a name="g"></a>

Die in der letzten Doppelstunde gebaute Konstruktion hatte jedoch noch einige Fehler. Zum Beispiel war die Stepanzahl nicht begrenzt. Heute haben wir versucht, dieses Problem zu lösen. Jedoch hat sich der Motor, je nachdem, was wir probiert haben, entweder immer weiter gedreht oder, wenn er nach einer Vierteldrehung auf dem Weg zurück war, sich unendlich in die andere Richtung gedreht.

## Montag, der 11.02.2019<a name="14"></a>

Wir haben nun die Lösung gefunden. Solange die Steps weniger als die STEPS_PER_OUT_REV/16 sind, geht der Motor die „Steps Required“, also in die eine, und nach Erreichen der Stepanzahl geht er „-StepsRequired“ und somit in die Gegenrichtung, bis die STEPS_PER_OUT_REV/8 erreicht sind. (Für eine Vierteldrehung teilt man die Gesamtanzahl für eine Drehung durch vier, um 90 Grad zu erhalten und nochmal durch 4, da der Motor immer 4 Schritte in einem Durchlauf läuft (Stepsrequired = 4)). So dreht der Motor beim Einstecken des Arduino eine Vierteldrehung und fährt dann wieder in die Ausgangsposition zurück. Ein Problem, das bei Beobachtung aufgefallen ist, ist jedoch, dass diese Startposition sich jedes Mal verschiebt, da der Motor beim Einstecken schon ein paar Schritte geht, ohne die Steps zu zählen. Daher müssen wir wahrscheinlich diese Schritte zählen und mit anderen Befehlen diese Schritte wieder zurück gehen.

<img src="https://github.com/BohrisNaturalisRettner/Informatikprojekt-Spektrometer-Stundenprotokoll/blob/master/90%C2%B0.png" width="1500">

## Dienstag, der 12.02.2019<a name="15"></a>

Da wir festgestellt haben, dass der Motor nicht immer gleich weit geht und diese Lösung außerdem recht umständlich wäre, haben wir uns heute um einen Startknopf gekümmert. Dieser könnte bewirken, dass der Motor sich erst dreht, wenn er Strom bekommt, und daher beim Einstecken nicht sofort dreht. So könnte das System erstmal starten, bevor der Motor sich dreht. Außerdem wollen wir in unserer Endversion sowieso einen Schalter zum Starten haben. Also haben wir aus dem Kabel einer alten Lampe aus dem Keller den Schalter ausgeschnitten und an den Arduino angeschlossen. Dieser ist auch an den analogen Eingang gekoppelt. Ist der Schalter aus, ist das Signal gleich Null. Ist der Schalter an, ist das Signal höher. Der Schalter soll beim Anschluss des Arduino an den Computer ausgeschaltet sein, damit der Stepper sich nicht vorher dreht. Und tatsächlich hat unsere Vermutung gestimmt. Der Motor dreht sich am Anfang nicht mehr. Wird der Schalter nun umgelegt, dreht sich der Motor und die Steps fangen an zu zählen. Am Ende soll, wie in dem einen vorherigen Versuch, das Ergebnis/ die LEDs solange angezeigt werden, bis der Schalter wieder umgelegt wird. Dieser resettet dann alle Variablen. Wird er wieder eingeschaltet, fängt der Durchlauf von vorne an. 

<img src="https://github.com/BohrisNaturalisRettner/Informatikprojekt-Spektrometer-Stundenprotokoll/blob/master/schalter%20foto.jpg" width="1500">

## Montag, der 18.02.2019<a name="16"></a>

In der heutigen Informatikstunde haben wir auf Github mit der Projektseite begonnen, soweit dies zu dem Zeitpunkt möglich ist. 

## Dienstag, der 19.02.2019<a name="17"></a>

Bei weiteren "Taschenlampenversuchen" ist uns vermehrt aufgefallen, dass die Bewegung des rotierenden Arms sehr unflüssig ist und somit später nicht zu der gewünschten Präzision führen wird. Dies führen wir auf die Holzplatte zurück, auf der unser Aufbau steht. Diese ist zum einen sehr dünn und biegsam und zum anderen bereits leicht verbogen, das heißt sie hat eine verhältnismäßig große Welle drin, die die Bewegung des Arms erheblich stört. 

## Montag, der 25.02.2019<a name="18"></a>

Auch an diesem Montag standen erneut das Stundenprotokoll und die Projektseite in unserem Fokus. 

## Dienstag, der 26.02.2019<a name="19"></a>

In der heutigen Doppelstunde haben wir weitere Verbesserungen am Auswertungsverfahren vorgenommen. Einerseits haben wir die Geschwindigkeit des Motors stark reduziert, in der Hoffnung das dieser dadurch stabiler läuft und uns die Auswertung der Orte an denen Licht wahrgenommen wird, leichter fällt. Andererseits haben wir die 90°, die der Motor zurücklegt in kleinere Einzelbereiche aufgeteilt, durch weitere Variablen. Zunächst haben wir mit 9 Variablen gearbeitet, allerdings war uns natürlich klar, das neun Variablen bei weitem nicht reichen um konkrete Winkel festzustellen. Deswegen haben wir noch im Unterricht eine Kopie des Codes mit 32 Variablen angefertigt und eine Version mit 64 Variablen begonnen. Diese haben wir am selben Abend noch beendet und zusätzlich eine Version mit 128 Variablen geschrieben. Mit dieser kann man den Winkel nun auf 0,7° Grad genau bestimmen.

<img src="https://github.com/BohrisNaturalisRettner/Informatikprojekt-Spektrometer-Stundenprotokoll/blob/master/nesute%20neun.png" width="1500">

## Montag, der 04.03.2019<a name="20"></a>

Nach den Problemen, die in der letzten Zeit durch die unebene Holzplatte aufgetreten sind, haben wir heute im Informatikunterricht beschlossen, diese durch eine wesentlich stabilere und ebenere Holzplatte auszutauschen. Diesbezüglich sind wir am Nachmittag bei David zuhause fündig geworden und haben die 7mm Pressholzplatte gegen eine 20mm Spanplatte ausgewechselt. Die Befestigung der Aufbauten haben wir mit Winkeln umgesetzt, da wir so zum einen den Aufbau leichter verschieben und verändern können und zum anderen der Aufbau stabiler auf der Holzplatte steht. 

<img src="https://github.com/BohrisNaturalisRettner/Informatikprojekt-Spektrometer-Stundenprotokoll/blob/master/winkel.jpg" width="1500">

## Dienstag, der 05.03.2019<a name="21"></a>

Heute haben wir den ersten "richtigen" Versuch durchgeführt, bei dem wir dieses mal auch die Wellenlänge berechnet haben. Die Wellenlänge des Lasers, den wir für unsere Versuche benutzen, beträgt 650nm und unser gemessener/errechneter Wert beträgt 620nm. Dieser Wert erscheint auf den ersten Blick sehr gut, allerdings ist er noch mit einigen Faktoren verbunden, die unsere Messgenauigkeit erheblich einschränken. Zum einen läuft die Bewegung des Stepper-Motors immer noch etwas unrund und zum anderen haben wir den "Nullpunkt" der Bewegung nicht festgelegt und verschieben den Arm immer per hand auf den geschätzten "Nullpunkt".

## Samstag, der 09.03.2019<a name="h"></a>

Endlich ist unser eigenes Gitter mit 1000 Strichen pro mm angekommen. Im Zuge dessen haben wir auch endlich eine ordentliche Halterung sowohl für das Gitter, als auch für den Laser gebaut, damit diese nun feststehen und keine weiteren Ungenauigkeiten mit sich bringen.

<img src="https://github.com/BohrisNaturalisRettner/Informatikprojekt-Spektrometer-Stundenprotokoll/blob/master/befestigung%20laser%20und%20gitter.jpg" width="1500">

## Montag, der 11.03.2019<a name="22"></a>

Heute haben wir zunächst im Informatikunterricht unsere Github Projektseite gepflegt und daraufhin am Nachmittag einen weiteren Versuch mit nun vermeintlich besseren Versuchsbedingungen durchgeführt. Allerdings entsprach das Ergebnis keineswegs unseren Vorstellungen und ebenso im Ansatz nicht dem Soll-Wert. Wir beschlossen daraufhin den Startpunkt für den Dreharm fix festzulegen, da dies eine der wenigen übrig gebliebenen möglichen Fehlerquellen war.

<img src="https://github.com/BohrisNaturalisRettner/Informatikprojekt-Spektrometer-Stundenprotokoll/blob/master/startpunkt.jpg" width="1500">

## Dienstag, der 12.03.2019<a name="i"></a>

Bevor wir heute den nächsten Versuch vorgenommen haben, haben wir zunächst den Startpunkt für den Dreharm mit einem Stopper festgelegt. Zusätzlich dazu haben wir den Schlitz vor dem Rohr verbessert indem wir zum einen schwarzes Klebeband nahmen, das um ein vielfaches weniger lichtdurchlässig ist und zum anderen den Schlitz verkleinerten. Der Versuch unter den vermutlich besten Bedingungen bis dahin ergab einen Wert von 720nm anstelle des Soll-Wertes von 650nm. Dieser Wert ist für uns zwar durchaus akzeptabel, aber bei weitem nicht das Optimum. 

## Montag, der 18.03.2019<a name="23"></a>

Aufgrund unserer anhaltenden Unzufriedenheit über die unrunde Bewegung des Armes, die so vermuten wir, zu den von uns erreichten Messergebnissen führt, überlegten wir welche Gründe dies noch haben könnte. Neben dem Stabilisationsrad, welches wir in naher Zukunft einmal ölen wollen, könnte auch der Stepper-Motor das Problem sein, da dieser eine verhältnismäßig große Masse bewegen muss. Wir überlegten nun, ob wir uns einen stärkeren Stepper-Motor kaufen.

## Dienstag, der 19.03.2019<a name="24"></a>

Auf unsere gestrigen Überlegungen zu einem stärkeren Stepper-Motor folgte heute eine ausgedehnte Internetrecherche in diversen Online-Shops und Foren, welche Stepper-Motoren stärker und schwächer sind und welche für unsere Belange am besten geeignet sind. Zum Schluss hatten wir zwar einige Favoriten, haben allerdings noch keine endgültige Entscheidung getroffen. 

## Montag, der 25.03.2019<a name="25"></a>

In der heutigen Informatikstunde haben wir uns noch einmal intensiv mit dem Stundenprotokoll auseinandergesetzt, das wir morgen abgeben müssen. An einigen Daten erfolgten Ergänzungen, die wir 

## Dienstag, der 26.03.2019<a name="26"></a>

Ebenso wie in der gestrigen Informatikstunde lag auch heute unser Fokus auf dem Stundenprotokoll, dessen Abgabe heute Abend erfolgt. In dieser Doppelstunde haben wir die letzten Punkte ergänzt und umformuliert.
