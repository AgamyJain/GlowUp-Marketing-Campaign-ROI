# GlowUp Marketing Campaign ROI Analysis

<p align="center">
  <img src="https://img.shields.io/badge/Power%20BI-Dashboard-F2C811?logo=powerbi&logoColor=black" alt="Power BI">
  <img src="https://img.shields.io/badge/Analytics-Marketing%20ROI-4472C4" alt="Marketing Analytics">
  <img src="https://img.shields.io/badge/Status-Completed-green" alt="Completed">
</p>

<p align="center">
  <strong>A Power BI marketing analytics project evaluating campaign expenditure, revenue, ROI, and campaign performance to support data-informed budget decisions.</strong>
</p>

---

## Table of Contents

- [Project Abstract](#project-abstract)
- [Business Scenario](#business-scenario)
- [Business Objectives](#business-objectives)
- [Business Questions](#business-questions)
- [Dataset Overview](#dataset-overview)
- [Tools and Techniques](#tools-and-techniques)
- [Methodology](#methodology)
- [Dashboard Preview](#dashboard-preview)
- [Key Findings](#key-findings)
- [Business Recommendations](#business-recommendations)
- [Project Structure](#project-structure)
- [How to Review the Project](#how-to-review-the-project)
- [Limitations](#limitations)
- [Author](#author)

---

## Project Abstract

GlowUp is a marketing campaign analytics case study focused on evaluating campaign expenditure, revenue generation, and return on investment. The project uses Power BI to compare marketing performance and organize campaign metrics into an accessible dashboard.

The analysis is designed to help evaluate which campaigns appear more efficient under the selected ROI definition, compare campaign-level results, and identify areas for further investigation. The dashboard supports business discussions about future marketing investment and campaign optimization.

ROI calculations depend on the definitions used for revenue and spend. Aggregate ROI and the simple average of campaign-level ROI percentages can produce different results, so the interpretation of each metric must remain consistent with the report and dashboard.

## Business Scenario

GlowUp is presented as a beauty and skincare startup that has run online and offline marketing campaigns, including social media advertising, influencer collaborations, and local events.

Management wants to understand which campaigns deliver stronger returns and how future marketing budgets could be allocated more effectively.

## Business Objectives

- Compare campaign performance using available metrics.
- Evaluate return on marketing expenditure.
- Examine conversion and engagement measures where available.
- Identify campaigns for further review.
- Recommend evidence-based approaches to future budget allocation.

## Business Questions

1. Which campaigns have the strongest ROI under the selected formula?
2. How do campaign results differ across available channels?
3. Which campaigns generate leads or conversions efficiently?
4. How do campaign expenditure and revenue compare?
5. What changes could improve future campaign performance?

## Dataset Overview

| Attribute | Description |
|---|---|
| Dataset | `glowup_campaigns.csv` |
| Format | CSV |
| Analysis tool | Microsoft Power BI |
| Business domain | Marketing campaign analytics |

The dataset contains the campaign information used in the analysis. Refer to the source file and report for the exact fields and metric definitions.

## Tools and Techniques

- Microsoft Power BI
- Data inspection and preparation
- DAX measures
- ROI analysis
- Campaign comparisons
- KPI visualization
- Business interpretation

## Methodology

### 1. Data Preparation

Inspect the campaign dataset and prepare the fields used in the analysis.

### 2. KPI Calculation

Evaluate available campaign expenditure, revenue, and performance measures.

**ROI formula:**

`ROI (%) = (Revenue - Spend) / Spend × 100`

This formula measures return relative to marketing spend using the project's revenue definition.

### 3. Campaign Comparison

Compare campaign results using the metrics available in the dataset.

### 4. Dashboard Development

Present campaign-level performance and comparisons through Power BI visualizations.

### 5. Recommendations

Use observed campaign results to identify opportunities for further testing and budget review.

## Dashboard Preview

![GlowUp Marketing ROI Dashboard](images/GlowUp_Marketing_ROI_Dashboard.png)

[Open the dashboard PDF](dashboard/GlowUp_Marketing_ROI_Dashboard.pdf)

## Key Findings

The project examines campaign performance using the selected ROI definition and available campaign metrics.

Consult the final dashboard and report for the confirmed results. Aggregate ROI and average campaign ROI should be distinguished when interpreting overall performance.

## Business Recommendations

- Compare campaigns using a consistent ROI definition.
- Review campaign spend alongside revenue and conversion measures where available.
- Investigate campaigns with relatively weak returns before increasing investment.
- Test budget reallocations incrementally and measure subsequent results.
- Document assumptions where source data is incomplete.

## Project Structure

```text
GlowUp-Marketing-Campaign-ROI/
├── README.md
├── data/
│   └── glowup_campaigns.csv
├── dashboard/
│   ├── GlowUp_Marketing_ROI_Dashboard.pbix
│   └── GlowUp_Marketing_ROI_Dashboard.pdf
├── report/
│   ├── GlowUp_Marketing_ROI_Report.docx
│   └── GlowUp_Marketing_ROI_Report.pdf
└── presentation/
    ├── GlowUp_Executive_Presentation.pptx
    └── GlowUp_Executive_Presentation.pdf
