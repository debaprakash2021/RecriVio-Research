 
# Dataset Methodology

**Project:** RecriVio – AI-Powered Recruitment Intelligence Platform

**Document Type:** Research Methodology

**Version:** 1.0

**Last Updated:** June 2026

---

# 1. Research Objective

## Primary Goal

Develop a comprehensive recruitment intelligence dataset that accurately represents modern hiring ecosystems, enabling AI-driven analytics, predictive hiring, workforce intelligence, recruiter productivity measurement, and recruitment optimization.

---

# 2. Research Methodology Framework

```
                    Research Planning
                           │
                           ▼
               Problem Definition
                           │
                           ▼
                 Data Source Selection
                           │
                           ▼
                  Data Collection
                           │
                           ▼
                   Data Validation
                           │
                           ▼
                 Data Cleaning & ETL
                           │
                           ▼
               Feature Engineering
                           │
                           ▼
                 Dataset Integration
                           │
                           ▼
                 Analytics Warehouse
                           │
                           ▼
              AI Model Consumption
                           │
                           ▼
             Dashboard Visualization
```

---

# 3. Research Design

| Attribute | Specification |
|------------|---------------|
| Research Type | Applied Research |
| Research Method | Quantitative + Descriptive |
| Research Domain | HR Technology, Recruitment Analytics, Artificial Intelligence |
| Dataset Nature | Structured + Semi-Structured |
| Processing Type | Batch + Real-Time |
| Analytical Approach | Descriptive, Diagnostic, Predictive |
| Validation Method | Cross Source Verification |
| Output | Recruitment Intelligence Dataset |

---

# 4. Dataset Objectives

| Objective ID | Description |
|--------------|-------------|
| D01 | Analyze recruitment funnel performance |
| D02 | Evaluate recruiter productivity |
| D03 | Measure ATS effectiveness |
| D04 | Predict hiring success probability |
| D05 | Analyze candidate behavior |
| D06 | Identify skill demand trends |
| D07 | Build hiring intelligence reports |
| D08 | Enable executive dashboards |
| D09 | Generate AI recommendations |
| D10 | Support predictive analytics |

---

# 5. Primary Data Sources

| Category | Data Source | Type | Update Frequency |
|-----------|-------------|------|------------------|
| Job Listings | LinkedIn Jobs | Structured | Daily |
| Job Listings | Indeed | Structured | Daily |
| Job Listings | Glassdoor | Structured | Daily |
| ATS Data | Greenhouse | Structured | Real-Time |
| ATS Data | Lever | Structured | Real-Time |
| ATS Data | Workday | Structured | Daily |
| ATS Data | Ashby | Structured | Daily |
| Company Hiring | Career Pages | Semi-Structured | Daily |
| Salary Intelligence | Glassdoor | Structured | Weekly |
| Salary Intelligence | Levels.fyi | Structured | Weekly |
| Skills Demand | LinkedIn Workforce Reports | Structured | Monthly |
| Labour Statistics | U.S. Bureau of Labor Statistics | Structured | Monthly |
| Labour Statistics | World Economic Forum Reports | Structured | Annual |
| Market Trends | Deloitte Human Capital Trends | Semi-Structured | Annual |
| Hiring Reports | SHRM | Semi-Structured | Quarterly |

---

# 6. Dataset Categories

## Candidate Dataset

### Core Attributes

- Candidate ID
- Name
- Email
- Phone
- Education
- Degree
- Institution
- Graduation Year
- Experience
- Skills
- Certifications
- Resume Score
- ATS Score
- AI Score
- Portfolio
- GitHub
- LinkedIn
- Expected Salary
- Current Location
- Preferred Location

---

## Job Dataset

Fields

- Job ID
- Company
- Department
- Employment Type
- Experience Required
- Required Skills
- Preferred Skills
- Salary Range
- Open Positions
- Hiring Manager
- Posting Date
- Closing Date
- Hiring Status

---

## Application Dataset

Fields

- Application ID
- Candidate ID
- Job ID
- Source
- Current Stage
- Application Date
- Resume Screening Result
- Interview Status
- Offer Status
- Joining Status
- Recruiter Assigned

---

## Interview Dataset

Fields

- Interview ID
- Interview Round
- Interview Type
- Interviewer
- Technical Score
- Communication Score
- Coding Score
- Behavioral Score
- Overall Recommendation
- Interview Duration
- Decision

---

## Recruiter Dataset

Fields

- Recruiter ID
- Recruiter Name
- Department
- Jobs Managed
- Candidates Screened
- Interviews Scheduled
- Offers Released
- Successful Hires
- Average Time-to-Hire
- Productivity Score

---

# 7. Feature Engineering

## Derived Features

| Feature | Formula |
|----------|----------|
| Resume Match Score | Skill Similarity + Experience Similarity |
| Candidate Ranking | Weighted Candidate Score |
| Hiring Probability | ML Prediction |
| Skill Gap Score | Required Skills - Candidate Skills |
| Recruiter Efficiency | Hires / Assigned Jobs |
| Source Quality | Successful Hires / Total Applicants |
| Interview Success Rate | Cleared Interviews / Conducted Interviews |
| Offer Acceptance Rate | Accepted Offers / Total Offers |
| Candidate Quality Index | Composite Weighted Score |
| Hiring Velocity | Total Hires / Month |

---

# 8. Data Collection Pipeline

```
External Sources
        │
        ▼
API Collection Layer
        │
        ▼
Raw Dataset Storage
        │
        ▼
Duplicate Detection
        │
        ▼
Missing Value Processing
        │
        ▼
Normalization
        │
        ▼
Feature Engineering
        │
        ▼
Validation Layer
        │
        ▼
Analytics Warehouse
        │
        ▼
AI Engine
        │
        ▼
Dashboard
```

---

# 9. Data Cleaning Strategy

## Duplicate Handling

- Candidate Email Matching
- Phone Number Matching
- Resume Hash Comparison
- LinkedIn URL Validation

---

## Missing Values

| Missing Field | Strategy |
|---------------|----------|
| Skills | Resume Parsing |
| Experience | Resume Extraction |
| Salary | Market Estimation |
| Location | Geocoding |
| Education | Resume Parsing |

---

## Standardization Rules

- Dates → ISO-8601
- Salary → INR/USD Standard
- Skills → Taxonomy Mapping
- Company Names → Canonical Naming
- Degree Names → Standard Academic Format

---

# 10. Data Validation Rules

| Rule | Validation |
|------|------------|
| Email | RFC Standard |
| Phone | Country Format |
| Salary | Positive Numeric |
| Experience | ≥ 0 Years |
| Interview Score | 0–100 |
| Resume Score | 0–100 |
| ATS Score | 0–100 |

---

# 11. Data Quality Metrics

| Metric | Target |
|---------|--------|
| Completeness | >98% |
| Accuracy | >97% |
| Consistency | >99% |
| Duplicate Rate | <1% |
| Missing Values | <2% |
| Validation Success | >99% |

---

# 12. Dataset Relationships

```
Candidate
    │
    ├──────── Applications
    │              │
    │              ▼
    │         Job Posting
    │              │
    │              ▼
    │         Interview
    │              │
    │              ▼
    │          Offer
    │              │
    │              ▼
    └──────── Employee
```

---

# 13. AI Feature Consumption

| AI Module | Dataset Used |
|------------|--------------|
| Resume Ranking | Candidate Dataset |
| Skill Gap Analysis | Candidate + Job Dataset |
| Hiring Prediction | Application Dataset |
| Salary Prediction | Salary Dataset |
| Recruiter Analytics | Recruiter Dataset |
| Offer Prediction | Interview Dataset |
| Candidate Recommendation | Combined Dataset |

---

# 14. Privacy & Compliance

- GDPR Compliance
- CCPA Compliance
- Data Anonymization
- Personally Identifiable Information (PII) Masking
- AES-256 Encryption for Sensitive Fields
- Role-Based Access Control (RBAC)
- Audit Logging
- Consent Management

---

# 15. Research Limitations

| Limitation | Impact |
|------------|--------|
| Proprietary ATS data availability | Limited access to enterprise datasets |
| Regional hiring bias | Country-specific trends may vary |
| Salary disclosure inconsistency | Approximation required in some markets |
| Public job posting dependency | Hidden job markets excluded |
| Rapid market changes | Periodic dataset updates required |

---

# 16. Future Dataset Expansion

- Real-time labor market intelligence
- GitHub developer activity integration
- Stack Overflow Developer Survey integration
- HackerRank coding assessment data
- AI interview transcript analysis
- Employee retention datasets
- Workforce diversity benchmarking
- Internal organizational performance datasets

---

# 17. Expected Dataset Scale

| Dataset | Estimated Records |
|----------|------------------:|
| Candidates | 500,000+ |
| Job Postings | 120,000+ |
| Applications | 3,500,000+ |
| Recruiters | 8,000+ |
| Interviews | 1,200,000+ |
| Offers | 250,000+ |
| Companies | 15,000+ |
| Skills | 18,000+ |
| Salary Records | 1,000,000+ |

---

# 18. Conclusion

The proposed dataset methodology establishes a scalable, research-oriented recruitment intelligence framework by integrating structured hiring data, labor market statistics, ATS records, salary benchmarks, and AI-generated features. The methodology supports descriptive, diagnostic, and predictive analytics while maintaining high standards of data quality, privacy, and reproducibility. This foundation enables RecriVio to deliver enterprise-grade recruitment intelligence and AI-assisted hiring insights.