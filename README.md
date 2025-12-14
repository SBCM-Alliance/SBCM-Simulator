# 🏙️ SBCM Simulator
**The Administrative Hydraulics Engine.**

[![Status](https://img.shields.io/badge/Status-Operational-success)]()
[![Engine](https://img.shields.io/badge/Core-PyScript_WASM-blue)](https://pyscript.net)
[![Theory](https://img.shields.io/badge/Theory-SBCM_Tetralogy-purple)](https://doi.org/10.5281/zenodo.17762960)
[![License](https://img.shields.io/badge/License-MIT-yellow)](LICENSE)

> **"A city is not a static stock of concrete. It is a dynamic fluid field of wealth."**
>
> In a depopulating society, infrastructure maintenance costs grow exponentially while the tax base shrinks linearly. This tool mathematically proves the inevitable ruin of municipalities and demonstrates the **"Optimization Solution (G-Cart)"** based on Field Theory.

---

## 📱 Live Demo

**👉 [Launch Simulator](https://sbcm-alliance.github.io/SBCM-Global-Scanner/)**
*(Runs entirely in your browser via WebAssembly)*

| **The Ruin (Current Trajectory)** | **The Solution (G-Cart Optimization)** |
| :---: | :---: |
| <img src="docs/demo_ruin.png" width="400" alt="Red City"> | <img src="docs/demo_gold.png" width="400" alt="Gold City"> |
| *Without flow control, wealth leaks out ($R_{block} \approx 10\%$), leading to fiscal collapse.* | *With mesh refinement, wealth circulates ($R_{block} \approx 95\%$), creating sustainability.* |

---

## 📐 The Logic: SBCM Tetralogy

This simulator implements the full stack of the **Standard Block Comparison Method (SBCM)** theory.

### 1. Static Audit (Part 1)
We normalize all municipal data using the **Standard Block ($B_{std} \approx 72,176$ people)**.
*   **$S$ (Scale Factor):** Relative size of the municipality.
*   **$D_{index}$ (Distortion Index):** Quantifies how "distorted" the budget is compared to the population scale.
    $$ D_{index} = \frac{Budget \div S}{Standard\_Cost} $$

### 2. Meso-Economics (Part 2)
We calculate the **Real Economic Value** retained within the region.
*   **$R_{block}$ (Retention Rate):** The percentage of budget that stays in the local economy.
*   **The Straw Effect:** If a project is too large for local capacity, wealth flows out to the metropolis.

### 3. Dynamic Thermodynamics (Part 3)
We simulate the **Time Evolution** of the city.
*   **Population:** Decays exponentially ($P(t) = P_0 e^{-\lambda t}$).
*   **Entropy:** Infrastructure costs increase due to aging ($C(t)$).
*   **Result:** The intersection point is the "Fiscal Death Date."

### 4. Field Theory (Part 4)
We apply **Administrative Hydraulics** to control the flow.
*   **G-Cart Protocol:** A mechanism that meshes large budget vectors into smaller local capacities.
*   **Effect:** Turning this ON maximizes $R_{block}$ (Retention) and prevents divergence (Leakage).

---

## 🛠️ Tech Stack

This project runs **serverless**. All complex thermodynamic calculations are performed client-side using Python compiled to WASM.

*   **Frontend:** HTML5 / CSS3 (Cyberpunk UI)
*   **Map Engine:** [MapLibre GL JS](https://maplibre.org/) + OpenFreeMap Vector Tiles
*   **Computation:** [PyScript](https://pyscript.net/) (Python running in the browser)
*   **Logic:** SBCM Core Library (Proprietary Algorithm)

---

## 🚀 Usage

### Run Locally
Since this uses PyScript and WASM, you need a local web server to avoid CORS issues.

```bash
# 1. Clone the repository
git clone https://github.com/SBCM-Alliance/SBCM-Simulator.git

# 2. Navigate to the directory
cd SBCM-Simulator

# 3. Start a simple Python server
python3 -m http.server 8000

# 4. Access in browser
# http://localhost:8000
```

### How to Simulate
1.  **Set Parameters:** Input the population and annual budget.
2.  **Check Distortion:** See if the $D_{index}$ is Green (Safe) or Red (Critical).
3.  **Run Time-Lapse:** Press `RUN` to watch the population decline and costs rise over 50 years.
4.  **Activate G-Cart:** Toggle the **G-Cart Switch** to see how vector decomposition saves the city from ruin.

---

## 📚 References

*   **SBCM Methodology:** [10.5281/zenodo.17762960](https://doi.org/10.5281/zenodo.17762960)
*   **Meso-Economic Framework:** [10.5281/zenodo.17766604](https://doi.org/10.5281/zenodo.17766604)
*   **Dynamic Thermodynamics:** [10.5281/zenodo.17777745](https://doi.org/10.5281/zenodo.17777745)
*   **Field Theory:** [10.5281/zenodo.17890326](https://doi.org/10.5281/zenodo.17890326)

---

<p align="center">
  <small>© 2025 SBCM Alliance. Powered by <b>Algorithmic Public Interestism</b>.</small>
</p>
