# IT2 System - Universal Printing Guide

This guide provides the recommended 3D printing settings and orientations for all components of the IT2 Autodarts system. 

> 💡 **Using Makerworld .3mf files?** If you are using the official print profiles on Makerworld, these settings and orientations are already pre-configured. You can skip this guide and proceed directly to assembly.
>
> ---
> *Note: Since I'm managing this project on my own, I use AI to help with the repetitive parts of the documentation - mostly for managing hyperlinks and fine-tuning the wording. I'm currently focused on getting all the technical content out there so you can start building as soon as possible. I'll be doing a full proofread and "ironing out" the phrasing later, but if you spot anything confusing in the meantime, please let me know on Discord!*

---

## Table of Contents
1. [Material Recommendations](#1-material-recommendations)
2. [General Settings (All Parts)](#2-general-settings-all-parts)
3. [Printing Orientation (STL Users)](#3-printing-orientation-stl-users)
4. [Component Specifics](#4-component-specifics)
    * [4.1 Main Components (Arms, Ring & Baseplate)](#41-main-components-arms-ring--baseplate)
    * [4.2 Baseplate Sound Dampeners (TPU)](#42-baseplate-sound-dampeners-tpu)

---

## 1. Material Recommendations

Choosing the right material depends on your environment and your printer setup.

| Environment     | Material               | Comment                                     |
| --------------- | ---------------------- | ------------------------------------------- |
| **Indoor**      | PLA                    | Sufficient for most setups                  |
| **Outdoor**     | PETG / ASA             | Better UV and temperature resistance        |
| **High-Temp**   | **PLA HT**             | Alternative if your printer is open-frame   |
| **Dampeners**   | **TPU 95A**            | Mandatory for sound insulation functionality|

> 💡 **Printer Tip:** PETG and especially ASA print best in **enclosed printers**. If you are using an **open-frame printer** (like the Bambu Lab A1), printing large ASA parts can be challenging due to warping. In this case, consider using **PLA HT (High Temperature)** for better thermal stability without the need for an enclosure.

---

## 2. General Settings (All Parts)

Unless specified otherwise, use these settings for a perfect balance of strength and printability:

| Setting         | Recommendation         | Reason                                      |
| --------------- | ---------------------- | ------------------------------------------- |
| **Layer Height**| **0.2mm**              | Mandatory for correct bridging & tolerances |
| **Wall Loops**  | 2 - 3                  | Provides structural rigidity                |
| **Infill**      | 10% - 25%              | **Cross Hatch** or **Gyroid** recommended   |
| **Supports**    | **Disabled**           | All parts are designed support-free         |

---

## 3. Printing Orientation (STL Users)

If you are importing STLs into your slicer, ensure you follow the orientations shown below for optimal strength and support-free results:

### 3.1 IT2 System (Arms & Ring)
![it2_orientation](images/02_printing/01_it2_orientation.png)

### 3.2 IT2 Baseplate
![baseplate_orientation](images/02_printing/02_baseplate_orientation.png)

### 3.3 TPU Sound Dampeners
![tpu_orientation](images/02_printing/03_tpu_orientation.png)

---

## 4. Component Specifics

### 4.1 Main Components (Arms, Ring & Baseplate)
These parts utilize the standard settings defined in Section 2.

*   **Makerworld (Main System):** [Official IT2 System Profile](https://makerworld.com/en/models/1334165)
*   **Makerworld (Baseplate):** [Official IT2 Baseplate Profile](https://makerworld.com/en/models/2782096)

> 📝 **Technical Note:** Ensure your filament is calibrated. Tight tolerances on dovetail joints require a clean print, and the 4-part baseplate design relies on the **0.2mm layer height** for optimal bridging performance.

> ⚠️ **Baseplate Hardware Tip:** If you are printing the **Self-Tapping** version of the baseplate, please note that this only applies to the M4 screws. The **M6 heat inserts** for the Rota Locks are **always mandatory** for all versions, as these components are adjusted frequently and require metal threads for long-term reliability.

### 4.2 Baseplate Sound Dampeners (TPU)
*   **Material:** TPU 95A.
*   **Infill:** 6%.
*   **Infill Type:** 3D Honeycomb.
*   **Wall Loops:** 1 or max 2.

> 📝 **Pro Tip:** Use "Print sequence: By object" to minimize stringing.

---

[Back to Main Manual](README.md) | [Back to Baseplate Manual](BASEPLATE.md)
