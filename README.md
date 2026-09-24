# Polymaker-Fibreron-CF-Filament--Anycubic Kobra-S1-Max--Presets
My custom filament configurations for Polymaker Fiberon Filaments for the Anycubic Kobra S1 Max

-----------------------------------------------------------------------------------------------------------------
A. How to Install
These profiles are designed for Anycubic Slicer Next (based on OrcaSlicer).

1. Launch Anycubic Slicer Next.

2. Go to File > Import > Import Configs...

3. Select the included .anycubic_filament file(s).

4. The profiles will now appear in your Filament dropdown list (likely under "User" or "Custom").

Note: Ensure your printer nozzle size matches the profile (0.4mm Hardened Steel is recommended for abrasive filaments like CF/GF).

-----------------------------------------------------------------------------------------------------------------
B. Material Processing Guide

--------------------
Polymaker Fiberon PA6-CF 20 (Carbon Fiber Nylon)
A high-strength, heat-resistant engineering material. Requires strict moisture control.

🔥 Drying Instructions (CRITICAL)
This material absorbs moisture from the air in minutes. It MUST be dried before every print.

Drying Temp: 100°C (212°F)

Time: 8–10 Hours

Storage: Must be printed from a sealed dry box (like the ACE Pro) with active desiccant/heating if possible.

♨️ Annealing Instructions (Optional)
Annealing increases thermal resistance and mechanical strength but causes slight shrinkage.

Method: External convection oven (Do not use printer chamber).

Temp: 100°C (212°F)

Time: 16 Hours

Cool Down: Turn oven off and let cool slowly to room temp (do not open door).

💧 Moisture Conditioning (Post-Annealing)
Annealing makes the part brittle. You must re-introduce moisture to restore toughness.

Option 1 (Fast): Submerge part in 60°C (140°F) water for 48 hours.

Option 2 (Passive): Leave part in ambient air for 5–7 days.

-------------------
Polymaker Fiberon PA612-CF15
Carbon Fiber Reinforced Nylon 6/12. Lower moisture sensitivity than PA6 and easier to print, but slightly lower max heat resistance (175°C HDT).

🔥 Drying Instructions
Drying Temp: 100°C (212°F)

Time: 8–10 Hours (or PolyDryer Level 3 for 18h)

Note: While less sensitive than PA6, "popping" noises during printing indicate it is wet.

♨️ Annealing (Recommended)
Annealing pushes the heat deflection temp from ~114°C to ~175°C.

Temp: 100°C (212°F)

Time: 16 Hours

Note: Older documentation may suggest 80°C for 6 hours, but 100°C/16h is the current standard for maximum performance.

💧 Moisture Conditioning
Required: Yes, after annealing.

Method: Same as PA6-CF (Water soak or air exposure).

----------------------------------------------------------------------------
General Print Tips for Kobra S1 Max

1. Bed Temp: Keep the bed LOW (40–50°C). Do not exceed 50°C. These materials use "Warp-Free" technology that relies on a cooler bed and chamber.

2. Adhesion: Use a thin layer of PVA glue (glue stick) on the Textured PEI plate.

3. Chamber Fans: Keep exhaust fans low (10–15%) to maintain a stable, warm (but not hot) environment.

4. Cooling: Part cooling fans should generally be OFF to prevent layer splitting.
Nozzle: exclusively use Hardened Steel nozzles; brass will wear out in <500g of printing.



------------------------------------------------------------------------------
Added Inslogic PA6-CF for Kobra S1 Max
# Inslogic PA6-CF Print Profile & Guidelines

**Material:** Carbon Fiber Reinforced Nylon 6 (20% CF).
**Properties:** Offers extreme stiffness, high tensile strength, and exceptional heat resistance (up to 209°C HDT).
**Warning:** Highly hygroscopic—requires thorough drying before printing.

---

## 🔥 Drying Instructions

* **Drying Temp & Time:** 90°C (194°F) for 12 Hours, or 110°C (230°F) for 4 Hours.
* **Workflow Note:** The Anycubic Ace 2 Pro caps at 65°C, which cannot perform the initial deep dry. Dehydrate the spool in a dedicated oven or high-temp dryer first, then feed from the Ace 2 Pro to maintain dryness while printing.

## ♨️ Annealing (Recommended)

Annealing completes crystallization to unlock the full 209°C heat resistance and relieve internal print stress.
* **Option 1:** 90°C (194°F) for 12 Hours
* **Option 2:** 110°C (230°F) for 6 Hours
* **Option 3:** 130°C (266°F) for 3 Hours
* **Cooling Note:** Let the part cool down slowly inside the oven to room temperature to prevent warping from thermal shock.

## 💧 Moisture Conditioning

* **Required:** Yes, after annealing.
* **Method:** Allow the annealed part to sit in ambient room humidity for several days, or place it in a warm water bath for several hours to restore flexibility and impact resistance to the nylon matrix.

---

## ⚙️ General Print Tips for Kobra S1 Max

1. **Bed Temp:** Set bed temperature to **50–70°C** (65°C recommended) on the Textured PEI Plate.
2. **Adhesion:** Apply a thin, even coat of PVA glue stick or Magigoo PA to the textured PEI sheet to ensure adhesion and act as a release layer when cool.
3. **Chamber & Enclosure:** Set chamber temperature to **60–65°C** with the internal filtration fan low (5–10%) to prevent rapid cooling and corner lifting.
4. **Cooling:** Run part cooling at **30%** (with 0% on the first 3 layers). Keep the auxiliary fan OFF (0%).
5. **Nozzle:** Exclusively use a **Hardened Steel nozzle** (0.4 mm or 0.6 mm) printed at **270–290°C**; brass will wear out in less than a single spool.
6. **Retraction Overrides:** Use 0.8 mm retraction length, 45 mm/s speed, 2.0 mm wipe distance, and 0.4 mm Z-hop to eliminate stringing and nozzle strikes.
