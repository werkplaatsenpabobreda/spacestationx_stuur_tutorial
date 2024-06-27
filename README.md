# SpaceStationX Stuurprogramma

## Introduction @showdialog
We gaan de instructies schrijven (programmeren) voor het stuur van de escapepod.

Verbind de micro:bit met de usb kabel aan je laptop.  
klik op de de drie puntjes naast ``Download`` en verbind de microbit door op de knop ``connect device`` te klikken.    
  
Volg de instructies.


## Stap 1

Sleep uit de categorie **basic** het block ``||basic:on start||`` in het grijze werkveld.  

*Deze instructies worden uitgevoerd als de microbit stroom krijgt doordat deze  verbonden wordt aan een batterij of aan een computer via een usbkabel, of wanneer deze gereset wordt.*

## Stap 2
Sleep uit de categorie **SpaceStationX** het blokje
``||SpaceStationX.prepareCommunications||``  en plaats deze binnen  ``||basic:on start||``.   

*Deze instructie bereidt de draadloze communicatie met de hoofdcomputer van SpaceStationX voor.*

## Stap 3
Sleep uit de categorie **SpaceStationX** het blokje
``||SpaceStationX.startSteeringWheelCommunication||`` en plaats deze binnen  ``||basic:on start||``  onder  ``||SpaceStationX.prepareCommunications||`` 

*Deze instructie start de communicatie van het stuur (de microbit) met de navigatie computer van de escape.*

## Stap 4
Sleep uit de categorie **SpaceStationX** het blok  ``||SpaceStationX.setHeading||`` en plaats deze binnen  ``||basic:on start||``  onder  ``||SpaceStationX.prepareCommunications||``  
Voer het juiste getal in voor de 'heading'.  

*Deze waarde komt uit een andere puzzel*

## Stap 5
Sleep uit de categorie **Loops** het blok  ``||Loops.every||``
en verander de waarde in het blokje naar 50

## Stap 6
Plaats uit de categorie **SpaceStationX** het blokje
``||SpaceStationX.calibrateSteeringWheel||`` binnen het blok  ``||Loops.every||``

##stap 7
Zoek in de categorie **Input...more** naar een blokje dat een rotatie van de microbit op een bepaalde as teruggeeft en plaats er twee in de vakjes van het blokje ``||SpaceStationX.calibrateSteeringWheel||`` 
``vraag eventueel om een hint ``

##Probeer je instructies
Klik op de knop ``Download``.  
Je instructies worden nu op de microbit gezet.
*Iedere keer dat je aanpassingen maakt in je instructies zul weer op de knop ``Download`` moeten klikken.*

##Koppel de escapepod computer
Sluit de microbit nu aan op de escapepod computer en test of je code werkt.  
De calibratie modus zou moeten starten op het scherm.

