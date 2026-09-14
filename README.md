<img width="1047" height="679" alt="Screenshot 2026-09-13 at 10 52 48 PM" src="https://github.com/user-attachments/assets/f26a1f2c-72af-4ca1-836b-6c4802c1644d" />
# Conceptual 69-kV / 12.47-kV Distribution Substation Engineering Design
Independent engineering portfolio project demonstrating conceptual substation design, electrical calculations, AutoCAD single-line development, protection philosophy, equipment assessment, risk analysis, reliability considerations, preventive maintenance planning, requirements traceability, and structured design QA.
> **Status:** Conceptual / Portfolio Project  
> **Not for Construction**

## Project Overview

This project develops a conceptual 69-kV / 12.47-kV distribution substation supplying six radial distribution feeders and a conceptual station-service load.

The study uses a 40-MVA, three-phase main transformer to supply a maximum assumed coincident load of 33.5 MVA. The project follows a structured engineering workflow from requirements definition and design-basis development through calculations, electrical single-line design, risk assessment, and final QA.

### Key Design Parameters

| Parameter | Value |
|---|---:|
| High-side voltage | 69 kV |
| Low-side voltage | 12.47 kV |
| Main transformer | 40 MVA |
| Transformer impedance | 8% conceptual assumption |
| Maximum study load | 33.5 MVA |
| Power factor | 0.90 lagging |
| Distribution feeders | 6 |
| System configuration | Radial |
| Station-service load | 0.5 MVA |

## Key Engineering Results

- Maximum assumed coincident load: **33.5 MVA**
- Real power at 0.90 power factor: **30.15 MW**
- Reactive power: **approximately 14.60 MVAr**
- Main-transformer loading: **83.75%**
- 69-kV operating current: **approximately 280.3 A**
- 12.47-kV operating current: **approximately 1.551 kA**
- Preliminary transformer-limited three-phase symmetrical fault current at the 12.47-kV bus: **approximately 23.15 kA**

### Transformer-Impedance Sensitivity

| Transformer Impedance | Preliminary Fault Current |
|---:|---:|
| 6% | 30.87 kA |
| 8% | 23.15 kA |
| 10% | 18.52 kA |

## Project Deliverables

| Deliverable | Description |
|---|---|
| Final Engineering Report | Summary of the complete conceptual engineering study |
| Electrical SLD | Final AutoCAD single-line diagram |
| Load Calculations | Load, power, operating-current, and transformer-utilization analysis |
| Short-Circuit Analysis | Preliminary transformer-limited fault-current assessment |
| Equipment Schedule | Preliminary equipment and duty assessment |
| Protection Coordination | Conceptual protection philosophy and coordination matrix |
| Risk & Reliability | FMEA, risk register, and reliability assessment |
| Preventive Maintenance | Conceptual equipment-maintenance strategy |
| QA / Design Review | QA checklist, requirements closure, findings, and open items |

## Study Limitations

This project is a conceptual engineering study and does not represent a utility-approved or construction-ready design.

The following items require detailed engineering and site-, utility-, or manufacturer-specific information:

- Utility source impedance, available fault current, and X/R ratio
- Site soil-resistivity data
- Detailed grounding-grid analysis
- Final relay settings and time-current coordination
- Final breaker interrupting and equipment short-circuit ratings
- Final CT/PT ratios and classes
- Final surge-arrester characteristics
- Detailed station-service load study
- Utility contingency and reliability criteria
- Arc-flash analysis
- Physical, civil, and structural substation design

- ## Tools Used

- **AutoCAD 2027 for Mac** — Electrical single-line diagram development
- **Microsoft Excel / Google Sheets** — Engineering calculations, FMEA, risk analysis, equipment schedules, requirements tracking, and QA
- **Microsoft Word / Google Docs** — Engineering documentation and final report development

- ## Repository Structure

```text
.
├── README.md
├── Final_Report/
│   └── Conceptual_Substation_Engineering_Report.pdf
├── Electrical_Design/
│   ├── Conceptual_Substation_Single_Line-SLD.pdf
│   └── Conceptual_Substation_Single_Line.dwg
├── Calculations/
│   ├── Load_Calculations.xlsx
│   └── Short_Circuit_Analysis.xlsx
├── Protection_Coordination/
├── Risk_Reliability_Maintenance/
└── QA_Design_Review/
