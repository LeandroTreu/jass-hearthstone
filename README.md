# Jasskarten Hearthstone Spiel

### Spielfeld
```
           Spieler 1

    Mana: 5/5    Leben: 5/5

           +------+
           |      |             <--- Verteidigungs Slot
           +------+
    +----+  +----+  +----+
    |    |  |    |  |    |      <--- Angriffs Slots
    |    |  |    |  |    |
    +----+  +----+  +----+


    +----+  +----+  +----+
    |    |  |    |  |    |
    |    |  |    |  |    |
    +----+  +----+  +----+
           +------+
           |      |
           +------+

    Mana: 5/5    Leben: 5/5

           Spieler 2
```
### Karten

* Ass
    * Effektkarte
    * Mana kosten: 3
    * Angriff/Leben: 0/0
    * Effekt: Zerstört eine Angriffskarte oder setzt eine Verteidigungskarte permanent auf 1/1. Wird nicht aufs Spielfeld gelegt sodern vom Spiel entfernt.

* König
    * Angriffskarte
    * Mana kosten: 3
    * Angriff/Leben: 13/8
    * Effekt: Setzt eine Angriffskarte für 1 Zug auf 1/1 (Effekt bleibt auch noch während folgendem gegnerischen Zug).

* Ober
    * Angriffskarte
    * Mana kosten: 3
    * Angriff/Leben: 12/8
    * Effekt: Spieler darf 2 karten gratis ziehen.

* Under
    * Angriffskarte
    * Mana kosten: 2
    * Angriff/Leben: 11/8
    * Effekt: keiner

* 10
    * Verteidigungskarte
    * Mana kosten: 2
    * Angriff/Leben: 10/10
    * Effekt: keiner

* 9
    * Angriffskarte
    * Mana kosten: 1
    * Angriff/Leben: 9/9
    * Effekt: keiner

* 8
    * Angriffskarte
    * Mana kosten: 1
    * Angriff/Leben: 8/8
    * Effekt: keiner

* 7
    * Angriffskarte
    * Mana kosten: 1
    * Angriff/Leben: 7/7
    * Effekt (permanent): Darf Verteidigungskarten ignorieren.

* 6
    * Verteidigungskarte
    * Mana kosten: 1
    * Angriff/Leben: 6/6
    * Effekt: Friert eine Angriffskarte für 1 Zug ein (Effekt bleibt auch noch während folgendem gegnerischen Zug).

### Spielregeln

#### Vorbereitung
* Das Jasskarten Set wird auf 2 Spieler ausgeteilt, so dass jeder Spieler einen Stapel für sich hat. Jeder Spieler zieht zu Beginn 4 Karten von seinem persönlichen Stapel.
* Jeder Spieler beginnt mit 5 Lebenspunkten.
* Jeder Spieler hat 5 Mana-punkte die Anfangs jedes Zuges auf 5/5 aufgefüllt werden.
* Derjenige Spieler der nicht beginnt hat im ersten Zug einmalig 6 Mana.
* Das Spielfeld is oben definiert und besteht aus 3 Angriffs Slots für Angriffskarten und 1 Verteidigungs Slot, der nur von Verteidigungskarten belegt werden darf.
#### Spielprinzip
Das Ziel des Spiels ist mit den gelegten Angriffskarten den Gegenspieler direkt anzugreifen um die Lebenspunkte des Gegners auf 0/5 zu bringen. Wenn ein Spieler von einer Karte angegriffen wird verliert der Spieler 1 Lebenspunkt.
* Eine Karte ausspielen kostet Mana (siehe kosten pro Karte oben).
* Eine Karte vom stapel ziehen kostet 1 Mana.
* Mit einer Karte angreifen kostet 1 Mana.
* Eine Karte die zerstört wird, wird vom Spiel entfernt und auf einen separaten Ablagestapel gelegt.
* Verteidigungskarten können nur in den Verteidigungs Slot gelegt werden. Sie schützen den Spieler; Angriffskarten (mit Ausnahme von Karte 7) müssen zwingend zuerst die Verteidigungskarte zerstören bevor sie den Spieler angreifen können. Verteidigungskarten regenerieren ihre Lebenspunkte nicht.
* Angriffskarten können nicht im selben Zug angreifen in dem sie gelegt werden. Angriffskarten regenerieren alle ihre Lebenspunkte am ende eines Zuges. Sie können nur in die Angriffs Slots gelegt werden.
* Der Effekt einer Karte wird nur einmal aktiviert beim ausspielen.

#### Spielende
##### Variante 1
Das Spiel endet sobald ein Spieler zu Beginn seines Zuges keine Aktion mehr ausführen kann.
Falls der andere Spieler genügend Karten hat um dem gegnerischen Spieler mindestens 1 Schaden zuzufügen, so verliert der Spieler, welcher keine Aktion mehr ausführen kann, 1 Leben. 
Der Spieler mit den meisten leben zum Spielende gewinnt.
Das Spiel endet frühzeitig falls ein Spieler alle Leben verliert.
##### Variante 2
Immer wenn ein Spieler den persönlichen Kartenziehstapel aufbraucht wird der Ablagestapel gemischt und zum neuen Kartenziehstapel für beide Spieler.
Der 2. Spieler behält seinen persönlichen Kartenziehstapel bis er aufgebraucht ist, bevor er auch vom neuen gemeinsamen Kartenziehstapel zieht.
Das Spiel endet erst wenn ein Spieler alle Leben verliert.