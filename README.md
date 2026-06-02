# IT2 - Autodarts Scoring System Manual

[![Discord](https://img.shields.io/badge/Discord-Join%20My%20Server-5865F2?style=flat&logo=discord&logoColor=white)](https://discord.com/invite/pZAjmwV5kE)
[![Buy Me a Coffee](https://img.shields.io/badge/Buy%20Me%20a%20Coffee-Support%20Project-FFDD00?style=flat&logo=buy-me-a-coffee&logoColor=black)](https://buymeacoffee.com/iterathor)

> 🌍 **This manual is available in other languages:** [Deutsch](README.de.md) | [Nederlands](README.nl.md)  
> 🛠️ **Optional Upgrade:** Looking for the mounting plate? [View the IT2 Baseplate Manual](BASEPLATE.md)
>
> ---
> *Note: As a solo designer managing this entire project, I use AI assistance to help with the extensive documentation. Some parts may contain AI-generated errors or misunderstandings. Until I have the time to fully review and refine every section, please stay attentive and reach out on Discord if you encounter any issues.*

Welcome to the official manual for the IT2 Autodarts Scoring System. This guide will walk you through the assembly process.

> 📥 **Download Files:** [IT2 System on Makerworld](https://makerworld.com/en/models/1013725)

![dimensions](images/01_overview/dimensions.png)

---
## Table of Contents
1. [General Overview](#1-general-overview)
2. [What You'll Need](#2-what-youll-need)
    * [2.1 Core Hardware (Required)](#21-core-hardware-required)
    * [2.2 Required Tools](#22-required-tools)
3. [General Assembly: Camera Arms](#3-general-assembly-camera-arms)
    * [3.1 Step 1: Camera Preparation & Resizing](#31-step-1-camera-preparation--resizing)
    * [3.2 Step 2: Heat Inserts Preparation](#32-step-2-heat-inserts-preparation)
    * [3.3 Step 3: Camera Installation & Closing](#33-step-3-camera-installation--closing)
4. [Build Options: Choose Your Path](#4-build-options-choose-your-path)
    * [4.1 Option 1: Winmau Plasma Light Ring](#41-option-1-winmau-plasma-light-ring)
    * [4.2 Option 2: IT2 DIY Light Ring](#42-option-2-it2-diy-light-ring)
    * [4.3 Option 3: Target Corona Light Ring](#43-option-3-target-corona-light-ring)
    * [4.4 Option 4: IT2 DIY Low Ceiling Light Ring](#44-option-4-it2-diy-low-ceiling-light-ring)
5. [Final Step: Installation & Wall Mounting](#5-final-step-installation--wall-mounting)
    * [5.1 Mounting Instructions: Direct Wall Mounting (Option A)](#51-mounting-instructions-direct-wall-mounting-option-a)
    * [5.2 Mounting Instructions: Baseplate Mounting (Option B)](#52-mounting-instructions-baseplate-mounting-option-b)
6. [Pro Tips & Troubleshooting](#6-pro-tips--troubleshooting)
    * [6.1 Assembly Best Practices](#61-assembly-best-practices)
    * [6.2 Hiding Winmau Plasma Power Cable](#62-hiding-winmau-plasma-power-cable)
    * [6.3 Hiding Target Corona Power Cable](#63-hiding-target-corona-power-cable)
7. [Recommended Electronics](#7-recommended-electronics)
8. [FAQ](#8-faq)
9. [Licensing & Community Support](#9-licensing--community-support)
10. [Support the Project](#10-support-the-project)


---

## 1. General Overview

**Project Sirius** was designed with a clear vision: to be the brightest star in the sky. It points the way forward for an Autodarts system that is not only on par with existing solutions but aims to be significantly better in aesthetics, features, modularity, and ease of use.

### Key Features
*   **Sleek & Slim Design** - The slimmest 3D-printed LED Light Ring as of 2026.
*   **Hidden Cable Management** - Internal routing for a clean look. Fits Corona or Plasma power barrels without any modifications.
*   **No-Support Printing** - Designed for zero supports, minimizing material waste and print time.
*   **Universal Compatibility** - Native support for Winmau Plasma, Target Corona, and IT2 DIY Rings.
*   **Flexible Assembly** - Choose between the **Heat Insert** version or the **Self-Tapping** version (no heat inserts required).
*   **Minimalist Hardware** - Built using only 12x M4 screws and 6x M2 screws.

---

## 2. What You'll Need

> **Note:** Many of the product links below are affiliate links. If you use them to make a purchase, I may receive a small commission at no additional cost to you, which helps support the development of this project.

> 🖨️ **3D Printing:** If you are not using the Makerworld .3mf profiles, please refer to the **[Universal Printing Guide](PRINTING.md)** for recommended settings and materials.

### 2.1 Core Hardware (Required) 

| Part Name          | Type                    | qty | Link                                                                                             | Comment                                                            |
| ------------------ | ----------------------- | --- | ------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------ |
| Cylindrical Screws | M4 (ISO4762/DIN912)     | 12  | [Aliexpress](https://s.click.aliexpress.com/e/_c4WUfT79)<br>[Amazon.de](https://amzn.to/49r8kCE) | Required for most of the assembly                                  |
| Cylindrical Screws | M2 (ISO4762/DIN912)     | 6   | [Aliexpress](https://s.click.aliexpress.com/e/_c4WUfT79)<br>[Amazon.de](https://amzn.to/4u4l5du) | Camera Screws.                                                     |
| M4 Heat Inserts ⚠️   | 6.3mm OD (max 9mm long) | 12  | [Aliexpress](https://s.click.aliexpress.com/e/_c3iaYfkD)<br>[Amazon.de](https://amzn.to/4wZr2uZ) | 6mm OD also fits. <br><br>⚠️ **Only for the heat insert version.** |

> 💡 **Looking for more?** [View Recommendations for Electronics & Accessories](#7-recommended-electronics)

### 2.2 Required Tools

| Tool                  | Link                                 | Purpose                                                          |
| --------------------- | ------------------------------------ | ---------------------------------------------------------------- |
| Hex Key Set           | [Aliexpress](https://s.click.aliexpress.com/e/_c3OuwTrf)<br>[Amazon.de](https://amzn.to/4nWmdhU) | For M4 and M2 cylindrical screws.                                |
| Pliers / Side Cutters | [Aliexpress](https://s.click.aliexpress.com/e/_c4NYxuoH)<br>[Amazon.de](https://amzn.to/3PBMeql) | Required for resizing the camera frames from 38x38 to 32x32.     |
| Soldering Iron        | [Aliexpress](https://s.click.aliexpress.com/e/_c3Jtjkzn)<br>[Amazon.de](https://amzn.to/3PBMeql) | Required for melting M4 heat inserts (Heat Insert version only). |

---

## 3. General Assembly: Camera Arms

Before building your specific version (DIY, Winmau Plasma, or Target Corona), you need to prepare and assemble the three camera arms. This process is identical for all versions.

### 3.1 Step 1: Camera Preparation & Resizing
...
