# IT2 - Autodarts Scoring System Handbuch

**Zuletzt aktualisiert:** Mittwoch, 27. Mai 2026  
**Version:** 1.0 (BETA)

> 🌍 **Dieses Handbuch ist auch in anderen Sprachen verfügbar:** [English](README.md)

Willkommen beim offiziellen Handbuch für das IT2 Autodarts Scoring System. Diese Anleitung führt dich durch den gesamten Montageprozess.

![dimensions](images/dimensions.png)

---
## Inhaltsverzeichnis
1. [Allgemeine Übersicht](#1-allgemeine-übersicht)
2. [Was du benötigst](#2-was-du-benötigst)
    * [2.1 Kern-Hardware (Erforderlich)](#21-kern-hardware-erforderlich)
    * [2.2 Empfohlene Elektronik](#22-empfohlene-elektronik)
    * [2.3 Benötigtes Werkzeug](#23-benötigtes-werkzeug)
3. [Allgemeine Montage: Kamera-Arme](#3-allgemeine-montage-kamera-arme)
    * [3.1 Schritt 1: Heat Inserts (Gewindeeinsätze)](#31-schritt-1-heat-inserts-gewindeeinsätze)
    * [3.2 Schritt 2: Kamera-Vorbereitung & Anpassung](#32-schritt-2-kamera-vorbereitung--anpassung)
4. [Aufbau-Optionen: Wähle deinen Weg](#4-aufbau-optionen-wähle-deinen-weg)
    * [4.1 Option 1: Winmau Plasma Lichtring](#41-option-1-winmau-plasma-lichtring)
    * [4.2 Option 2: IT2 DIY Lichtring](#42-option-2-it2-diy-lichtring)
    * [4.3 Option 3: Target Corona Lichtring](#43-option-3-target-corona-lichtring)
5. [Letzter Schritt: Wandmontage](#5-letzter-schritt-wandmontage)
6. [Profi-Tipps & Fehlerbehebung](#6-profi-tipps--fehlerbehebung)
    * [6.1 Best Practices für die Montage](#61-best-practices-für-die-montage)
    * [6.2 Ausrichtung & Performance](#62-ausrichtung--performance)
7. [Lizenzierung & Community-Support](#7-lizenzierung--community-support)

---

## 1. Allgemeine Übersicht

**Project Sirius** wurde mit einer klaren Vision entwickelt: der hellste Stern am Himmel zu sein. Es weist den Weg für ein Autodarts-System, das nicht nur mit bestehenden Lösungen mithalten kann, sondern in den Bereichen Ästhetik, Funktionen, Modularität und Benutzerfreundlichkeit deutlich besser sein will.

### Hauptmerkmale
*   **Schlankes & flaches Design** - Der flachste LED-Lichtring Stand 2026.
*   **Verstecktes Kabelmanagement** - Interne Kabelführung für einen sauberen, professionellen Look.
*   **Universelle Kompatibilität** - Winmau Plasma, Target Corona – und weitere in der Zukunft.
*   **Montage mit nur zwei Schraubentypen** - Minimalistische Hardware: M4 für den Zusammenbau, M2 für die Kameras.

---

## 2. Was du benötigst

> **Hinweis:** Viele der unten aufgeführten Produktlinks sind Affiliate-Links. Wenn du über diese Links etwas kaufst, erhalte ich eventuell eine kleine Provision ohne zusätzliche Kosten für dich. Dies hilft, die Entwicklung dieses Projekts zu unterstützen.

### 2.1 Kern-Hardware (Erforderlich) 

| Bauteil Name        | Typ                      | Menge | Link                 | Kommentar                                                                                                |
| ------------------ | ------------------------ | ----- | -------------------- | ------------------------------------------------------------------------------------------------------ |
| Zylinderschrauben  | M4x10mm (ISO4762/DIN912) | 12    | Aliexpress<br>Amazon | Erforderlich für den Großteil der Montage.                                                             |
| Zylinderschrauben  | M2x6mm (ISO4762/DIN912)  | 6-12  | Aliexpress<br>Amazon | Kameraschrauben.                                                                                       |
| M4 Heat Inserts*   | 6.3mm AD                 | 12    | Aliexpress<br>Amazon | Ein Einsatz mit 6mm AD funktioniert ebenfalls.<br><br>*Nur erforderlich für die Heat-Insert-Version. |

### 2.2 Empfohlene Elektronik

| Bauteil Name | Typ                                    | Link       | Kommentar                                      |
| ------------ | -------------------------------------- | ---------- | ---------------------------------------------- |
| Kameras      | HBV OV2710                             | Aliexpress | Bestes Preis-Leistungs-Verhältnis.             |
| LED-Streifen | Auxmer 5000k 12V 9.6W                  | Aliexpress | Persönlicher Favorit. Sehr naturgetreue Farben.|
| PC           | Dell Wyse 5070 >=4GB RAM >= 16 Storage | Aliexpress | Persönlicher Favorit. Gute Leistung zum Preis. |
| Touchscreen  | Anmite 16" Touchscreen                 | Aliexpress | Persönlicher Favorit. Günstiger Touchscreen.   |

### 2.3 Benötigtes Werkzeug

| Werkzeug             | Zweck                                                                   |
| -------------------- | ----------------------------------------------------------------------- |
| Innensechskant-Set   | Für M4 und M2 Zylinderschrauben.                                        |
| Zange / Seitenschneider | Zum Anpassen der Kamerarahmen von 38x38 auf 32x32.                   |
| Lötkolben            | Zum Einsetzen der M4 Heat Inserts (nur Heat-Insert-Version).            |

---

## 3. Allgemeine Montage: Kamera-Arme

Bevor du deine spezifische Version baust (DIY, Winmau Plasma oder Target Corona), musst du die drei Kamera-Arme vorbereiten. Dieser Prozess ist für alle Versionen identisch.

> **Hinweis:** Wenn du die **Self-Tapping-Version** (selbstschneidend) gedruckt hast, kannst du Schritt 1 (Heat Inserts) überspringen.

### 3.1 Schritt 1: Heat Inserts (Gewindeeinsätze)
Wenn du die **Heat-Insert-Version** verwendest, schmelze die **M4-Einsätze** mit einem Lötkolben in die vorgesehenen Löcher der Kamera-Arme.
*   Achte darauf, dass die Einsätze bündig mit der Oberfläche abschließen.

![head-to-arm-assembly](images/head-to-arm-assembly.png)

### 3.2 Schritt 2: Kamera-Vorbereitung & Anpassung
Einige Kameras werden mit einem 38x38mm Montagerahmen geliefert. Damit diese passen, musst du den **äußeren Rahmen abbrechen**, um die Größe auf **32x32mm** zu reduzieren.
*   Brich die perforierten Kanten vorsichtig mit einer Zange ab.

---

## 4. Aufbau-Optionen: Wähle deinen Weg

Nachdem deine Kamera-Arme vorbereitet sind, wähle die Aufbauanleitung, die zu deinem Setup passt.

### 4.1 Option 1: Setup mit Winmau Plasma Lichtring

**Schritt 1:** ...
**Schritt 2:** ...

[Zurück zum Inhaltsverzeichnis](#inhaltsverzeichnis)

---

### 4.2 Option 2: Setup mit IT2 DIY Lichtring

**Schritt 1:** ...
**Schritt 2:** ...

[Zurück zum Inhaltsverzeichnis](#inhaltsverzeichnis)

---

### 4.3 Option 3: Target Corona Lichtring

**Schritt 1:** ...
**Schritt 2:** ...

[Zurück zum Inhaltsverzeichnis](#inhaltsverzeichnis)

---

## 5. Letzter Schritt: Wandmontage

**Schritt 1:** ...
**Schritt 2:** ...

[Zurück zum Inhaltsverzeichnis](#inhaltsverzeichnis)

---

## 6. Profi-Tipps & Fehlerbehebung

Befolge diese Tipps und Best Practices, um das bestmögliche Erlebnis mit deinem IT2-System zu gewährleisten.

### 6.1 Best Practices für die Montage
Wenn du die Kameras mit M2-Schrauben und den Rahmen mit M4-Schrauben befestigst, ziehe diese nur **"handfest"** an.
*   Vermeide übermäßiges Festziehen, da dies die 3D-gedruckten Gewinde belasten oder die Kamera-Platine leicht biegen kann, was den Fokus beeinträchtigen könnte.

### 6.2 Ausrichtung & Performance
#### 120° Ausrichtung
Die korrekte Ausrichtung ist entscheidend für die Genauigkeit der Punkteerfassung. Je nach Version wird dies unterschiedlich gehandhabt:

*   **Winmau Plasma & DIY Ring:** Diese Setups verfügen über eine **"Hardware-Locked"** Ausrichtung. Solange die Arme korrekt sitzen, sind deine 120-Grad-Winkel mathematisch perfekt – es sind keine manuellen Ausrichtungswerkzeuge erforderlich.
*   **Target Corona:** Da die Adapter frei auf dem Ring verschiebbar sind, musst du darauf achten, sie manuell in einem Winkel von exakt **120 Grad** zueinander auszurichten, um eine optimale Genauigkeit zu erreichen.

---

## 7. Lizenzierung & Community-Support

### Kommerzielle Lizenz
*   **Verkauf mit Gewinnabsicht:** Der Verkauf dieses Designs erfordert eine aktive kommerzielle Lizenz, die über mein [Makerworld-Profil](https://makerworld.com/en/@HipsThor/) erhältlich ist. Verkäufe sind nur zulässig, solange das Abonnement aktiv ist.

### Ausnahmen (Nicht-kommerziell)
*   **Persönlich & Sozial:** Das Teilen mit Freunden, Familie oder deinem lokalen Dartclub (nur zum Materialpreis) ist ausdrücklich erwünscht und erfordert keine Lizenz. Ich freue mich über Feedback oder eine kleine Spende, wenn dir das Projekt gefällt.
*   **Community-Unterstützung:** Das Drucken für Community-Mitglieder, die keinen eigenen Drucker besitzen (Materialpreis + kleine Bearbeitungsgebühr), ist erlaubt, **MUSS** aber transparent gehandhabt und vorher mit mir (**IteraThor**) auf Discord besprochen werden.

### Unterstütze das Projekt
*   **Feedback:** Tritt dem Discord bei oder hinterlasse einen Kommentar auf Makerworld.
*   **Spenden:** Unterstütze die Entwicklung hier: [Buy Me a Coffee](https://www.buymeacoffee.com/IteraThor)

---
