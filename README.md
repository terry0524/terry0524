<div align="center">

# Jongseok Park

### Mechanical Engineering × AI/Data × Physical Systems

I use Python to collect, process, and validate data, then implement and evaluate models and services for physical-system problems.

[Portfolio](https://mech-insight-portfolio.lovable.app) · [GitHub](https://github.com/terry0524) · [LinkedIn](https://www.linkedin.com/in/terry0524) · [Email](mailto:terry0524@soongsil.ac.kr)

</div>

## About Me

Mechanical engineering student at Soongsil University working across public APIs, sensor data, time-series modeling, and web services. I define the data and evaluation conditions before interpreting a model result, and state where a prototype still needs integration or validation.

## Data and Implementation Experience

| Area | Evidence | Tools / Methods |
|---|---|---|
| Collection & API integration | KHNP XML collector; URL-to-text input in JobDecoder | Python, HTTP/XML, Supabase Edge Functions |
| Processing & pipelines | Chunked mobility aggregation and spatial joins; building/weather alignment; lag and rolling features | pandas, NumPy, scikit-learn, spatial data tools |
| Data quality | Missing/stale/outlier flags; schema, duplicate and missing-field checks; source/time/hash records | Python validation, unittest |
| AI / ML implementation | Ridge/baseline comparison; LSTM/BiGRU/Attention experiments; LLM gateway; pretrained pose inference | scikit-learn, TensorFlow, Lovable gateway, MediaPipe |
| Service implementation | Static operations dashboard; JD analysis web app; browser-side exercise feedback | React, Next.js, TypeScript, shadcn/ui, Recharts |
| Evaluation & physical systems | Time-ordered comparisons; disturbance guard, Python replay and C++ implementation; explicit metric tradeoffs | MAE/RMSE, C/C++, sensor processing |

The portfolio update is awaiting publication on its existing Lovable host. Until then, the public repositories below provide the current implementation and validation details.

## Featured Projects

### 1. FlexPump AI — Public API Collection and Data Quality

- **Problem:** Inspect public pumped-storage observations before using them for analysis.
- **Implementation:** KHNP Python XML collector, common observation records, STALE/MISSING/OUTLIER flags, daily CSV checks, Ridge versus lag-7 baseline, and unit tests.
- **Scope:** A separate static dashboard MVP demonstrates the UI. KMA/KPX collectors, SCHEMA_CHANGED, automatic quality-based prediction exclusion, and live dashboard integration are not implemented.
- **Link:** [Public repository](https://github.com/terry0524/flexpump-ai) · [Static demo](https://terry0524.github.io/flexpump-ai/) · [Portfolio](https://mech-insight-portfolio.lovable.app/#projects)

### 2. Seoul Mobility Transition — Data Pipeline

- **Problem:** Turn heterogeneous transport and spatial inputs into reproducible district-level analysis.
- **Implementation:** Source audit, chunked pandas aggregation, spatial master construction, clustering, policy outputs, and validation reports.
- **Scope:** Raw source data is acquired separately. The README documents acquisition and remaining reproduction requirements; full reproduction requires the documented inputs and QA records.
- **Link:** [Public repository](https://github.com/terry0524/seoul-mobility-transition-2026) · [Portfolio](https://mech-insight-portfolio.lovable.app/#projects)

### 3. CBT / TempShield AI — Disturbance-Aware Sensor Processing

- **Problem:** Limit transient error under thermal disturbances while checking the aggregate-error tradeoff.
- **Implementation:** Temperature-rate cues, a causal hysteresis/hold/recovery guard, Python replay/evaluation, and C++ implementation.
- **Evaluation:** The revised manuscript reports median interval peak error 0.275°C → 0.210°C, with 93/104 selected intervals improving. Aggregate MAE changes from 0.178°C to 0.191°C. These are reference-relative results; 74 file entries are not 74 independent participants or recordings.
- **Research status:** Accepted for publication in International Journal of Precision Engineering and Manufacturing-Smart Technology on **2026-10-06**.
- **Access:** Company-provided original/derived data and code with unclear disclosure rights are not public. [Portfolio](https://mech-insight-portfolio.lovable.app/#projects)

### 4. Building Cooling Electricity Prediction

- **Problem:** Predict floor-level AC electricity consumption from CU-BEMS and separately acquired weather data.
- **Implementation:** Time alignment, 10-minute preprocessing, train-only scaling, sliding windows, and LSTM/BiGRU/BiGRU+Attention comparisons using MAE/RMSE/R².
- **Scope:** The target is AC electricity consumption, not measured thermal cooling load. Building airflow was not used. Attention did not improve every floor; filtered time gaps and weather interpolation are limitations.
- **Link:** [Public repository](https://github.com/terry0524/building-cooling-load-prediction) · [Portfolio](https://mech-insight-portfolio.lovable.app/#projects). Original datasets are acquired separately.

## Additional Projects

| Project | Implementation and limits | Links |
|---|---|---|
| JobDecoder | React/Vite + Supabase Edge Functions; URL input collection, Lovable AI gateway, response normalization and report UI. Match scores are AI outputs with no verified accuracy claim. | [Demo](https://job-decoder-0524.lovable.app) · [Case study](https://mech-insight-portfolio.lovable.app/project/job-decoder) |
| FormCheck AI | Browser-side MediaPipe PoseLandmarker plus deterministic exercise state/feedback logic. Uses a pretrained model; physical-device and exercise reliability validation remains limited. | [Demo](https://formcheck-ai-phi.vercel.app) · [Public repository](https://github.com/terry0524/formcheck-ai) · [Portfolio](https://mech-insight-portfolio.lovable.app/#projects) |

## Other Engineering Work

Wind-power forecasting, polar climate analysis, ANSYS thermal analysis, fluid experiments, and embedded course work provide supporting engineering context. They are not additional featured projects. [ANSYS case study](https://mech-insight-portfolio.lovable.app/project/ansys-thermal-analysis)

Smart Conveyor is a three-person course project connecting vision classification with rejection/recheck control. Its public repository is deferred until my authored scope and disclosure rights are confirmed.

## Technical Skills

- **Data:** Python, pandas, NumPy, scikit-learn, time-series preprocessing, validation
- **AI / services:** TensorFlow, LSTM, BiGRU, React, Next.js, TypeScript, Supabase Edge Functions, Lovable AI gateway, MediaPipe
- **Physical systems:** C/C++, Arduino, MQTT, Edge Impulse, ANSYS, thermal/fluid analysis
- **Workflow:** Git/GitHub, Jupyter, unit testing and metric-based comparison


## Certifications and Courses

- TOEIC Speaking
- TOEIC
- Google Advanced Data Analytics Capstone
- Regression Analysis
- Machine Learning Nuts and Bolts
- Airbus Beyond: Supply Chains

## Connect

[Portfolio](https://mech-insight-portfolio.lovable.app) · [LinkedIn](https://www.linkedin.com/in/terry0524) · [Email](mailto:terry0524@soongsil.ac.kr)
