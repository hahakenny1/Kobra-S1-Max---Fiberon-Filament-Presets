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
