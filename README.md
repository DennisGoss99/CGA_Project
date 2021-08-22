# **Projekt: Outerspace**

![](https://github.com/DennisGoss99/CGA_Project/blob/main/project/Application/assets/textures/gui/StartupScreen.png?raw=true "OuterspaceTitlescreen")

**Video:**
https://youtu.be/uEeNadJq5RM

**Old-Repo:**
https://github.com/DennisGoss99/Prj_OuterSpace

# Teammitglieder

- Anastasia Chouliaras [11139952]
- Dennis Goßler [11140150]

# Spielidee

Unser Spiel "Outer Space" ist ein Simulationsspiel, in dem der Spieler mit einem Raumschiff unser Sonnensystem erkunden kann.
Der Spieler kann die Bewegung der Planeten, die realitätsnah gestaltet worden sind, beobachten und sich darin bewegen.
Die Besonderheit des Spiels sind die zahlreichen Interaktionsmöglichkeiten die den Spieler die Umgebung beeinflussen lassen.

Die verschiedenen Kameraperspektiven sowie die Steuerung der Geschwindigkeit in der die Planeten sich bewegen, ermöglichen dem Spieler jede Perspektive einzunehmen.
Zusätzlich lassen sich neue Sonnensysteme generieren, sodass man die Umgebung jederzeit neu erstellen lassen kann.

Durch die verschiedenen Kameraperspektiven und die Steuerung der Geschwindigkeit in der die Planeten fliegen, sowie die Generierung neuer Sonnensysteme kann der Spieler Einfluss nehmen.

# Featureliste

## Anmerkung:
Da wir fast immer simultan an einem Features gearbeitet haben, ist nur aufgelistet, wenn alleine an einem Feature gearbeitet wurde.

## Steuerung: 
-	WASD Tasten: Richtungsangaben
-	T-Taste: Turbo, schnelles nach vorne fliegen
-	F5: Kamerawechsel zwischen Orbit und first-Person View
-	F1: Hilfemenü öffnen
-	Mausrad: Steuerung der Entfernung zum Raumschiff(nur bei Orbit-Kamera)
-	N: eine neues Sonnensystem wird generiert
-	Q/E: rollen des Ruamschiffes
-	Z: Zoom (Mausrad hoch, runter im Zommmodus)
-	TAB: Geschwindigkeitsregulierung [Dennis]
-	Spacebar: maximale Geschwindigkeit

## Selbst modellierte Objekte (mit Blender):
-	Planeten/Monde/Sonnen
- Atmosphären (Kugel mit invertieren normalen)
-	Ringe
- Cockpit [Dennis]
-	Raumschiff: Modell als Basis genommen und angepasst/verbessert
-	Asteroiden [Dennis]
-	Texturen herrausgesucht und bearbeitet [Anastasia]

## Methoden/Umsetzung:
-	Von der Sonne aus werden alle Objekte beleuchtet
-	Planeten bewegen sich automatisch und rotieren um sich selbst
-	Mehrstufige Transformation von Objekten (Sonne-Planet-Mond)
-	Sonnensysteme werden mit zufälligen Parametern neu generiert
-	Planenten können transparente Atmosphären besitzen  
-	Darstellung von GUI-Elementen 
-	Darstellen eines Willkommensbildschirm [Dennis]
-	Animationssystem [Dennis]
-	Geschwindigkeitsregulierung über GUI
-	Kamerawechsel 
-	Die Kamera hat eine Zoom Funktion
-	Entfernung, GUI-Elemente und Raketenantrieb werden in Abhängigkeit zum Kameramodus gerendert
-	Umsetzung der Umgebung als Skybox
-	wechsel zwischen verschiedenen shadern (GUI, Skybox, Partikel, etc...)
-	Multitexturing bei Planeten (z.B. die Woleken der Erde)
-	Animation des Raketenantriebs mit 2D- Partikeln 
-	in Abhängigkeit vom Kameramodus

# Änderungen zum Exposé
Wie bereits Angemerkt wurde sind die Begriffe Orbit- und 3rd-Person Kamera Synonyme.
Es wurden natürlich zwei verschiede Kameras implementiert, eine 1st-Person und eine 3rd-Person Kamera.

## Quellen:

### Texturen:

Skybox:
- https://assetstore.unity.com/packages/2d/textures-materials/sky/3-skyboxes-25142

Sonnensystem
- https://www.solarsystemscope.com/textures/

Cockpit
- https://wallpaperaccess.com/space-shuttle-cockpit

Flammen
- https://www.deviantart.com/joesalotofthings/art/Multi-Shot-02Red-Muzzle-Flash-Special-Effect-867844881

Saturn Ringe
- https://www.deviantart.com/alpha-element/art/Stock-Image-Saturn-Rings-393767006

### Modelle

Raumschiff Grundmodell
- https://free3d.com/de/3d-model/low-poly-space-ship-21086.html

### Inspirationen 
Youtube ThinMatrix Videoreihe:
- https://www.youtube.com/playlist?list=PLRIWtICgwaX0u7Rf9zkZhLoLuZVfUksDP

### Schriftarten

Nasalization
https://fonts.adobe.com/fonts/nasalization

