Stavba robota
=============

Robot je postaven podle:

http://www.nxtprograms.com/NXT2/multi-bot/vehicle/steps.html

Zapojení:
=========
* IN 1: senzor light
* IN 2: senzor ultrasonic
* IN 3: senzor zvuk
* OUT_B: motor levy pas
* OUT_C: motor pravy pas

![Multibot](https://github.com/jiristepan/legoboti/blob/master/legonxt/multibot/multibot.jpg?raw=true)

Algoritmy
=========
- nejprve jsme zkoušeli naivní algoritmus carovac.nxc, ktery jednoduse jede pokud vidi caru a toci se pokud ji nevidi. Pomale, ale spolehlive.
- nasledne jsme zkusili algoritmy stridajici pravou a levou zatacku dle toho, zda vidi svetlou nebo bilou. Postupne jsme je doplnili o zvyseni zataceni, pokud robot jednu barvu vidi dlouho. Tyto jsou cara.nxc a cara-best.nxc

Vysledek cara-best.nxc.

[Video jizdy](https://youtu.be/TfHb00dVfD4)

