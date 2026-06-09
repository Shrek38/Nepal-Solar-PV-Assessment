# Nepal Solar PV Potential Assessment

Replication of **Bhatta et al. (2025)** — *Harnessing Solar PV Potential for
Decarbonization in Nepal: A GIS-Based Assessment of Ground-Mounted, Rooftop,
and Agrivoltaic Solar Systems.*

Published in: *Energy for Sustainable Development*, 85, 101618.
DOI: [10.1016/j.esd.2024.101618](https://doi.org/10.1016/j.esd.2024.101618)

---

## Project Summary

This project replicates the spatial and techno-economic analysis of Nepal's
solar PV potential using:
- **Google Earth Engine (GEE)** for geospatial processing
- **Python** for numerical modelling and figure reproduction

### Key Results

| System Type         | Generation Potential | LCOE ($/MWh) |
|---------------------|----------------------|--------------|
| Ground-mounted PV   | 159 TWh/year         | $56.3        |
| Rooftop PV          | 32–64 TWh/year       | $66.8        |
| Agrivoltaic (20%)   | 329 TWh/year         | $73.2        |

Total potential: **up to 552 TWh/year** (~45× Nepal's current generation)

---

## Repository Contents

| File | Description |
|------|-------------|
| `HRO-102_Group-18.ipynb` | Main Jupyter notebook — GIS analysis, LCOE computation, figures |
| `HRO-102_Report.pdf` | Full written report (HRO-102, Group 18) |

---

## How to Run

1. Clone this repository:
```bash
   git clone https://github.com/Shrek38/Nepal-Solar-PV-Assessment.git
   cd Nepal-Solar-PV-Assessment
```

2. Install dependencies:
```bash
   pip install earthengine-api numpy pandas matplotlib pillow requests
```

3. Authenticate Google Earth Engine (first time only):
```bash
   earthengine authenticate
```

4. Open the notebook:
```bash
   jupyter notebook HRO-102_Group-18.ipynb
```

---

## Authors

**Group 18 — HRO-102**
- Mehak Chawla (24125029)
- Ved Arya (24125038)
- Nitin Nigam (23125024)
- Pruthviraj (23125027)

Institution: IIT Roorkee

---

## Reference

Bhatta, G., Lohani, S.P., KC, M., Bhandari, R., Palit, D., & Anderson, T. (2025).
Harnessing solar PV potential for decarbonization in Nepal.
*Energy for Sustainable Development*, 85, 101618.
