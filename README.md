# Demand Management Tracker

A comprehensive application for tracking and managing demand requests with detailed metrics, timelines, and resource allocation.

## Features

- **Demand Tracking**: Track demand requests with detailed information
- **Status Management**: Monitor demand status through various stages
- **NPS Tracking**: Net Promoter Score tracking and analytics
- **Resource Planning**: Effort estimation and resource allocation
- **QA Management**: Quality assurance tracking and metrics
- **Source Management**: Track new sources and data sources
- **Timeline Management**: Approved dates, revised dates, and due dates

## Project Structure

```
DemandManagementTracker/
├── frontend/          # React/Vue frontend application
├── backend/           # Node/Express backend API
├── database/          # Database schemas and migrations
├── docs/              # Documentation
└── scripts/           # Utility scripts
```

## Quick Start

1. Clone the repository
2. Install dependencies
3. Configure environment variables
4. Run migrations
5. Start the application

## Excel Format to Application

### Column Mapping

| Excel Column | Data Type | Description |
|---|---|---|
| Number | Integer | Unique demand identifier |
| Name | String | Demand name/title |
| Status | String | Current status (Open, In Progress, Closed, etc.) |
| NPS | Numeric | Net Promoter Score |
| QTR | String | Quarter (Q1, Q2, Q3, Q4) |
| POD | String | Pod/Team identifier |
| Complexity | String | Complexity level (Low, Medium, High) |
| Approved Start DT | Date | Approved start date |
| Due_DT Revised | Date | Revised due date |
| Approved Due DT | Date | Approved due date |
| Calculator Effort | Numeric | Calculated effort hours |
| Efforts Revised | Numeric | Revised effort hours |
| Approved Effort | Numeric | Approved effort hours |
| Approved Badging | String | Badging information |
| Framework Change | Boolean | Framework change required |
| RAW | String | RAW status |
| RAW # | Numeric | RAW count |
| QA | String | QA status |
| QA # | Numeric | QA count |
| Conformed | String | Conformed status |
| Conformed # | Numeric | Conformed count |
| New Source Added | String | New source status |
| Source # | Numeric | Source count |
| Demand Owner/Comments | String | Owner name and comments |
