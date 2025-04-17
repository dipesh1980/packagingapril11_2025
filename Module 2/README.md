# 🧠 End-to-End Semiconductor Assembly Pipeline

A seamless transformation from bare silicon to a packaged IC requires coordinated stages, each demanding precision equipment and stringent environmental control.

## 📌 Pipeline Overview

<details>
  <summary>Design Verification & Tape-Out</summary>

**Inputs**: EDA tool streams, Process Design Kits (PDKs)  
**Deliverables**: GDSII layout, validation scripts
</details>

<details>
  <summary>Wafer Fabrication</summary>

**Inputs**: Prime-grade Si wafers, photolithography tools, process chemistries  
**Deliverables**: Patterned wafers housing thousands of dies
</details>

<details>
  <summary>ATMP (Assembly, Test, Mark & Package)</summary>

**Inputs**: Substrates, bonding materials, encapsulants  
**Processes**: Dicing, die-attach, wire/flip-chip bonding, encapsulation, electrical test
</details>

<details>
  <summary>PCB-Level Assembly & Validation</summary>

**Inputs**: Populated PCBs, reflow ovens, inspection stations  
**Outputs**: Verified system boards
</details>

<details>
  <summary>Final System Integration</summary>

**Inputs**: Board-level assemblies, mechanical enclosures  
**Outputs**: Turnkey electronic products (e.g., smartphones, servers)
</details>

---

## 🏭 Anatomy of an ATMP Facility

Outsourced Semiconductor Assembly & Test (OSAT) hubs—or in-house ATMP wings at IDM fabs—are structured into specialized zones:

- **Material Preparation**: Staging of substrates, adhesives, molding compounds  
- **Cleanroom Assembly (ISO 6/7)**:
  - Die-Bond: Epoxy dispensing, pick-and-place
  - Cure: Solidify epoxy with thermal profiles
  - Wire Bond: Ball/wedge bonding, loop shaping
  - Encapsulation & Marking: Transfer-molding, laser engraving
  - Singulation: High-speed sawing
  - Electrical Test & Burn-In: Parametric tests, thermal stress
  - Packaging & Dispatch: Tape-and-reel, trays, labeling

> 🏗️ *Example: Micron’s Sanand facility spans 500,000 sq.ft. of Class 1000/10000 cleanroom.*

---

## 🌀 Wafer Pre-Processing

<details>
  <summary>Steps Overview</summary>

- **Carrier Unloading & EPI Inspection**  
- **Front-Side Protective Tape Lamination**  
- **Backside Thinning via Grinding**  
- **Frame Mounting**  
- **Laser Scribe & Blade Dicing**
</details>

---

## 🔩 Wire-Bond Packaging Workflow

<details>
  <summary>1. Die Attach & Cure</summary>

- **Epoxy Jet Dispense**: Sub-10 nL droplets  
- **Pick-&-Place**: ±2 µm precision  
- **Thermal Cure**: 150 °C for 90 s
</details>

<details>
  <summary>2. Wire Bonding</summary>

- **Ball Formation**: EFO spark  
- **Bonding Sequence**: Ball-to-pad, stitch bond  
- **Loop Control**: Shape and height optimized
</details>

<details>
  <summary>3. Transfer Molding & Marking</summary>

- **Molding Press**: 300 bar @ 175 °C  
- **Laser Ablation**: 355 nm UV laser
</details>

<details>
  <summary>4. Singulation & Debris Control</summary>

- **Precision Sawing**: <30 µm kerf  
- **Ionized Air Curtains**: Debris removal
</details>

---

## 🔃 Flip-Chip Assembly Steps

<details>
  <summary>1. Bump Formation</summary>

- Electroplating SnAgCu (~80 µm)
</details>

<details>
  <summary>2. Flip & Align</summary>

- Sub-1 µm vision-guided placement
</details>

<details>
  <summary>3. Reflow Soldering</summary>

- Nitrogen peak: 245 °C
</details>

<details>
  <summary>4. Underfill & Cure</summary>

- Capillary infiltration, cure @ 125 °C
</details>

<details>
  <summary>5. Molding, Marking, Ball Mount</summary>

- Glob-top, laser coding  
- BGA attach and inert-atmosphere reflow
</details>

---

## 🌐 Wafer-Level Packaging (WLP) & RDL

<details>
  <summary>1. Reconstitution & Mold</summary>

- Die sorting onto carrier wafers  
- Epoxy encapsulation to reconstitute wafer
</details>

<details>
  <summary>2. RDL Build-Up</summary>

- Spin-coating PI/BCB  
- Cu sputter & lithography  
- Up to 5 routing layers
</details>

<details>
  <summary>3. Ball Array Creation</summary>

- Cu pillars, SAC305 caps  
- Reflow for adhesion
</details>

<details>
  <summary>4. Singulation & Inspection</summary>

- Laser/blade dicing  
- AOI & X-ray analysis
</details>

---

