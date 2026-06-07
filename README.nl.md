# IT2 - Autodarts Scoring Systeem Handleiding

[![Discord](https://img.shields.io/badge/Discord-Join%20My%20Server-5865F2?style=flat&logo=discord&logoColor=white)](https://discord.com/invite/pZAjmwV5kE)

**Versie:** 1.0 (BETA)

> 🌍 **Deze handleiding is beschikbaar in andere talen:** [English](README.md) | [Deutsch](README.de.md)  
> 🛠️ **Optionele Upgrade:** Op zoek naar de montageplaat? [Bekijk de IT2 Baseplate Handleiding](BASEPLATE.nl.md)
> ---
> *Opmerking: Omdat ik dit project alleen beheer, gebruik ik AI voor de tijdrovende klusjes in de documentatie – vooral voor de links en de zinsopbouw. Mijn focus ligt nu op het online krijgen van alle technische inhoud, zodat jullie zo snel mogelijk kunnen beginnen met bouwen. Ik ga alles later nog uitgebreid nalezen en de formuleringen "gladstrijken", maar laat het me tot die tijd weten via Discord als er iets onduidelijk is!*
>
> ⚠️ **Opmerking:** Deze handleiding is vertaald met behulp van AI. Er kunnen vertaalfouten aanwezig zijn.

Welkom bij de officiële handleiding voor het IT2 Autodarts Scoring Systeem. Deze gids begeleidt je door het montageproces.

> 📥 **Bestanden downloaden:** [IT2 Systeem op Makerworld](https://makerworld.com/en/models/1334165)

![dimensions](images/01_overview/dimensions.png)

---
## Inhoudsopgave
1. [Algemeen Overzicht](#1-algemeen-overzicht)
2. [Wat heb je nodig](#2-wat-heb-je-nodig)
    * [2.1 Kernhardware (Vereist)](#21-kernhardware-vereist)
    * [2.2 Vereist Gereedschap](#22-vereist-gereedschap)
3. [Algemene Montage: Camera-armen](#3-algemene-montage-camera-armen)
    * [3.1 Stap 1: Camera Voorbereiding & Aanpassen](#31-stap-1-camera-voorbereiding--aanpassen)
    * [3.2 Stap 2: Schmelzeinsätze (Heat Inserts) Voorbereiden](#32-stap-2-schmelzeinsätze-heat-inserts-voorbereiden)
    * [3.3 Stap 3: Camera Installatie & Sluiten](#33-stap-3-camera-installatie--sluiten)
4. [Bouwopties: Kies je Pad](#4-bouwopties-kies-je-pad)
    * [4.1 Optie 1: Winmau Plasma Lichtring](#41-optie-1-winmau-plasma-lichtring)
    * [4.2 Optie 2: IT2 DIY Lichtring](#42-option-2-it2-diy-light-ring)
    * [4.3 Optie 3: Target Corona Lichtring](#43-optie-3-target-corona-lichtring)
    * [4.4 Optie 4: IT2 DIY Low Ceiling Lichtring](#44-option-4-it2-diy-low-ceiling-lichtring)
5. [Pre-installatie: Camera Positionering](#5-pre-installatie-camera-positionering)
6. [Laatste Stap: Installatie & Wandmontage](#6-laatste-stap-installatie--wandmontage)
    * [6.1 Montage-instructies: Directe Wandmontage (Optie A)](#61-montage-instructies-directe-wandmontage-optie-a)
    * [6.2 Montage-instructies: Baseplate Montage (Optie B)](#62-montage-instructies-baseplate-montage-optie-b)
7. [Pro Tips & Problemen Oplossen](#7-pro-tips--problemen-oplossen)
    * [7.1 Best Practices voor Montage](#71-best-practices-voor-montage)
    * [7.2 Winmau Plasma Stroomkabel Verbergen](#72-winmau-plasma-stroomkabel-verbergen)
    * [7.3 Target Corona Stroomkabel Verbergen](#73-target-corona-stroomkabel-verbergen)
8. [Aanbevolen Elektronica](#8-aanbevolen-elektronica)
9. [Veelgestelde Vragen (FAQ)](#9-veelgestelde-vragen-faq)
10. [Licenties & Community Ondersteuning](#10-licenties--community-ondersteuning)


---

## 1. Algemeen Overzicht

### Belangrijkste Kenmerken
*   **Slank Ontwerp** - De dunste 3D-geprinte LED-lichtring vanaf 2026.
*   **Verborgen Kabelbeheer** - Interne routing voor een strak uiterlijk. Past op Corona- of Plasma-stroomaansluitingen zonder aanpassingen.
*   **Printen zonder Support** - Ontworpen voor nul supports, waardoor materiaalverspilling and printtijd worden geminimaliseerd.
*   **Universele Compatibiliteit** - Native ondersteuning for Winmau Plasma, Target Corona en IT2 DIY-ringen.
*   **Flexibele Montage** - Kies tussen de **Heat Insert** versie of de **Self-Tapping** versie (geen heat inserts vereist).
*   **Minimalistische Hardware** - Gebouwd mit slechts 12x M4x10mm schroeven en 6x M2x6mm schroeven.

---

## 2. Wat heb je nodig

> **Opmerking:** Veel van de onderstaande productlinks zijn affiliate links. Als je via deze links een aankoop doet, ontvang ik mogelijk een kleine commissie zonder extra kosten voor jou, wat de ontwikkeling van dit project ondersteunt.

> 🖨️ **3D-printen:** Als je de Makerworld .3mf-profielen niet gebruikt, raadpleeg dan de **[Universele Printgids](PRINTING.md)** for aanbevolen instellingen en materialen.

### 2.1 Kernhardware (Vereist)

| Onderdeelnaam      | Type                      | Aantal | Link | Opmerking                                                                                                |
| ------------------ | ------------------------- | ------ | ---- | -------------------------------------------------------------------------------------------------------- |
| Cilinderschroeven  | M4x10mm (ISO4762/DIN912)  | 12     | [Aliexpress](https://s.click.aliexpress.com/e/_c4WUfT79)<br>[Amazon.de](https://amzn.to/49r8kCE) | Vereist voor het grootste deel van de montage.                                                           |
| Cilinderschroeven  | M2x6mm (ISO4762/DIN912)   | 6      | [Aliexpress](https://s.click.aliexpress.com/e/_c4WUfT79)<br>[Amazon.de](https://amzn.to/4u4l5du) | Cameraschroeven.                                                                                         |
| M4 Heat Inserts ⚠️  | 6,3mm OD (max 9mm long)   | 12     | [Aliexpress](https://s.click.aliexpress.com/e/_c3iaYfkD)<br>[Amazon.de](https://amzn.to/4wZr2uZ) | 6mm OD past ook. <br><br>⚠️ **Alleen voor de Heat Insert-versie.**                                       |
> 💡 **Op zoek naar meer?** [Bekijk Aanbevelingen for Elektronica & Accessoires](#8-aanbevolen-elektronica)

### 2.2 Vereist Gereedschap

| Gereedschap            | Link                                 | Doel                                                                     |
| ---------------------- | ------------------------------------ | ------------------------------------------------------------------------ |
| Inbussleutelset        | [Aliexpress](https://s.click.aliexpress.com/e/_c3OuwTrf)<br>[Amazon.de](https://amzn.to/4nWmdhU) | Voor M4 en M2 cilinderschroeven.                                         |
| Tang / Zijkniptang     | [Aliexpress](https://s.click.aliexpress.com/e/_c4NYxuoH)<br>[Amazon.de](https://amzn.to/3PBMeql) | Nodig for het aanpassen van de cameraframes van 38x38 naar 32x32.        |
| Soldeerbout            | [Aliexpress](https://s.click.aliexpress.com/e/_c3Jtjkzn)<br>[Amazon.de](https://amzn.to/3PBMeql) | Nodig for het smelten van M4 heat inserts (alleen Heat Insert-versie).  |

---

## 3. Algemene Montage: Camera-armen

Voordat je jouw specifieke versie bouwt (DIY, Winmau Plasma of Target Corona), moet je de drie camera-armen voorbereiden en monteren. Dit proces is identiek for alle versies.

### 3.1 Step 1: Camera Voorbereiding & Aanpassen
> Sommige camera's worden geleverd mit een 38x38mm montageframe. Om ze passend te maken, moet je het **buitenframe afbreken** om ze te verkleinen naar **32x32mm**.

*   Breek de geperforeerde randen voorzichtig af mit een tang.

![camera-resize](images/03_general/01_camera_resize.png)

### 3.2 Stap 2: Schmelzeinsätze (Heat Inserts) Voorbereiden
> **Self-Tapping Versie:** Als je deze versie hebt geprint, kun je deze stap overslaan.

Smelt de **M4 inserts** in de gaten van de camera-armen and -koppen mit een soldeerbout, zoals weergegeven in de onderstaande afbeelding.

![heat_inserts](images/03_general/02_heat_inserts.png)

### 3.3 Stap 3: Camera Installatie & Sluiten
**1. Montage van Kop & Arm**  
Verbind de camerakop en de arm mit twee **M4 schroeven**. Trek daarna de USB-kabel door het interne kanaal van de behuizing en sluit deze aan op de 4-pins connector van de camera.

![arm_assembly](images/03_general/03_arm_assembly.png)

**2. Camera Installatie**  
Bevestig de camera-PCB mit twee **M2 schroeven**. 

> **Opmerking:** Deze gaten zijn zelftappend. Het gebruik van slechts twee schroeven wordt aanbevolen en is opzettelijk.

**3. Zonnekap (Lens Hood) & Sluiten**  
Draai de zonnekap mit de klok mee in het cameradeksel (twist-lock) en klik het deksel vervolgens op de kop.
> **Tip:** Kies tussen de twee verschillende zonnekap-ontwerpen die in het printprofiel zijn opgenomen.

![lens_hood](images/03_general/04_lens_hood.png)

**Eindresultaat van Fase 1**  
Na het voltooien van deze stappen heb je drie volledig gemonteerde camera-armen klaar for installatie.

[<img src="images/03_general/05_result_phase1.png" width="200" alt="volledig gemonteerde camera-armen">](images/03_general/05_result_phase1.png)

---

## 4. Bouwopties: Kies je Pad

Nadat je camera-armen zijn voorbereid, kies je de bouwhandleiding die bij jouw opstelling past.

### 4.1 Optie 1: Winmau Plasma Lichtring

> **Pro Tip:** Je hebt de mogelijkheid om de Winmau Plasma stroomkabel door de interne kanalen van het IT2-systeem te leiden for een nog strakker uiterlijk. Dit vereist een paar extra stappen - zie [Sectie 7.2: Winmau Plasma stroomkabel verbergen](#72-winmau-plasma-stroomkabel-verbergen) for details.

**Stap 1: De armen monteren**  
Bevestig de drie [voorbereide camera-armen](#3-algemene-montage-camera-armen) op de daarvoor bestemde posities op de Winmau Plasma ring. De IT2-armen zijn ontworpen om perfect op het profiel van de Plasma te passen. Gebruik M4 schroeven om ze vast te zetten.  

![plasma_mounting](images/04_options/01_plasma_mounting.png)

[Terug naar de inhoudsopgave](#inhoudsopgave) | **Volgende stap: [5. Camera Positionering](#5-pre-installatie-camera-positionering)**

---

### 4.2 Optie 2: IT2 DIY Lichtring

**Stap 1: Ring Montage**  
Verbind de 3D-geprinte segmenten van de IT2 DIY lichtring. Zorg for een stevige verbinding om de stabiliteit te behouden.

![ring_dovetail](images/04_options/02_diy_ring_assembly.png)

**Stap 2: LED-installatie**  
Installeer de **LED-strip** in het daarvoor bestemde kanaal van de ring. Begin onderaan om een schone stroomkabelrouting mogelijk te maken.

![led_install](images/04_options/03_diy_led_install.png)

**Stap 3: De armen bevestigen**  
Zet de camera-armen vast op de geïntegreerde montagepunten op de DIY-ring mit M4 schroeven.

![arm_mounting](images/04_options/04_diy_arm_mounting.png)

[Terug naar de inhoudsopgave](#inhoudsopgave) | **Volgende stap: [5. Camera Positionering](#5-pre-installatie-camera-positionering)**

---

### 4.3 Optie 3: Target Corona Lichtring

**Stap 1: Adapter Voorbereiding**  
Installeer het **onderste deel van de IT2 Corona Adapter** op de drie [voorbereide camera-armen](#3-general-assembly-camera-arms) mit M4 schroeven. 

![corona_adapter_prep](images/04_options/05_corona_adapter_prep.png)

**Step 2: Montage & Uitlijning**  
Plaats de Target Corona ring in de uitsparingen van de geïnstalleerde onderste adapteronderdelen. 

![corona_ring_mounting](images/04_options/06_corona_ring_mounting.png)

Haak vervolgens het **bovenste deel van de adapter** in de ring en klik het op zijn plaats. 

![corona_adapter_hook](images/04_options/07_corona_adapter_hook.png)

> **Tip:** Probeer de adapters op een geschatte **120-graden offset** te positioneren tijdens het vastklikken. Dit minimaliseert de hoeveelheid fijnafstelling die later nodig is.

![corona_alignment](images/04_options/08_corona_alignment.png)

> **Pro-Tip:** Je hebt de mogelijkheid om de Target Corona stroomkabel door de interne kanalen van het IT2-systeem te leiden for een nog strakker uiterlijk. Dit vereist een paar extra stappen - zie [Sectie 7.3: Target Corona stroomkabel verbergen](#73-target-corona-stroomkabel-verbergen) for details.

[Terug naar de inhoudsopgave](#inhoudsopgave) | **Volgende stap: [5. Camera Positionering](#5-pre-installatie-camera-positionering)**

---

### 4.4 Optie 4: IT2 DIY Low Ceiling Lichtring

> Deze versie is speciaal ontwikkeld for ruimtes mit een laag plafond. Er is een plafondhoogte van minimaal **2,00m** vereist.

**Montage-instructies**  
De montagelogica for deze versie is identiek aan de standaard DIY-ring. Volg de gedetailleerde **[stap-voor-stap instructies in Sectie 4.2](#42-option-2-it2-diy-light-ring)**.

> 💡 **Tip:** In tegenstelling tot de standaard ring bestaat de Low Ceiling-versie aus **6 verschillende segmenttypen**. Let op: alle drie de segmenten die op de camera's worden gemonteerd, verschillen van de standaardversie – twee daarvan zijn gespiegeld und korter om de plafondvrijheid te waarborgen. Leg alle stukken for het verbinden van de zwaluwstaarten in de juiste volgorde op de vloer om volgordefouten te voorkomen. Eenmaal verbonden zijn de stukken vaak erg moeilijk uit elkaar te trekken zonder risico op schade.

**Eindresultaat**  
Na de montage zou je Low Ceiling Lichtring er als volgt uit moeten zien:

![low_ceiling_assembly](images/04_options/09_low_ceiling_assembly.png)

[Terug naar de inhoudsopgave](#inhoudsopgave) | **Volgende stap: [5. Camera Positionering](#5-pre-installatie-camera-positionering)**

---

## 5. Pre-installatie: Camera Positionering

Voordat je jouw systeem monteert, moet je beslissen over de oriëntatie van je camera-armen. 

> **Camera Positionering**  
> Lijn de camera-armen uit mit de **11- of 6-uurs** segmenten for optimale herkenning ([Offizielle Autodarts Richtlijnen](https://autodarts.diy/getting-started/camera-positioning/)).  
> **Opmerking:** De **Low Ceiling** of **draagbare standaard** versie gebruikt in plaats daarvan het **3-uurs** segment.

![camera_positions](images/01_overview/camera_positions.png)

---

## 6. Laatste Stap: Installatie & Wandmontage

Het IT2-systeem biedt twee belangrijke installatiepaden, afhankelijk van je eisen for esthetiek, montage-inspanning und wandbescherming.

### Optie A: Directe Montage
In deze configuratie wordt het IT2-systeem direct aan de muur gemonteerd. Dit vereist het boren van **6 gaten** for de armen und **2 extra gaten voor de dartbordophanging** (indien nog niet aanwezig).
*   **Voordelen:** Minder onderdelen om te monteren; minimale voetafdruk; systeem zit vlak tegen de muur.
*   **Nadelen:** Vereist meer boorpunten; pootposities moeten handmatig worden bepaald via metingen, het tekenen van cirkels of het gebruik van een boorsjabloon.

### Option B: IT2 Baseplate
De **[IT2 Baseplate](BASEPLATE.nl.md)** is een optionele eenheid die het installatieproces vereenvoudigt und extra functies biedt zoals geluidsdemping und native standaard compatibiliteit.

Raadpleeg de **[IT2 Baseplate Handleiding](BASEPLATE.nl.md)** voor gedetailleerde, stap-voor-stap instructies voor wandmontage en uitlijning.

---

### 6.1 Montage-instructies: Directe Wandmontage (Optie A)
Er zijn twee manieren om ervoor te zorgen dat je systeem perfect is uitgelijnd bij directe montage aan de muur:

#### Methode 1: Gebruik van het IT2 Boorsjabloon (Aanbevolen)
Dit is de makkelijkste und meest nauwkeurige manier om je boorgaten te positioneren.
1. Lijn het midden van het sjabloon uit mit de door jou gemarkeerde bullseye-hoogte (1,73m).
2. Zet het sjabloon waterpas.
3. Marker de boorposities via de aangewezen punten op het sjabloon.
    > 💡 **Tip:** Om het boren te minimaliseren terwijl de perfecte stabiliteit behouden blijft, raad ik aan om slechts **twee diagonale gaten** per arm te gebruiken (bijv. linksboven und rechtsonder) in plaats von alle vier.

> 💡 **Tip:** Als je de oriëntatie van de camera-armen wilt veranderen (bijv. de hoofdarm links in plaats van rechts plaatsen), draai het sjabloon dan gewoon ondersteboven. Je kunt dann een waterpas op de onderrand gebruiken om het perfect uit te lijnen.

![drill_template](images/01_overview/drill_template.png)

#### Methode 2: Handmatig Markeren & Tekenen
Als je de posities liever zelf markeert zonder het 3D-geprinte sjabloon, volg dann de afmetingen in de onderstaande technische tekening. Dit garandeert de correcte 120-graden offset und afstand tot de bullseye.

![manual_marking](images/01_overview/manual_marking.png)

---

### 6.2 Montage-instructies: Baseplate Montage (Option B)
Raadpleeg de **[IT2 Baseplate Handleiding](BASEPLATE.nl.md)** voor gedetailleerde, stap-voor-stap instructies voor wandmontage en uitlijning.

[Terug naar de inhoudsopgave](#inhoudsopgave)

---

## 7. Pro Tips & Problemen Oplossen

Volg deze pro tips for de best mogelijke ervaring mit je IT2-systeem.

### 7.1 Best Practices voor Montage
Zorg er bij het aandraaien van schroeven for dat ze slechts **"handvast"** zitten.
*   Voorkom te vast aandraaien, omdat dit de heat inserts kan belasten.
*   **Self-Tapping Versie:** Wees extra voorzichtig mit de self-tapping versie. De plastic schroefdraad kan gemakkelijk strippen, wat **onherstelbaar** is als er te veel kracht wordt uitgeoefend.

### 7.2 Winmau Plasma Stroomkabel Verbergen
**Step 1:** ...
**Step 2:** ...
*(Instructies volgen binnenkort)*

### 7.3 Target Corona Stroomkabel Verbergen
**Step 1:** ...
**Step 2:** ...
*(Instructies volgen binnenkort)*

[Terug naar de inhoudsopgave](#inhoudsopgave)

---

## 8. Aanbevolen Elektronica

| Onderdeelnaam | Type                                   | Link | Opmerking                                    |
| ------------- | -------------------------------------- | ---- | -------------------------------------------- |
| Camera's      | HBV OV2710                             | [Aliexpress](https://s.click.aliexpress.com/e/_c4bziy33) | Beste prijs-kwaliteitverhouding camera's.    |
| LED-strip     | Auxmer 12V 9.6W LED-strip              | [Aliexpress](https://s.click.aliexpress.com/e/_c3z7FC4l) | Mijn favoriet. Beste kleurweergave.          |
| Voeding       | 12V 3A Voedingsadapter                 | [Aliexpress](https://s.click.aliexpress.com/e/_c2IYxq1R) | Vereist for de DIY LED-strip.               |
| DC-connector  | 2.1mm DC-bus                           | [Aliexpress](https://s.click.aliexpress.com/e/_c3L2uy4H) | Om de voeding op de LED's aan te sluiten.    |
| PC            | Dell Wyse 5070 ≥4GB RAM ≥ 16GB Opslag    |      | Mijn favoriet. Goede prijs-kwaliteitverhouding. |
| Touchscreen   | Anmite 16" Touchscreen                 | [Aliexpress](https://s.click.aliexpress.com/e/_c34qKHYZ) | Mijn favoriet. Goede prijs-kwaliteitverhouding. |

---

## 9. Veelgestelde Vragen (FAQ)

### V: Welke camera's moet ik kiezen?
**A:** De duidelijke winnaar for prijs-kwaliteitverhouding is de **HBV OV2710**. Investeren in duurdere camera's mit een hogere resolutie is onnodig, aangezien Autodarts beperkt is in resolutie. Hoewel de **OV9732** een goedkoper alternatief is, vereist deze aanzienlijk betere verlichting; daarom raad ik uitsluitend de OV2710 aan vanwege de superieure verwerking van verschillende lichtomstandigheden.

### V: Welke LED-strip moet ik nemen?
**A:** Vermijd USB-lichtstrips. De communitystandaard is **6000K COB LED's** (12V of 24V). Mijn persoonlijke aanbeveling is de **Auxmer 120 LED's/m (9.6W, CRI90)**; in mijn tests presteerde deze zelfs beter dann de Winmau Plasma. Als je een beperkt budget hebt, werkt elke 6000K strip mit ongeveer 10W per meter, mits deze helder genoeg is.

### V: Moet ik een Raspberry Pi of een Mini-PC gebruiken?
**A:** Tenzij je al een Raspberry Pi bezit, raad ik aan om een refurbished Mini-PC te kopen. Deze zijn vaak goedkoper (vanaf €50) und bieden betere prestaties und touchscreen-ondersteuning. Mijn persoonlijke favoriet is de **Dell Wyse 5070** (4GB RAM, 16GB opslag), die breed verkrijgbaar is als refurbished model und de Autodarts-software perfect draait.

---

## 10. Licenties & Community Ondersteuning
IT2 wordt geleverd onder een aangepaste licentie. Voor informatie over commercieel gebruik, privé delen und community-ondersteuning wordt verwezen naar het bestand **[LICENSE.md](LICENSE.md)**.
