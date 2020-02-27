# PBD
*„Constraints are as fundemental in game physics, as shaders are in computer graphics“* - **Erin Catto**

![](Cover.png)

## Facharbeit

Der Quellcode und Programm zur Facharbeit  ***"Positionsbedingte Dynamiken"***.
Verfasst von **Benedikt Schöps** _(@m4dh0rs3)_.
Abgegeben am 28.02.2020 am **Clara-Wieck-Gymnasium Zwickau.**

Basierend auf dem Paper [***"Position Based Dynamics"***](https://matthias-research.github.io/pages/publications/posBasedDyn.pdf) von u.A. **Matthias Müller**

- Betreuer: **Lucas Völkel**

- Lektoren: **Jonathan Schöps, Daniel Schöps**

## Bedinung
- Nach dem Starten des Programmes kannst du mit der **Linken Maustaste Massepunkte erschaffen**. 
Du kannst damit auch ein Massepunkt bewegen.

- Wenn du diesen mit **Rechtsklick** anwählst, setzt du die Masse auf Infinity. Somit ist der **Punkt statisch**.
Hälst du weiter **Rechtsklick** gedrückt, kannst du den Massepunkt mit einem Zweiten verbinden,
um deren Bewegung zueinander einzuschränken. So kannst du ganze komplexe Körper bauen.

- Mit der **Leertaste** kannst du die Simulation **anhalten**. 
Veränderst du dann die Position eines Massepunktes, werden verbundene Zwangsbedingung für den Abstand auch verlängert.

- Mit **R** kannst du aktivieren, ob der Radius des Massepunktes mit in die Simulation einbezogen werden soll. 
- Mit **K** lässt sich das zugrundeliegende Skelett der Körper anzeigen.

- Mit **Q** kannst du eine Box erschaffen.
- Mit **T** kannst du ein Dreieck erschaffen.
- Mit **S** speicherst du das aktuelle System in Kurzform in der Zwichenablage ab.



## Instalation
### Windows:
1. Lade den kompremierten Ordner _"PBD-Windows"_ herunter
2. Schlüssle ihn mit 7-Zip oder RAR auf.
3. Neben den DLL-Bibliotheken ist die Anwendungsdatei _"PBD"_ vorhanden. Wen du bereits das Framework LÖVE2D instaliert hast, dann kanst du auch die Datei mit dem Suffix _".love"_ ausführen.

### Linux:
1. Instaliere das LÖVE2D Package. Dazu gibt es auf [LÖVE2D.ORG](https://love2d.org) mehr informationen
2. Lade dir die Datei _"PBD.love"_ herunter.
3. Je nach Desktop kannst du das Programm mit einem Doppelklick, alternativ auch mit $ love PBD.love ausführen.

### Android:
Du kannst das PBD-Programm auch auf Android ausführen. Bitte folge [dieser Anleitung](https://love2d.org/wiki/Getting_Started#Android).
