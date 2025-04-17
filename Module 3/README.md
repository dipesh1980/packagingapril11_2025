# ❄️ Thermal Simulation of a Flipchip BGA Package in Ansys Icepak

This repository provides a step-by-step guide to simulate the thermal behavior of a Flipchip BGA package using **ANSYS Icepak**, for a power input of **1 W**.

---

## 🧊 Lab Overview

> **Goal**: Create a detailed 3D Flipchip BGA model and simulate its thermal profile.  
> **Tool**: ANSYS Icepak via Workbench  
> **Power Input**: 1 Watt  

---

## 🚀 Step-by-Step Simulation Flow

<details>
  <summary>🛠️ Step 1: Insert Icepak Design</summary>

- Open **Ansys Workbench**  
- Go to: `Project` → `Insert Icepak Design`
</details>

<details>
  <summary>🧭 Step 2: Launch the Icepak Layout</summary>

- Click the **Icepak** tab from the top toolbar  
- The layout environment will open
</details>

<details>
  <summary>📦 Step 3: Create Flipchip BGA Package</summary>

Navigate to: `Icepak` → `Toolkit` → `Geometry` → `Packages` → `Flipchip_BGA`  
Configure:


✅ Click **OK** to generate the model
</details>

<details>
  <summary>📂 Step 4: Explore the Model</summary>

In the **Model Tree**, expand the **Solids** to see:

- Substrate  
- Die  
- Underfill  
...and more
</details>

<details>
  <summary>♨️ Step 5: Assign Thermal Power</summary>

- Navigate to: `Project Manager` → `Thermal`  
- Set `Power = 1 W` → Click **OK**
</details>

<details>
  <summary>🌡️ Step 6: Assign Thermal Sources</summary>

- Select: `Flipchip-BGA1_substrate`  
- Right-click → `Assign Thermal` → `Source`  
- Set: `Thermal Condition = Ambient Temperature`  
- Click **OK**  
- Delete any extra thermal items (e.g., `Flipchip_BGA_trace1`)
</details>

<details>
  <summary>📈 Step 7: Add Temperature Monitors</summary>

Assign **Temperature Monitors** to:

- Substrate  
- Die  
- Underfill  

→ Use: `Assign Monitor` → `Point` → Select **Temperature** → **OK**
</details>

<details>
  <summary>🧩 Step 8: Generate the Mesh</summary>

- Navigate to the **Mesh** tab  
- `Simulation` → `Generate Mesh` → **Save** → Click **OK**
</details>

<details>
  <summary>🔍 Step 9: Inspect Mesh Quality</summary>

- In `Mesh Visualization`, click **Quality**  
- Check:
  - Face Alignment  
  - Skewness  
  - Volume
</details>

<details>
  <summary>✅ Step 10: Validate Setup</summary>

Click `Validate` from the top bar  
✅ Ensure all validation checks pass (green ticks)
</details>

<details>
  <summary>📊 Step 11: Run Simulation & Plot Results</summary>

- Click `Analyze All`  
- Select the Flipchip BGA model  
- Go to: `Plot Field` → Select `Temperature`  
- Enable:
  - **Specify Name**
  - **Specify Folder**
  - **Plot on Surface Only**
- Enable **Gaussian Smoothing**  
- Click **OK** → then **Done**
</details>

---

## ✅ Final Output

✔️ You now have a complete **thermal simulation** of the Flipchip BGA package for **1 W** power dissipation.  
🔍 Use surface plots and monitors to analyze heat distribution and identify thermal hotspots.

---

## 📸 Screenshots

> *(Include screenshots of each step in this section if available, or link to a `/screenshots/` folder)*
<table>
  <tr>
    <td><img src="../images/Picture1.png" width="250"/></td>
    <td><img src="../images/Picture2.png" width="250"/></td>
    <td><img src="../images/module3/Screenshot 2025-04-04 220840 - Copy.png" width="250"/></td>
  </tr>
  <tr>
    <td><img src="../images/module3/Screenshot 2025-04-04 220840.png" width="250"/></td>
    <td><img src="../images/module3/Screenshot 2025-04-04 221220 - Copy.png" width="250"/></td>
    <td><img src="../images/module3/Screenshot 2025-04-04 221220.png" width="250"/></td>
  </tr>
  <tr>
    <td><img src="../images/module3/Screenshot 2025-04-04 221657 - Copy.png" width="250"/></td>
    <td><img src="../images/module3/Screenshot 2025-04-04 221657.png" width="250"/></td>
    <td><img src="../images/module3/Screenshot 2025-04-04 221825 - Copy.png" width="250"/></td>
  </tr>
  <tr>
    <td><img src="../images/module3/Screenshot 2025-04-04 221825.png" width="250"/></td>
    <td><img src="../images/module3/Screenshot 2025-04-04 222041 - Copy.png" width="250"/></td>
    <td><img src="../images/module3/Screenshot 2025-04-04 222041.png" width="250"/></td>
  </tr>
  <tr>
    <td><img src="../images/module3/Screenshot 2025-04-04 222103 - Copy.png" width="250"/></td>
    <td><img src="../images/module3/Screenshot 2025-04-04 222103.png" width="250"/></td>
    <td><img src="../images/module3/Screenshot 2025-04-04 222453 - Copy.png" width="250"/></td>
  </tr>
  <tr>
    <td><img src="../images/module3/Screenshot 2025-04-04 222453.png" width="250"/></td>
    <td><img src="../images/module3/Screenshot 2025-04-04 222516.png" width="250"/></td>
    <td><img src="../images/module3/Screenshot 2025-04-04 222746.png" width="250"/></td>
  </tr>
  <tr>
    <td><img src="../images/module3/Screenshot 2025-04-04 222453.png" width="250"/></td>
    <td><img src="../images/module3/Screenshot 2025-04-04 223108.png" width="250"/></td>
    <td><img src="../images/module3/Screenshot 2025-04-04 223300.png" width="250"/></td>
  </tr>
  <tr>
    <td><img src="../images/module3/Screenshot 2025-04-04 223415 - Copy.png" width="250"/></td>
    <td><img src="../images/module3/Screenshot 2025-04-04 223415.png" width="250"/></td>
    <td><img src="../images/module3/Screenshot 2025-04-04 223843.png" width="250"/></td>
  </tr>
  <tr>
    <td><img src="../images/module3/Screenshot 2025-04-04 223904.png" width="250"/></td>
    <td><img src="../images/module3/Screenshot 2025-04-04 224148.png" width="250"/></td>
    <td><img src="../images/module3/Screenshot 2025-04-04 224249.png" width="250"/></td>
  </tr>
  <tr>
    <td><img src="../images/module3/Screenshot 2025-04-04 224409.png" width="250"/></td>
    <td><img src="../images/module3/Screenshot 2025-04-04 224954.png" width="250"/></td>
    <td><img src="../images/module3/Screenshot 2025-04-04 225019.png" width="250"/></td>
  </tr>
  <tr>
    <td><img src="../images/module3/Screenshot 2025-04-04 225048.png" width="250"/></td>
    <td><img src="../images/module3/Screenshot 2025-04-04 225112.png" width="250"/></td>
    <td><img src="../images/module3/Screenshot 2025-04-04 225310.png" width="250"/></td>
  </tr>
  <tr>
    <td><img src="../images/module3/Screenshot 2025-04-04 225336.png" width="250"/></td>
    <td><img src="../images/module3/Screenshot 2025-04-04 225509.png" width="250"/></td>
    <td><img src="../images/module3/Screenshot 2025-04-04 225808.png" width="250"/></td>
  </tr>
  <tr>
    <td><img src="../images/module3/Screenshot 2025-04-04 225839.png" width="250"/></td>
    <td><img src="../images/module3/Screenshot 2025-04-04 230328.png" width="250"/></td>
    <td><img src="../images/module3/Screenshot 2025-04-04 235038.png" width="250"/></td>
  </tr>
  <tr>
    <td><img src="../images/module3/Screenshot 2025-04-04 235105.png" width="250"/></td>
    <td><img src="../images/module3/Screenshot 2025-04-04 235203.png" width="250"/></td>
    
  </tr>

</table>
---
