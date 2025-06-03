# Healthcare Data Analysis Project

## Project Overview

This project explores clinical visit data from a healthcare provider to extract actionable insights that support strategic decision-making, enhance patient care and improve financial sustainability.

**Objectives:**
- Analyze visit patterns by time, location, and type (in-person vs telemedicine)
- Evaluate billing trends across payment methods (Cash vs Insurance)
- Assess patient satisfaction using Net Promoter Score (NPS)
- Identify common diagnoses and explore trends across various dimensions

## Dataset Description
The project is based on three related datasets:

# 🏥 Healthcare Data Analysis Project

## 📌 Project Overview

This project explores clinical visit data from a healthcare provider to extract actionable insights that support strategic decision-making, enhance patient care, and improve financial sustainability.

**Objectives:**
- Analyze visit patterns by time, location, and type (in-person vs telemedicine)
- Evaluate billing trends across payment methods (Cash vs Insurance)
- Assess patient satisfaction using Net Promoter Score (NPS)
- Identify common diagnoses and explore trends across various dimensions

---

## 🧾 Dataset Description

The project is based on three related datasets:

# 🏥 Healthcare Data Analysis Project

## 📌 Project Overview

This project explores clinical visit data from a healthcare provider to extract actionable insights that support strategic decision-making, enhance patient care, and improve financial sustainability.

**Objectives:**
- Analyze visit patterns by time, location, and type (in-person vs telemedicine)
- Evaluate billing trends across payment methods (Cash vs Insurance)
- Assess patient satisfaction using Net Promoter Score (NPS)
- Identify common diagnoses and explore trends across various dimensions

## Dataset Description

The project is based on three related datasets:

| Table            | Description                                                  |
|------------------|--------------------------------------------------------------|
| `Visit Table`    | Records each clinical visit, including time, type, and location |
| `Billing Table`  | Tracks invoiced amounts per visit (may have multiple entries) |
| `Diagnosis Table`| Contains diagnosis codes linked to visits                    |

### Key Features:
- `VisitCode`: Unique identifier for each clinical visit  
- `VisitDateTime`: Date and time of the visit  
- `MedicalCenter`: Name of the medical center  
- `VisitCategory`: Type of visit (In-person or Telemedicine)  
- `Payor`: Payment method (Cash or Insurance)  
- `Amount`: Billed amount per invoice  
- `NPS Score`: Patient satisfaction rating (0–10)  
- `Diagnosis`: Medical condition identified during the visit  


## Exploratory Data Analysis (EDA)

### Key Insights:
- In-person visits dominate but virtual visits are growing
- Insurance visits yield higher average revenue per visit
- Certain medical centers have higher NPS scores
- Most common diagnoses: [e.g. URTI, Malaria, Hypertension]

## Recommendations

- Allocate more staff to high-traffic centers
- Expand telemedicine services for follow-ups and mild conditions
- Investigate causes of low NPS in underperforming centers
- Track diagnosis patterns for better inventory and planning
              
## Tools & Technologies

- Python: `pandas`, `matplotlib`, `seaborn`
- Jupyter Notebook




