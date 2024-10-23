# Code Strucktur

In diesem Kapitel werden wir den grundlegenden Rahmen des QR-Codes auf kariertem
Papier aufbauen. Der Rahmen besteht aus mehreren wichtigen Elementen: den
Positionierungsmarken, den Timing-Patterns und der Ruhezone. Diese Elemente sind
entscheidend für die korrekte Funktion des QR-Codes. Zusätzlich legen wir die
Größe des QR-Codes fest und betonen, dass er quadratisch ist.

## QR-Code Größe und Form

Ein QR-Code ist immer quadratisch, das bedeutet, dass die Höhe und Breite gleich
sind.
Die Größe eines QR-Codes wird in "Modulen" gemessen, wobei jedes Modul ein
einzelnes Kästchen auf dem karierten Papier darstellt.
Die Gesamtgröße des QR-Codes hängt von der Menge der zu kodierenden Daten und
der Fehlerkorrektur-Stufe ab.

### Größenfestlegung

Bestimme die Anzahl der Module, die dein QR-Code haben soll.
Ein typischer kleiner QR-Code hat eine Größe von 21x21 Modulen.
Je mehr Daten du kodieren möchtest, desto größer wird der QR-Code.
Zeichne ein quadratisches Raster mit der festgelegten Anzahl von Modulen auf
deinem karierten Papier. Dies wird der Rahmen für deinen QR-Code sein.

## Positionierungsmarken

Die Positionierungsmarken sind drei große quadratische Muster, die sich in drei der vier Ecken des QR-Codes befinden. Sie helfen dem QR-Code-Scanner, den Code korrekt auszurichten und zu erkennen. Jede Positionierungsmarke besteht aus:

1. Einem 3x3 schwarzen Quadrat in der Mitte.
2. Einem 1 Kästchen breiten weißen Rand um das schwarze Quadrat.
3. Einem 1 Kästchen breiten schwarzen Rand um den weißen Rand.

### Schritt-für-Schritt-Anleitung:

1. Wähle eine Ecke deines karierten Papiers, um die erste Positionierungsmarke
zu platzieren.
2. Zeichne ein 3x3 Quadrat aus schwarzen Kästchen.
3. Lasse um das schwarze Quadrat einen 1 Kästchen breiten weißen Rand.
4. Zeichne um den weißen Rand einen 1 Kästchen breiten schwarzen Rand.
5. Wiederhole diesen Vorgang für die beiden anderen Ecken
(oben links, oben rechts und unten links).

## Timing-Patterns

Die Timing-Patterns helfen dem QR-Code-Scanner, die Größe der Module (Kästchen)
zu bestimmen und den QR-Code zu entschlüsseln.
Diese bestehen aus abwechselnden schwarzen und weißen Kästchen und verlaufen
horizontal und vertikal zwischen den Positionierungsmarken.

## Ruhezone

Die Ruhezone ist ein leerer Rand um den gesamten QR-Code, der dafür sorgt
, dass der Code korrekt gelesen wird.
Diese Zone besteht aus mindestens 4 leeren Kästchen (weiße Kästchen) rund um den QR-Code.

## Synchronisationsmuster

Diese befinden sich in der Mitte des QR-Codes und helfen bei der korrekten Ausrichtung der Datenmodule.

## Formatinformationen

Diese enthalten Informationen über die Fehlerkorrektur und die Maske des QR-Codes.

## Versionsinformationen

 Bei größeren QR-Codes geben Diese die Version des QR-Codes an.