# Seasonal-forecasts
Seasonal montly forecasts for cities

**Goal:** To provide monthly probabilistic forecasts for the next six months, allowing cities to anticipate deviations from average weather conditions and adjust medium-term planning.

---

### 🛠 Technical Overview
* **Provided by:** Ficlima & Municipia.
* **Methodology:** Raw models optimized through **Machine Learning (AI)** methods using local observed data.
* **Delivery:** Results supplied to URBREATH project tools via **WMS**.
* **Update Frequency:** 🔄 **Monthly.** Information is updated and delivered every month.

---

### 📊 Data & Variables: Anomalies
The system displays how the expected weather differs from the historical average (climatology).

| Category | Variables Included |
| :--- | :--- |
| **Basic Anomalies** | Monthly Average Temperature (Absolute ºC), Monthly Average Precipitation (Relative %), and Monthly Average Wind (Relative %). |
| **Tailored Variables** | Indicators co-defined with cities (taking into account SOTA limitations), list to be presented at the Pilsen event. |

---

### 🔍 How to Interpret the Data
Users should interpret these anomalies as deviations from "normal" weather to make strategic operational decisions.
* **Relative Anomalies (%):** Used for precipitation and mean wind.
* **Absolute Anomalies (ºC):** Used for average temperature.

---

### 💡 Practical Example: Operational Planning
> **Case Study (Cluj-Napoca):** Garden pruning is usually planned for October. However, if monthly updates consistently forecast significant **cold anomalies** for that month, the city can adjust the pruning calendar to avoid potential frost damage to the vegetation.

---

### 🔗 Explore the Tool
You can access the seasonal visualization system here:
👉 [Ficlima Seasonal Tool](https://urbreath.virtualcitymap.de/ficlima/)

---

### 🔗 Synergies with other scales
Seasonal forecasts bridge the gap between long-term strategic projections and daily operations. By adapting long-term "flags" to this scale, cities can verify if current seasonal trends align with expected climate scenarios.
