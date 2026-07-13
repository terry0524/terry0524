<div align="center">

# Jongseok Park

### Mechanical Engineering × AI/Data × Physical Systems

I connect experiments, simulation, sensor data, and machine learning to analyze and improve physical systems.

[![Portfolio](https://img.shields.io/badge/Portfolio-0B1F33?style=for-the-badge&logo=googlechrome&logoColor=white)](https://mech-insight-portfolio.lovable.app)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-1D4ED8?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/terry0524)
[![Email](https://img.shields.io/badge/Email-4F46E5?style=for-the-badge&logo=gmail&logoColor=white)](mailto:terry0524@soongsil.ac.kr)
[![GitHub](https://img.shields.io/badge/GitHub-6D28D9?style=for-the-badge&logo=github&logoColor=white)](https://github.com/terry0524)

</div>

---

## About Me

I am a mechanical engineering student at Soongsil University working across physical AI, thermal systems, sensor-based measurement, and time-series modeling. My work links engineering theory with experiments, simulation, data processing, and deployable implementations.

I focus on determining whether a model remains useful outside ideal conditions: under thermal disturbances, measurement uncertainty, changing operating states, and deployment constraints. This supports work in physical AI, engineering analysis, equipment validation, predictive modeling, and research.

## Core Engineering Areas

| Area | Experience | Tools / Methods |
|---|---|---|
| Thermal & Fluid Systems | Thermal response, heat transfer, fluid behavior, and equipment-level physical interpretation | ANSYS, transient thermal analysis, contact thermal resistance, heat flux analysis |
| Experimental Analysis | Sensor-data collection, controlled disturbances, hot-plate testing, and theory-to-measurement comparison | Experimental design, sensor data processing, visualization, root-cause analysis |
| AI / Machine Learning | Regression and supervised learning for physical-system estimation and prediction | Python, Scikit-learn, XGBoost, Edge Impulse, LSTM, BiGRU |
| Time-Series Forecasting | Building-energy and wind-power forecasting from sequential operational and environmental data | Feature engineering, NWP data, SCADA-related correction, recurrent models |
| Edge AI / Embedded Deployment | Moving estimation logic from trained models into constrained device-side pipelines | C, C++, Arduino C, CMake, Wio Terminal, Edge Impulse |
| Engineering Validation | Metric-based comparison, disturbance testing, error analysis, and implementation checks | MAE, RMSE, peak error, validation protocols, competition-rule compliance |

## Featured Projects

<details open>
<summary><strong>1. Robust Core Body Temperature Estimation under Thermal Disturbances</strong></summary>

- **Problem:** Estimate core body temperature from sensor data while remaining reliable during external thermal disturbances.
- **My Contribution:** Built disturbance detection and post-processing around an Edge Impulse regression model, evaluated raw versus processed outputs, and developed C++ and pure C deployment paths with Choice Technology.
- **Result:** Disturbance peak error decreased from **1.36°C to 0.90°C**. Average MAE changed from approximately **0.178°C to 0.192°C**, so the method improved peak robustness—not average error. A separate integrated evaluation produced MAE of approximately **0.143°C**.
- **Methods:** Sensor processing · Edge Impulse · C/C++ · hot-plate validation
- **Link:** Research manuscript in progress; source repository is not public

</details>

<details>
<summary><strong>2. Wind Power Forecasting</strong></summary>

- **Problem:** Forecast wind-power output from NWP data while handling SCADA-related corrections within competition rules.
- **My Contribution:** Engineered weather features, trained XGBoost models, and implemented a rule-compliant correction workflow.
- **Result:** Completed an end-to-end forecasting and correction pipeline; validation scores are omitted until a supporting artifact is public.
- **Methods:** NWP feature engineering · XGBoost · time-series validation
- **Link:** Source repository is not public

</details>

<details>
<summary><strong>3. Building Cooling Load Prediction</strong></summary>

- **Problem:** Predict floor-level cooling-energy demand from nonlinear building time-series data.
- **My Contribution:** Built the preprocessing and sliding-window pipeline, trained LSTM and BiGRU models, and tested an Attention-based architecture.
- **Result:** Completed a controlled three-model comparison using MAE and RMSE to evaluate floor-level cooling-load prediction.
- **Methods:** Python · TensorFlow · recurrent time-series models
- **Link:** [Portfolio case study](https://mech-insight-portfolio.lovable.app/projects/cooling-load-prediction)

</details>

<details>
<summary><strong>4. ANSYS Thermal Analysis</strong></summary>

- **Problem:** Determine the allowable input power of an electronic component while accounting for transient behavior and contact thermal resistance.
- **My Contribution:** Built the ANSYS thermal model, interpreted temperature and heat-flux fields, and performed the input-power parameter study.
- **Result:** Calculated a maximum allowable chip input power of approximately **13.154 W**.
- **Methods:** Transient thermal simulation · contact resistance · heat-flux analysis
- **Link:** [Portfolio case study](https://mech-insight-portfolio.lovable.app/projects/ansys-thermal-analysis)

</details>

<details>
<summary><strong>5. King Sejong Station Climate Analysis</strong></summary>

- **Problem:** Examine temperature anomalies and their relationship with regional sea-ice conditions across incomplete multi-year observations.
- **My Contribution:** Integrated KPDC weather and NSIDC sea-ice data, detected abnormal-temperature sequences, and evaluated lagged relationships.
- **Result:** Analyzed **1,493 daily records**, identified **36 consecutive abnormal-temperature events**, and found the strongest lag correlation at **−30 days** with **r ≈ −0.462**.
- **Methods:** Multi-source time-series integration · event detection · lag correlation
- **Link:** Source repository is not public

</details>

## Selected Engineering Results

| Project | Metric / Outcome | Engineering Significance |
|---|---|---|
| Core Body Temperature Estimation | Peak error **1.36°C → 0.90°C**; average MAE **0.178°C → 0.192°C** | Improved disturbance robustness, with the average-error tradeoff stated explicitly |
| ANSYS Thermal Analysis | Maximum allowable chip input power of approximately **13.154 W** | Converts simulation results into an equipment-design constraint |
| King Sejong Station Climate Analysis | **1,493 records**, **36 events**, strongest correlation at lag **−30 days**, **r ≈ −0.462** | Connects multi-source climate data with event and lag-based interpretation |
| Building Cooling Load Prediction | Controlled comparison of **LSTM, BiGRU, and Attention-based models** | Evaluates architecture choice for floor-level energy forecasting |

## Technical Skills

| Priority | Skills |
|---|---|
| Engineering & Validation | Mechanical Engineering · Heat Transfer · Fluid Mechanics · Thermal Analysis · Experimental Analysis · Engineering Validation · Root Cause Analysis |
| Data & Predictive Modeling | Python · Pandas · NumPy · Matplotlib · Scikit-learn · XGBoost · LSTM · BiGRU · Time-Series Forecasting |
| Embedded & Sensor Systems | Edge Impulse · Sensor Data Processing · Arduino C · C · C++ · CMake · Wio Terminal · MQTT |
| Engineering Tools | ANSYS · Jupyter · Tableau · Git · GitHub |

## Research and Current Work

- Evaluating robustness-focused core body temperature estimation under controlled thermal disturbances
- Expanding hot-plate-based validation and disturbance-response analysis
- Porting inference and post-processing logic into a pure C deployment path
- Developing NWP-based wind-power forecasting and SCADA-related correction methods
- Preparing a research manuscript on sensor-based temperature estimation and disturbance robustness

## Certifications and Courses

- TOEIC Speaking
- TOEIC
- Google Advanced Data Analytics Capstone
- Regression Analysis
- Machine Learning Nuts and Bolts
- Airbus Beyond: Supply Chains

## GitHub Analytics

<div align="center">
  <img height="165" src="https://github-profile-summary-cards.vercel.app/api/cards/stats?username=terry0524&theme=tokyonight" alt="Jongseok Park's GitHub stats" />
  <img height="165" src="https://github-profile-summary-cards.vercel.app/api/cards/repos-per-language?username=terry0524&theme=tokyonight" alt="Most-used languages in public GitHub repositories" />
  <br />
  <img height="165" src="https://streak-stats.demolab.com?user=terry0524&hide_border=true&theme=tokyonight" alt="Jongseok Park's GitHub contribution streak" />
</div>

> GitHub widgets reflect activity visible to their respective public APIs and may not represent private project work.

## Connect

- [LinkedIn](https://www.linkedin.com/in/terry0524)
- [Portfolio](https://mech-insight-portfolio.lovable.app)
- [Email](mailto:terry0524@soongsil.ac.kr)
- [GitHub](https://github.com/terry0524)

Open to conversations about physical AI, engineering analysis, validation, and data-driven mechanical systems.
