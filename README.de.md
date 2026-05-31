# IT2 - Autodarts Scoring System Handbuch

[![Discord](https://img.shields.io/badge/Discord-Server%20beitreten-5865F2?style=flat&logo=discord&logoColor=white)](https://discord.com/invite/pZAjmwV5kE)
[![Buy Me a Coffee](https://img.shields.io/badge/Buy%20Me%20a%20Coffee-Projekt%20unterstützen-FFDD00?style=flat&logo=buy-me-a-coffee&logoColor=black)](https://buymeacoffee.com/iterathor)

**Zuletzt aktualisiert:** 31. Mai 2026  
**Version:** 0.95

> 🌍 **Dieses Handbuch ist auch in anderen Sprachen verfügbar:** [English](README.md) | [Nederlands](README.nl.md)

Willkommen beim offiziellen Handbuch für das IT2 Autodarts Scoring System. Diese Anleitung führt dich durch den gesamten Montageprozess.

![dimensions](images/01_overview/dimensions.png)

---
## Inhaltsverzeichnis
1. [Allgemeine Übersicht](#1-allgemeine-übersicht)
2. [Was du benötigst](#2-was-du-benötigst)
    * [2.1 Hardware (Erforderlich)](#21-hardware-erforderlich)
    * [2.2 Erforderliches Werkzeug](#22-erforderliches-werkzeug)
3. [Allgemeine Montage: Kamera-Arme](#3-allgemeine-montage-kamera-arme)
    * [3.1 Schritt 1: Kamera-Vorbereitung & Größenanpassung](#31-schritt-1-kamera-vorbereitung--größenanpassung)
    * [3.2 Schritt 2: Vorbereitung der Schmelzeinsätze](#32-schritt-2-vorbereitung-der-schmelzeinsätze)
    * [3.3 Schritt 3: Kamera-Installation & Verschluss](#33-schritt-3-kamera-installation--verschluss)
4. [Aufbau-Optionen: Wähle deinen Weg](#4-aufbau-optionen-wähle-deinen-weg)
    * [4.1 Option 1: Winmau Plasma Lichtring](#41-option-1-winmau-plasma-lichtring)
    * [4.2 Option 2: IT2 DIY Lichtring](#42-option-2-it2-diy-lichtring)
    * [4.3 Option 3: Target Corona Lichtring](#43-option-3-target-corona-lichtring)
    * [4.4 Option 4: IT2 DIY Low Ceiling Lichtring](#44-option-4-it2-diy-low-ceiling-lichtring)
5. [Letzter Schritt: Installation & Wandmontage](#5-letzter-schritt-installation--wandmontage)
6. [Profi-Tipps & Fehlerbehebung](#6-profi-tipps--fehlerbehebung)
    * [6.1 Best Practices für die Montage](#61-best-practices-für-die-montage)
    * [6.2 Ausrichtung & Performance](#62-ausrichtung--performance)
    * [6.3 Verstecken des Winmau Plasma Stromkabels](#63-verstecken-des-winmau-plasma-stromkabels)
7. [Empfohlene Elektronik](#7-empfohlene-elektronik)
8. [Lizenzierung & Community-Support](#8-lizenzierung--community-support)


---

## 1. Allgemeine Übersicht

**Projekt Sirius** wurde mit einer klaren Vision entwickelt: der hellste Stern am Himmel zu sein. Es weist den Weg für ein Autodarts-System, das nicht nur mit bestehenden Lösungen gleichzieht, sondern in den Bereichen Ästhetik, Funktionen, Modularität und Benutzerfreundlichkeit deutlich besser sein will.

### Hauptmerkmale
*   **Schlankes Design** - Der bisher schmalste 3D-gedruckte LED-Lichtring (Stand 2026).
*   **Verdeckte Kabelführung** - Interne Kanäle für eine saubere Optik. Passt ohne Modifikationen für Corona- oder Plasma-Stromanschlüsse.
*   **Druck ohne Supports** - Für null Supports optimiert, um Materialabfall und Druckzeit zu minimieren.
*   **Universelle Kompatibilität** - Native Unterstützung für Winmau Plasma, Target Corona und IT2 DIY-Ringe.
*   **Flexible Montage** - Wähle zwischen der **Heat-Insert-Version** oder der **selbstschneidenden Version** (keine Schmelzeinsätze erforderlich).
*   **Minimalistische Hardware** - Gebaut mit nur 12x M4 Schrauben und 6x M2 Schrauben.

---

## 2. Was du benötigst

> **Hinweis:** Viele der unten aufgeführten Produktlinks sind Affiliate-Links. Wenn du über diese Links kaufst, erhalte ich eine kleine Provision ohne zusätzliche Kosten für dich, was die Entwicklung dieses Projekts unterstützt.

### 2.1 Hardware (Erforderlich)

| Teil-Name           | Typ                       | Menge | Link                 | Kommentar                                                                                                |
| ------------------- | ------------------------- | ----- | -------------------- | -------------------------------------------------------------------------------------------------------- |
| Zylinderschrauben   | M4x10mm (ISO4762/DIN912)  | 12    | [Aliexpress](https://s.click.aliexpress.com/e/_c4WUfT79)<br>[Amazon.de](https://amzn.to/49r8kCE) | Erforderlich für den Großteil der Montage.                                                               |
| Zylinderschrauben   | M2x6mm (ISO4762/DIN912)   | 6     | [Aliexpress](https://s.click.aliexpress.com/e/_c4WUfT79)<br>[Amazon.de](https://amzn.to/4u4l5du) | Kameraschrauben.                                                                                         |
| M4 Schmelzeinsätze*    | 6.3mm AD (max 9mm lang)   | 12    | [Aliexpress](https://s.click.aliexpress.com/e/_c3iaYfkD)<br>[Amazon.de](https://amzn.to/4wZr2uZ) | Ein Insert mit 6mm funktioniert ebenfalls.<br><br>*Nur für die Heat-Insert-Druckversion erforderlich.   |
> 💡 **Suchst du Empfehlungen für sonstige Hardware?** [Empfohlene Elektronik & Zubehör ansehen](#7-empfohlene-elektronik)

### 2.2 Erforderliches Werkzeug

| Werkzeug               | Zweck                                                                    |
| ---------------------- | ------------------------------------------------------------------------ |
| Inbusschlüssel-Set     | Für M4 und M2 Zylinderschrauben.                                         |
| Zange / Seitenschneider| Zum Anpassen der Kamerarahmen von 38x38 auf 32x32.                       |
| Lötkolben              | Zum Einschmelzen der M4 Schmelzeinsätze (nur Heat-Insert-Version).          |

---

## 3. Allgemeine Montage: Kamera-Arme

Bevor du deine spezifische Version (DIY, Winmau Plasma oder Target Corona) baust, musst du die drei Kamera-Arme vorbereiten und zusammenbauen. Dieser Prozess ist für alle Versionen identisch.

### 3.1 Schritt 1: Kamera-Vorbereitung & Größenanpassung
> Einige Kameras werden mit einem 38x38mm Montagerahmen geliefert. Um sie passend zu machen, musst du den **äußeren Rahmen abbrechen**, um sie auf **32x32mm** zu verkleinern.

*   Brich die perforierten Kanten vorsichtig mit einer Zange ab.

![camera-resize](images/03_general/01_camera_resize.png)

### 3.2 Schritt 2: Vorbereitung der Schmelzeinsätze
> **Selbstschneidende Version:** Wenn du diese Version gedruckt hast, kannst du diesen Schritt überspringen.

Schmelze die **M4 Inserts** mit einem Lötkolben in die Löcher der Kamera-Arme und -Köpfe ein, wie im Bild unten gezeigt.

![heat_inserts](images/03_general/02_heat_inserts.png)

### 3.3 Schritt 3: Kamera-Installation & Verschluss
**1. Montage von Kopf & Arm**  
Verbinde den Kamerakopf und den Arm mit zwei **M4 Schrauben**. Ziehe danach das USB-Kabel durch den internen Kanal des Gehäuses und schließe es an den 4-Pin-Anschluss der Kamera an.

![arm_assembly](images/03_general/03_arm_assembly.png)

**2. Montage der Kamera**  
Befestige die Kamera-Platine mit zwei **M2 Schrauben**. 

> **Hinweis:** Diese Löcher sind selbstschneidend. Die Verwendung von nur zwei Schrauben wird empfohlen und ist beabsichtigt.

**3. Lens Hood & Verschluss**  
Drehe die Lens Hood im Uhrzeigersinn in den Kameradeckel (Twist-Lock) und klicke den Deckel anschließend auf den Kopf.
> **Tipp:** Wähle zwischen den zwei verschiedenen Lens-Hood-Designs, die im Druckprofil enthalten sind.

![lens_hood](images/03_general/04_lens_hood.png)

**Endergebnis von Phase 1**  
Nach Abschluss dieser Schritte solltest du drei vollständig montierte Kamera-Arme bereit für die Installation haben.

[<img src="images/03_general/05_result_phase1.png" width="200" alt="vollständig montierte Kamera-Arme">](images/03_general/05_result_phase1.png)

---

## 4. Aufbau-Optionen: Wähle deinen Weg

Nachdem deine Kamera-Arme vorbereitet sind, wähle die Aufbauanleitung, die zu deinem Setup passt.

### 4.1 Option 1: Winmau Plasma Lichtring

> **Pro-Tipp:** Du hast die Möglichkeit, das Stromkabel des Winmau Plasma durch die internen Kanäle des IT2-Systems zu führen, um eine noch sauberere Optik zu erzielen. Dies erfordert einige zusätzliche Schritte – siehe [Abschnitt 6.3: Verstecken des Winmau Plasma Stromkabels](#63-verstecken-des-winmau-plasma-stromkabels) für Details.

**Schritt 1: Montage der Arme**  
Befestige die drei [vorbereiteten Kamera-Arme](#3-allgemeine-montage-kamera-arme) an den vorgesehenen Positionen auf dem Winmau Plasma Ring. Die IT2-Arme sind so konzipiert, dass sie perfekt auf das Profil des Plasma passen. Verwende M4 Schrauben, um sie zu sichern.  

![plasma_mounting](images/04_options/01_plasma_mounting.png)

[Zurück zum Inhaltsverzeichnis](#inhaltsverzeichnis) | **Nächster Schritt: [5. Installation an die Wand](#5-letzter-schritt-installation--wandmontage)**

---

### 4.2 Option 2: IT2 DIY Lichtring

**Schritt 1: Zusammenbau des Rings**  
Verbinde die 3D-gedruckten Segmente des IT2 DIY Lichtrings. Achte auf eine feste Verbindung, um die Stabilität zu gewährleisten.

![ring_dovetail](images/04_options/02_diy_ring_assembly.png)

**Schritt 2: LED-Installation**  
Installiere den **LED-Streifen** in den dafür vorgesehenen Kanal des Rings. Beginne unten, damit das Stromkabel sauber weggeführt werden kann.

![led_install](images/04_options/03_diy_led_install.png)

**Schritt 3: Befestigung der Arme**  
Sichere die Kamera-Arme an den integrierten Montagepunkten des DIY-Rings mit M4 Schrauben.

![arm_mounting](images/04_options/04_diy_arm_mounting.png)

[Zurück zum Inhaltsverzeichnis](#inhaltsverzeichnis) | **Nächster Schritt: [5. Installation an die Wand](#5-letzter-schritt-installation--wandmontage)**

---

### 4.3 Option 3: Target Corona Lichtring

**Schritt 1: Vorbereitung der Adapter**  
Installiere den **unteren Teil des IT2 Corona Adapters** an den drei [vorbereiteten Kamera-Armen](#3-general-assembly-camera-arms) mit M4 Schrauben. 

![corona_adapter_prep](images/04_options/05_corona_adapter_prep.png)

**Schritt 2: Montage & Ausrichtung**  
Setze den Target Corona Ring in die Vertiefungen der installierten unteren Adapterteile. 

![corona_ring_mounting](images/04_options/06_corona_ring_mounting.png)

Hake dann den **oberen Teil des Adapters** in den Ring ein und lass ihn einrasten. 

![corona_adapter_hook](images/04_options/07_corona_adapter_hook.png)

> **Tipp:** Versuche, die Adapter beim Einrasten in einem ungefähren **120-Grad-Abstand** zu positionieren. Dies minimiert den Aufwand für die spätere Feinjustierung.

![corona_alignment](images/04_options/08_corona_alignment.png)

[Zurück zum Inhaltsverzeichnis](#inhaltsverzeichnis) | **Nächster Schritt: [5. Installation an die Wand](#5-letzter-schritt-installation--wandmontage)**

---

### 4.4 Option 4: IT2 DIY Low Ceiling Lichtring

Diese Version wurde speziell für Räume mit geringer Deckenhöhe entwickelt. Sie erfordert eine Deckenhöhe von mindestens **2,00m**.

**Schritt 1: Zusammenbau des Rings**  
Verbinde die 3D-gedruckten Segmente des IT2 DIY Lichtrings durch Zusammenschieben der **Schwalbenschwanzverbindungen**. Verwende die **3 Montage-Segmente** und **6 Zwischensegmente** in der richtigen Reihenfolge für eine perfekte 120°-Ausrichtung.

*(Bild-Platzhalter: Low Ceiling Ring Zusammenbau)*

> **Hinweis:** Alle Segmente müssen bündig aneinanderliegen. Die Verbindungen sollten sich mit mäßigem Kraftaufwand zusammenschieben lassen. Falls sie zu fest sitzen, liegt dies meist an Druckertoleranzen oder nicht kalibriertem Filament. Schleife in diesem Fall die Kanten vorsichtig ab.

**Schritt 2: LED-Installation**  
Installiere den **LED-Streifen** wie im Bild unten gezeigt. Achte darauf, dass der Streifen die tiefste Fläche berührt, um optimale Ergebnisse zu erzielen.

*(Bild-Platzhalter: Low Ceiling LED Installation)*

**Schritt 3: Befestigung der Arme**  
Sichere die Kamera-Arme an den integrierten Montagepunkten des DIY-Rings mit M4 Schrauben.

*(Bild-Platzhalter: Low Ceiling Arm Montage)*

[Zurück zum Inhaltsverzeichnis](#inhaltsverzeichnis) | **Nächster Schritt: [5. Installation an die Wand](#5-letzter-schritt-installation--wandmontage)**

---

## 5. Letzter Schritt: Installation & Wandmontage

Das IT2-System bietet zwei Hauptinstallationswege, je nach deinen Anforderungen an Ästhetik, Montageaufwand und Wandschutz.

### 5.1 Option A: Direktmontage
In dieser Konfiguration wird das IT2-System direkt an der Wand montiert. Dies erfordert das Bohren von bis zu 8 Löchern (je 2 pro Bein und 2 für dein Dartboard).
*   **Vorteile:** Weniger Teile zum Zusammenbauen; minimaler Platzbedarf; das System sitzt bündig an der Wand.
*   **Nachteile:** Erfordert mehr Bohrpunkte in der Wand; die Positionen für die Beine müssen manuell durch Messen, Anzeichnen oder eine Bohrschablone ermittelt werden.

### 5.2 Option B: IT2 Baseplate
Die **IT2 Baseplate** ist eine optionale Einheit, die den Installationsprozess vereinfacht und zusätzliche Funktionen bietet.

*   **Vorteile:**
    *   **Einfache Installation:** Zentriere die Platte auf dem Bullseye und montiere sie waagerecht; das komplette Setup wird dann mit nur drei Wandschrauben an der Platte befestigt.
    *   **Wandschutz:** Erfordert nur **3 Löcher**, die in die Wand gebohrt werden müssen.
    *   **Schallschutz:** Verfügt über ein integriertes, optionales Schallschutzsystem.
    *   **Ständer-Kompatibilität:** Kann standardmäßig auf einem Dartständer installiert werden (z. B. Winmau Xtreme Dartboard Stand 2).
*   **Nachteile:**
    *   **Wandabstand:** Die Basisplatte fügt ca. **30mm Tiefe** hinzu. Du **MUSST** den Abstand deiner Oche (Abwurflinie) um 30mm anpassen, um die offiziellen Maße einzuhalten.

[Zurück zum Inhaltsverzeichnis](#inhaltsverzeichnis)

---

## 6. Profi-Tipps & Fehlerbehebung

Um das bestmögliche Erlebnis mit deinem IT2-System zu gewährleisten, befolge diese Profi-Tipps.

### 6.1 Best Practices für die Montage
Wenn du die Kameras mit M2-Schrauben und den Rahmen mit M4-Schrauben sicherst, ziehe diese nur **"handfest"** an.
*   Vermeide übermäßiges Festziehen, da dies die 3D-gedruckten Gewinde belasten oder die Kamera-Platine leicht verbiegen kann, was den Fokus beeinträchtigen könnte.

### 6.2 Ausrichtung & Performance
#### 120°-Ausrichtung
Die korrekte Ausrichtung ist entscheidend für die Scoring-Genauigkeit. Je nach Version wird dies unterschiedlich gehandhabt:

*   **Target Corona:** Da die Adapter ein freies Verschieben auf dem Ring ermöglichen, musst du darauf achten, sie manuell in einem Winkel von exakt **120 Grad** zueinander auszurichten.

### 6.3 Verstecken des Winmau Plasma Stromkabels
**Schritt 1:** ...
**Schritt 2:** ...

[Zurück zum Inhaltsverzeichnis](#inhaltsverzeichnis)

---

## 7. Empfohlene Elektronik

| Teil-Name    | Typ                                    | Link       | Kommentar                                      |
| ------------ | -------------------------------------- | ---------- | ---------------------------------------------- |
| Kameras      | HBV OV2710                             | Aliexpress | Beste Preis-Leistungs-Kameras.                 |
| LED-Streifen | Auxmer 12V 9.6W LED-Streifen           | Aliexpress | Mein Favorit. Beste Farbwiedergabe.            |
| PC           | Dell Wyse 5070 >=4GB RAM >= 16 Storage | Aliexpress | Mein Favorit. Gutes Preis-Leistungs-Verhältnis. |
| Touchscreen  | Anmite 16" Touchscreen                 | Aliexpress | Mein Favorit. Gutes Preis-Leistungs-Verhältnis. |

---

## 8. Lizenzierung & Community-Support

### Kommerzielle Lizenz
*   **Gewinnerzielungsabsicht:** Der Verkauf dieses Designs mit Gewinnabsicht erfordert eine aktive kommerzielle Lizenz, erhältlich über mein [Makerworld-Profil](https://makerworld.com/en/@HipsThor/). Verkäufe sind nur während eines aktiven Abonnements gestattet.

### Ausnahmen (Nicht-kommerziell)
*   **Privat & Sozial:** Das Teilen mit Freunden, Familie oder deinem lokalen Dartclub (nur zu Materialkosten) ist ausdrücklich erwünscht und erfordert keine Lizenz. Ich freue mich über Feedback oder eine kleine Spende, wenn dir das Projekt gefällt.
*   **Community-Unterstützung:** Das Drucken für Community-Mitglieder, die keinen eigenen Drucker besitzen (Materialkosten + kleine Bearbeitungsgebühr), ist erlaubt, **MUSS** aber transparent gehandhabt und vorher mit mir (**IteraThor**) auf Discord besprochen werden.

### Unterstütze das Projekt
*   **Feedback:** Tritt dem Discord bei oder hinterlasse einen Kommentar auf Makerworld.
*   **Spenden:** Unterstütze die Entwicklung hier: [Buy Me a Coffee](https://www.buymeacoffee.com/IteraThor)

---
--
terlasse einen Kommentar auf Makerworld.
*   **Spenden:** Unterstütze die Entwicklung hier: [Buy Me a Coffee](https://www.buymeacoffee.com/IteraThor)

---
--
