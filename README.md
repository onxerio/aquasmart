AquaSmart v5.1
Presented at APSD 2026 — Africa Public Service Day, KICC Nairobi
"Enhancing Public Sector Institutions and Empowering Multi-Stakeholder Partnerships to Achieve Universal Water Availability and Safe Sanitation by 2063"


Diagram: ![AquaSmart Schematic](assets/aquasmart-schematic.svg)


💧 AQUASMART 
A 7-stage intelligent water purification and monitoring system with real-time heavy metal detection, adaptive electrochemical treatment, cryptographic audit logging, and a role-based digital command dashboard.

=PROBLEM 
Only 36% of Kenyans use a safely managed drinking water service (UN SDG Tracker, 2024).
Kenya has boreholes. Millions drink from them daily. But groundwater quality testing requires a manual sample sent to one of 10 labs nationwide, costing KES 5,000 per analysis. Results take days. No institution currently watches thousands of individual community boreholes continuously for contamination.
Chemical contaminants — fluoride, arsenic, iron, cadmium, manganese, chromium — occur widely in groundwater used for drinking but are not regularly monitored.
AquaSmart is the missing layer.
The System
7-Stage Treatment Pipeline

*Pre-filter
Removes sediment, protects downstream electrodes

 CDI
Ion adsorption at 1.4V — removes salts, nitrates. Auto-extends 10→20min at high TDS

Electrocoagulation (EC)
12V aluminium electrodes, polarity reversal every 10s. Removes ~75% fluoride, turbidity, bacteria

DPASV Detection
Electrochemical heavy metal identification 

Taste Regeneration 
Removes odour/chlorine, restores minerals

TDS Safety Gate
Physical outlet lock if TDS > 500 PPM. Water cannot leave unsafe by design

UV-C Disinfection 
2–3 log inactivation of bacteria, viruses, protozoa. Zero chemicals

Stripping Voltage
WHO Limit
Health Risk
Iron (Fe)
−0.5V
0.3 mg/L
Taste, staining
Cadmium (Cd)
−0.6V
0.003 mg/L
Kidney accumulation (10–30 years)
Manganese (Mn)
−0.7V
0.4 mg/L
Neurological damage
Arsenic (As)
−0.8V
0.010 mg/L
Group 1 carcinogen
Chromium (Cr)
−0.9V
0.05 mg/L
Carcinogenic (Cr VI)


Features
Live 7-stage pipeline view — real-time stage status
CDI health panel — electrode voltage, treatment duration, high-TDS mode
DPASV readout — metal concentrations vs WHO limits per batch
SHA-256 hash chain audit log — tamper-evident treatment history. Every record cryptographically sealed to the previous one
4 user roles — Super Admin, Admin, Operator, Viewer. Strict permission scoping
SCADA protection — 3-attempt lockout, 30-minute session timeout
AQUA Agent — AI water quality officer (Groq API, LLaMA 3.3 70B). Role-aware. Live data. Zero hardware execution privileges
Multilingual ticker — English, Swahili, Kikuyu, Kamba
Legal & Regulatory Compliance
Framework
Relevance
WHO GDWQ (4th Ed.)
All detection thresholds mapped directly
Water Act Sections 21 & 111
National water quality database duty
Water Act Sections 143 & 147
Pollution fines up to KES 1M — audit log provides evidence trail
EMCA CAP.387 Section 91
Hazardous waste — GO electrode disposal logged in hash chain
EMCA Section 142
Fines up to KES 5M — operator compliance by design
KEBS KS 459
Kenya national drinking water standard
AU Agenda 2063 Goal 1
Continental safe water access mandate
Scale Model
Hub and spoke. Water services provider owns central dashboard. AquaSmart units mount directly onto community boreholes — no new pipeline infrastructure.
Financing: M-KOPA-style pay-as-you-go mobile money tariff per litre. Self-sustaining utility, not a one-time government expense.
Data licensing: County governments, NGOs, and water boards license continuous borehole quality data — the resolution of coverage that does not exist in Kenya today.
Unit cost: Under KES 30,000 at component cost.


📧 GitHub: @onxerio
