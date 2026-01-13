Maven – Inhouse Power BI Dashboard
📌 Overview

Maven-Inhouse Dashboard is an internal Power BI reporting solution built to track and monitor the complete lead journey across multiple marketing campaigns and projects. The dashboard provides end-to-end visibility into lead inflow, CRM stage progression, opportunity creation, and key performance metrics such as CPL (Cost Per Lead) and CPQL (Cost Per Qualified Lead).

The core data structure is designed around Project as the unique identifier — where a single project can have multiple campaigns running simultaneously, and leads are generated across these campaigns.

🎯 Key Objectives

This dashboard was developed to solve the following business needs:

Track total leads generated campaign-wise and project-wise

Monitor the current CRM stage of every lead

Identify whether an Opportunity has been created for each lead

Evaluate marketing efficiency using CPL and CPQL, campaign-wise

Enable performance comparison across campaigns under the same project

🔍 Dashboard Features

✅ Lead Tracking & Funnel View

Total leads received across campaigns

Lead distribution across CRM stages

✅ CRM Stage Monitoring

Real-time view of the current stage of each lead

Stage-wise lead movement insights

✅ Opportunity Conversion Tracking

Opportunity created status for each lead

Conversion trend based on campaign and project

✅ Campaign Performance Metrics

CPL (Cost Per Lead) by campaign

CPQL (Cost Per Qualified Lead) by campaign

Project-level rollups for overall ROI insights

🧩 Data Model & Logic

Project acts as the primary mapping key

One Project → Multiple Campaigns

Leads are mapped to campaigns, and their stage + opportunity status is tracked using CRM data

Calculations are built using Power BI measures to ensure accurate and campaign-level cost performance reporting

🛠 Tools & Technologies

Power BI (Dashboard Development, Visuals, DAX Measures)

CRM Data Integration (Lead stage + opportunity creation status)

Campaign Spend Data (Used for CPL and CPQL calculation)

📈 Business Impact

This dashboard helps internal stakeholders:

Make faster campaign optimization decisions

Improve visibility across the sales funnel

Identify high-performing campaigns and underperforming channels

Track project-wise marketing outcomes and opportunity conversions
