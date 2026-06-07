# IT2 - Autodarts Scoring System Manual

[![Discord](https://img.shields.io/badge/Discord-Join%20My%20Server-5865F2?style=flat&logo=discord&logoColor=white)](https://discord.com/invite/pZAjmwV5kE)

> 🌍 **This manual is available in other languages:** [Deutsch](README.de.md) | [Nederlands](README.nl.md)  
> 🛠️ **Optional Upgrade:** Looking for the mounting plate? [View the IT2 Baseplate Manual](BASEPLATE.md)
> ---
> *Note: Since I'm managing this project on my own, I use AI to help with the repetitive parts of the documentation - mostly for managing hyperlinks and fine-tuning the wording. I'm currently focused on getting all the technical content out there so you can start building as soon as possible. I'll be doing a full proofread and "ironing out" the phrasing later, but if you spot anything confusing in the meantime, please let me know on Discord!*

Welcome to the official manual for the IT2 Autodarts Scoring System. This guide will walk you through the assembly process.

> 📥 **Download Files:** [IT2 System on Makerworld](https://makerworld.com/en/models/1334165)

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
5. [Pre-Installation: Camera Positioning](#5-pre-installation-camera-positioning)
6. [Final Step: Installation & Wall Mounting](#6-final-step-installation--wall-mounting)
    * [6.1 Mounting Instructions: Direct Wall Mounting (Option A)](#61-mounting-instructions-direct-wall-mounting-option-a)
    * [6.2 Mounting Instructions: Baseplate Mounting (Option B)](#62-mounting-instructions-baseplate-mounting-option-b)
7. [Pro Tips & Troubleshooting](#7-pro-tips--troubleshooting)
    * [7.1 Assembly Best Practices](#71-assembly-best-practices)
    * [7.2 Hiding Winmau Plasma Power Cable](#72-hiding-winmau-plasma-power-cable)
    * [7.3 Hiding Target Corona Power Cable](#73-hiding-target-corona-power-cable)
8. [Recommended Electronics](#8-recommended-electronics)
9. [FAQ](#9-faq)
10. [Licensing & Community Support](#10-licensing--community-support)


---

## 1. General Overview

### Key Features
*   **Sleek & Slim Design** - The slimmest 3D-printed LED Light Ring as of 2026.
*   **Hidden Cable Management** - Internal routing for a clean look. Fits Corona or Plasma power barrels without any modifications.
*   **No-Support Printing** - Designed for zero supports, minimizing material waste and print time.
*   **Universal Compatibility** - Native support for Winmau Plasma, Target Corona, and IT2 DIY Rings.
*   **Flexible Assembly** - Choose between the **Heat Insert** version or the **Self-Tapping** version (no heat inserts required).
*   **Minimalist Hardware** - Built using only 12x M4x10mm screws and 6x M2x6mm screws.

---

## 2. What You'll Need

> **Note:** Many of the product links below are affiliate links. If you use them to make a purchase, I may receive a small commission at no additional cost to you, which helps support the development of this project.

> 🖨️ **3D Printing:** If you are not using the Makerworld .3mf profiles, please refer to the **[Universal Printing Guide](PRINTING.md)** for recommended settings and materials.

### 2.1 Core Hardware (Required) 

| Part Name          | Type                    | Qty | Link | Comment                                                            |
| ------------------ | ----------------------- | --- | ---- | ------------------------------------------------------------------ |
| Cylindrical Screws | M4x10mm (ISO4762/DIN912) | 12  | [Aliexpress](https://s.click.aliexpress.com/e/_c4WUfT79)<br>[Amazon.de](https://amzn.to/49r8kCE) | Required for most of the assembly.                                 |
| Cylindrical Screws | M2x6mm (ISO4762/DIN912)  | 6   | [Aliexpress](https://s.click.aliexpress.com/e/_c4WUfT79)<br>[Amazon.de](https://amzn.to/4u4l5du) | Camera screws.                                                     |
| M4 Heat Inserts ⚠️   | 6.3mm OD (max 9mm long) | 12  | [Aliexpress](https://s.click.aliexpress.com/e/_c3iaYfkD)<br>[Amazon.de](https://amzn.to/4wZr2uZ) | 6mm OD also fits. <br><br>⚠️ **Only for the Heat Insert version.** |

> 💡 **Looking for more?** [View Recommendations for Electronics & Accessories](#8-recommended-electronics)

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
> Some cameras come with a 38x38mm mounting frame. To make them fit, you need to **break the outer frame** to downsize them to **32x32mm**.

*   Carefully break off the perforated edges using a pair of pliers.

![camera-resize](images/03_general/01_camera_resize.png)

### 3.2 Step 2: Heat Inserts Preparation
> **Self-Tapping Version:** If you printed this version, you can skip this step.

Melt the **M4 inserts** into the holes of the camera arms and heads using a soldering iron, as shown in the image below.

![heat_inserts](images/03_general/02_heat_inserts.png)

### 3.3 Step 3: Camera Installation & Closing
**1. Head & Arm Assembly**  
Connect the camera head and the arm using two **M4 screws**. After that, pull the USB cable through the internal channel of the housing and connect it to the 4-pin connector of the camera.

![arm_assembly](images/03_general/03_arm_assembly.png)

**2. Camera Installation**  
Secure the camera PCB with two **M2 screws**. 

> **Note:** These holes are self-tapping. Using only two screws is recommended and intentional.

**3. Lens Hood & Closing**  
Twist the lens hood clockwise into the camera cover (twist-lock) and then click the cover onto the head.
> **Tip:** Choose between the two different lens hood designs included in the print profile.

![lens_hood](images/03_general/04_lens_hood.png)

**Final Result of Phase 1**  
Upon completing these steps, you should have three fully assembled camera arms ready for installation.

[<img src="images/03_general/05_result_phase1.png" width="200" alt="fully assembled camera arms">](images/03_general/05_result_phase1.png)

---

## 4. Build Options: Choose Your Path

After your camera arms are prepared, choose the build guide that matches your setup.

### 4.1 Option 1: Winmau Plasma Light Ring

> **Pro Tip:** You have the option to route the Winmau Plasma power cable through the internal channels of the IT2 system for an even cleaner look. This requires a few extra steps - see [Section 7.2: Hiding Winmau Plasma Power Cable](#72-hiding-winmau-plasma-power-cable) for details.

**Step 1: Mounting the Arms**  
Attach the three [prepared camera arms](#3-general-assembly-camera-arms) to the designated positions on the Winmau Plasma ring. The IT2 arms are designed to fit perfectly onto the Plasma's profile. Use M4 screws to secure them.  

![plasma_mounting](images/04_options/01_plasma_mounting.png)

[Back to Table of Contents](#table-of-contents) | **Next Step: [5. Pre-Installation: Camera Positioning](#5-pre-installation-camera-positioning)**

---

### 4.2 Option 2: IT2 DIY Light Ring

**Step 1: Ring Assembly**  
Connect the 3D-printed segments of the IT2 DIY Light Ring. Ensure a tight connection to maintain stability.

![ring_dovetail](images/04_options/02_diy_ring_assembly.png)

**Step 2: LED Installation**  
Install the **LED strip** in the designated channel of the ring. Start from the bottom to allow for clean power cable routing.

![led_install](images/04_options/03_diy_led_install.png)

**Step 3: Attaching the Arms**  
Secure the camera arms to the integrated mounting points on the DIY ring using M4 screws.

![arm_mounting](images/04_options/04_diy_arm_mounting.png)

[Back to Table of Contents](#table-of-contents) | **Next Step: [5. Pre-Installation: Camera Positioning](#5-pre-installation-camera-positioning)**

---

### 4.3 Option 3: Target Corona Light Ring

**Step 1: Adapter Preparation**  
Install the **bottom part of the IT2 Corona Adapter** onto the three [prepared camera arms](#3-general-assembly-camera-arms) using M4 screws. 

![corona_adapter_prep](images/04_options/05_corona_adapter_prep.png)

**Step 2: Mounting & Alignment**  
Place the Target Corona ring into the recesses of the installed bottom adapter parts. 

![corona_ring_mounting](images/04_options/06_corona_ring_mounting.png)

Then, hook the **upper part of the adapter** into the ring and snap it into place. 

![corona_adapter_hook](images/04_options/07_corona_adapter_hook.png)

> **Tip:** Try to position the adapters at an approximate **120-degree offset** while snapping them on. This will minimize the amount of fine-tuning needed later.

![corona_alignment](images/04_options/08_corona_alignment.png)

> **Pro Tip:** You have the option to route the Target Corona power cable through the internal channels of the IT2 system for an even cleaner look. This requires a few extra steps - see [Section 7.3: Hiding Target Corona Power Cable](#73-hiding-target-corona-power-cable) for details.

[Back to Table of Contents](#table-of-contents) | **Next Step: [5. Pre-Installation: Camera Positioning](#5-pre-installation-camera-positioning)**

---

### 4.4 Option 4: IT2 DIY Low Ceiling Light Ring

> This version was specifically developed for rooms with low ceiling height. It requires a ceiling height of at least **2.00m**.

**Assembly Instructions**  
The assembly logic for this version is identical to the standard DIY ring. Please follow the detailed **[step-by-step instructions in Section 4.2](#42-option-2-it2-diy-light-ring)**.

> 💡 **Tip:** Unlike the standard ring, the Low Ceiling version consists of **6 different segment types**. Please note that all three segments that mount to the cameras are different from the standard version - two of them are mirrored and shorter to accommodate the ceiling clearance. Before connecting the dovetails, lay out all pieces on the floor in the correct order to avoid sequence errors. Once connected, the pieces are often very difficult to pull apart without risking damage.

**Final Result**  
After assembly, your Low Ceiling Light Ring should look as follows:

![low_ceiling_assembly](images/04_options/09_low_ceiling_assembly.png)

[Back to Table of Contents](#table-of-contents) | **Next Step: [5. Pre-Installation: Camera Positioning](#5-pre-installation-camera-positioning)**

---

## 5. Pre-Installation: Camera Positioning

Before mounting your system, you need to decide on the orientation of your camera arms. 

> **Camera Positioning**  
> Align camera arms with the **11** or **6** segments for optimal recognition ([Autodarts Guidelines](https://autodarts.diy/getting-started/camera-positioning/)).  
> **Note:** The **Low Ceiling** or **portable stand** version uses the **3** segment instead.

![camera_positions](images/01_overview/camera_positions.png)

---

## 6. Final Step: Installation & Wall Mounting

The IT2 system offers two main installation paths, depending on your requirements for aesthetics, mounting effort, and wall protection.

### Option A: Direct Mounting
In this configuration, the IT2 system is mounted directly to the wall. This requires drilling **6 holes** for the arms and **2 additional holes** for the dartboard hanger (if not already present).
*   **Pros:** Fewer parts to assemble; minimal footprint; system sits flush against the wall.
*   **Cons:** Requires more drill points; leg positions must be determined manually via measurements, drawing circles, or using a drill template.

### Option B: IT2 Baseplate
The **[IT2 Baseplate](BASEPLATE.md)** is an optional unit that simplifies the installation process and offers additional features like sound dampening and native stand compatibility.

For detailed instructions on how to install and align the baseplate, please refer to the **[Baseplate Assembly & Installation Guide](BASEPLATE.md)**.

---

### 6.1 Mounting Instructions: Direct Wall Mounting (Option A)
There are two ways to ensure your system is perfectly aligned when mounting directly to the wall:

#### Method 1: Using the IT2 Drill Template (Recommended)
This is the easiest and most precise way to position your mounting holes.
1. Align the center of the template with your marked bullseye height (1.73m).
2. Level the template.
3. Mark the drill positions through the designated points on the template.
    > 💡 **Tip:** To minimize drilling while maintaining perfect stability, I recommend using only **two diagonal holes** per arm (e.g., top-left and bottom-right) instead of all four.

> 💡 **Tip:** If you want to change the orientation of the camera arms (e.g., placing the main arm on the left instead of the right), simply flip the template upside down. You can then use a spirit level on the bottom edge to align it perfectly.

![drill_template](images/01_overview/drill_template.png)

#### Method 2: Manual Marking & Drawing
If you prefer to mark the positions yourself without the 3D-printed template, follow the measurements shown in the technical drawing below. This ensures the correct 120-degree offset and distance from the bullseye.

![manual_marking](images/01_overview/manual_marking.png)

---

### 6.2 Mounting Instructions: Baseplate Mounting (Option B)
Please refer to the **[IT2 Baseplate Manual](BASEPLATE.md)** for detailed, step-by-step instructions on wall mounting and alignment.

[Back to Table of Contents](#table-of-contents)

---

## 7. Pro Tips & Troubleshooting

To ensure the best possible experience with your IT2 system, follow these pro tips.

### 7.1 Assembly Best Practices
When tightening screws, ensure they are only **"finger-tight"**.
*   Avoid over-tightening as this can stress the heat inserts.
*   **Self-Tapping Version:** Be extra careful with the self-tapping version. The plastic threads can easily strip, which is **irreversible** if too much force is applied.

### 7.2 Hiding Winmau Plasma Power Cable
**Step 1:** ...
**Step 2:** ...
*(Instructions coming soon)*

### 7.3 Hiding Target Corona Power Cable
**Step 1:** ...
**Step 2:** ...
*(Instructions coming soon)*

[Back to Table of Contents](#table-of-contents)

---

## 8. Recommended Electronics

| Part Name    | Type                                   | Link | Comment                                       |
| ------------ | -------------------------------------- | ---- | --------------------------------------------- |
| Cameras      | HBV OV2710                             | [Aliexpress](https://s.click.aliexpress.com/e/_c4bziy33) | Best price-to-performance cameras.            |
| LED Strip    | Auxmer 12V 9.6W LED Strip              | [Aliexpress](https://s.click.aliexpress.com/e/_c3z7FC4l) | My favorite. Best color reproduction.         |
| Power Supply | 12V 3A Power Adapter                   | [Aliexpress](https://s.click.aliexpress.com/e/_c2IYxq1R) | Required for the DIY LED strip.               |
| DC Connector | 2.1mm DC Socket                        | [Aliexpress](https://s.click.aliexpress.com/e/_c3L2uy4H) | To connect the power supply to the LEDs.      |
| PC           | Dell Wyse 5070 ≥4GB RAM ≥ 16GB Storage |      | My favorite. Good price-to-performance ratio. |
| Touchscreen  | Anmite 16" Touchscreen                 | [Aliexpress](https://s.click.aliexpress.com/e/_c34qKHYZ) | My favorite. Good price-to-performance ratio. |

---

## 9. FAQ

### Q: Which cameras should I choose?
**A:** The clear winner for price-to-performance is the **HBV OV2710**. Investing in more expensive, higher-resolution cameras is unnecessary as Autodarts is resolution-limited. While the **OV9732** is a cheaper alternative, it requires significantly better lighting; therefore, I exclusively recommend the OV2710 for its superior handling of various light conditions.

### Q: Which LED strip should I get?
**A:** Avoid USB light strips. The community standard is **6000K COB LEDs** (12V or 24V). My personal recommendation is the **Auxmer 120 LEDs/m (9.6W, CRI90)**; in my tests, it even outperformed the Winmau Plasma. If you're on a budget, any 6000K strip with around 10W per meter will work, provided it's bright enough.

### Q: Should I use a Raspberry Pi or a Mini PC?
**A:** Unless you already own a Raspberry Pi, I recommend buying a refurbished Mini PC. They are often cheaper (starting at €50) and offer better performance and touchscreen support. My personal favorite is the **Dell Wyse 5070** (4GB RAM, 16GB storage), which is widely available refurbished and handles the Autodarts software perfectly.

---

## 10. Licensing & Community Support
IT2 is provided under a custom license. For information regarding commercial use, private sharing, and community support, please refer to the **[LICENSE.md](LICENSE.md)** file.
