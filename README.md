# **Rabivy**

This project develops a go-to-market strategy for Rabivy (maridebart cafraglutide), AX Pharmaceutical's investigational antibody-peptide conjugate for the treatment of obesity and Type 2 diabetes. 

**This project is for demonstration purposes only and was not commissioned by AX Pharmaceuticals.**

**All data is simulated based on publically available literature.**

The goal is to move beyond a conventional launch playbook and build a decision science-driven commercial system - one that identifies the right patients, surfaces the highest-probability prescribers, and puts actionable intelligence directly in the hands of AX Pharmaceutical's commercial teams. The work spans the full arc from strategic framing through to a production-ready, continuously updated deployment: starting with the conceptual framework, progressing into predictive modelling, translating outputs into rep-facing tools, and closing with an automated pipeline that keeps the system current as the market evolves.

*Figure 1. Project Overview*

<img width="4400" height="2475" alt="GTM Project Overview V2" src="https://github.com/user-attachments/assets/38da2afc-3f6e-47ec-94b0-4747f7419943" />


---

## Phase 1 - GTM Conceptualisation

The first phase involved mapping the strategic landscape and defining the core frameworks that would underpin the GTM approach.

This included an analysis of the GLP-1 market (see figure 1 below), competitive positioning against Novo Nordisk and Eli Lilly, patient segmentation across core and non-core populations, clinician targeting priorities, a prescriber propensity model, and a payer coverage breakdown by payer type.

*Figure 2. Market Breakdown*

<img width="650" height="450" alt="GLP1 Target Market" src="https://github.com/user-attachments/assets/34eda982-e59e-40ed-8c93-b1b1551b7779" />

The output of this phase is a single-page strategic overview, captured in the FigJam whiteboard linked below.

Link to whiteboard -> https://www.figma.com/board/oSwiFlp6dT6MgfH1QCZJkj/AX-Pharma-Rabivy-GTM-Strategy?node-id=436-960&t=eJx4DY8dpyspgabI-1

---

## Phase 2 - Predictive Modelling

In Phase 2, we built a propensity-to-prescribe model using simulated HCP data and literature-based weightings. The scorecard combines nine variables - including prescribing volume, payer mix, formulary tier, prior authorization burden, and existing AX Pharmaceuticals relationship - into a single score that identifies high-probability Rabivy prescribers and competitive switching opportunities.

*Figure 3. Geographic Distribution of Potential Rabivy Prescribers*

<img width="700" height="500" alt="image" src="https://github.com/user-attachments/assets/caea57ef-c022-491e-9740-696c02c23f68" />

---

## Phase 3 - UX & Commercial Enablement

In Phase 3, we built a rep-facing dashboard that allows commercial users to filter HCPs by territory, segment, and score, supporting prioritisation in the field.

*Figure 4. Rabivy Propensity Dashboard*

<img width="897" height="488" alt="image" src="https://github.com/user-attachments/assets/13d5403e-90a6-4353-ae73-1fb0e9a42b05" />


---

## Phase 4 - CI/CD & Deployment

Develop an automated pipeline for continuous model refresh and deployment.

### Focus Areas
- Automated data ingestion
- Model retraining
- Version control
- Monitoring & validation
- Scalable deployment architecture

---
