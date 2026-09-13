# 📊 BizSight

### Turning Data into Decisions

**BizSight** is an AI-powered business analytics platform built for **Small and Medium Enterprises (SMEs), e-commerce businesses, and online sellers** — helping them understand their sales and financial data without needing a data analyst.

Users upload raw business data, and BizSight automatically cleans it, maps it to the right business fields, calculates key financial metrics, generates plain-language insights, and presents everything through an interactive dashboard.

> 🏆 Built for the **HEC – NCEAC & PEC Generative & Agentic AI Training – Cohort 11 Mid-Term Hackathon**

🔗 **Live Application:** [bizzsight.vercel.app](https://bizzsight.vercel.app)

---

## 📁 Repository Contents

This repository contains the complete hackathon submission for BizSight:

| Deliverable | Description |
|---|---|
| [`BizSight_Code/`](./BizSight_Code) | Full source code (frontend + backend) — see its README for setup and architecture details |
| [`BizSight_PRD.pdf`](./BizSight_PRD.pdf) | Product Requirements Document |
| [`BizSight_Presentation_Slides.pptx`](./BizSight_Presentation_Slides.pptx) | Presentation slides used for the project walkthrough |

### Folder Structure

```text
HACKATHON-MIDTERM-PROJECT/
│
├── BizSight_Code/
│   │
│   ├── frontend/
│   │   │
│   │   ├── app/
│   │   │   ├── api/
│   │   │   │   ├── process/
│   │   │   │   │   └── route.js
│   │   │   │   │
│   │   │   │   └── suggest-mapping/
│   │   │   │       └── route.js
│   │   │   │
│   │   │   ├── components/
│   │   │   │   ├── Navbar.jsx
│   │   │   │   ├── Hero.jsx
│   │   │   │   ├── HowItWorks.jsx
│   │   │   │   ├── Features.jsx
│   │   │   │   ├── FileUpload.jsx
│   │   │   │   ├── MappingReview.jsx
│   │   │   │   └── Dashboard.jsx
│   │   │   │
│   │   │   ├── analyze/
│   │   │   │   └── page.js
│   │   │   │
│   │   │   └── page.js
│   │   │
│   │   ├── package.json
│   │   └── ...
│   │
│   ├── python-service/
│   │   │
│   │   ├── pipeline/
│   │   │   ├── cleaning.py
│   │   │   ├── mapping.py
│   │   │   └── metrics.py
│   │   │
│   │   ├── main.py
│   │   └── requirements.txt
│   │
│   ├── sample_messy_orders.csv
│   ├── .gitignore
│   └── README.md
│
├── BizSight_PRD.pdf
├── BizSight_Presentation_Slides.pptx
└── README.md
```

---

## 🚀 What Does BizSight Do?

BizSight simplifies the process of converting raw business data into meaningful insights:

**Upload Data → Clean Data → Map Columns → Analyze → Generate Insights → Visualize Results**

Supported upload formats: `.CSV`, `.XLS`, `.XLSX`

BizSight calculates key business metrics including:

- Revenue
- Cost of Goods Sold (COGS)
- Gross Profit
- Net Profit
- Number of Orders
- Average Order Value (AOV)
- Customer Acquisition Cost (CAC)
- Repeat Purchase Rate
- Return / Cancellation Rate
- Marketing Spend

...and layers AI-generated, plain-language business insights on top of the numbers.

---

## ✨ Key Features

- 📁 **Data Upload** — CSV, XLS, and XLSX support
- 🧹 **Automatic Data Cleaning** — handles duplicates, missing values, irrelevant data, and inconsistent formatting
- 🔄 **Smart Column Mapping** — detects and maps differently-labeled columns (e.g., "Client Name," "Buyer" → "Customer Name")
- ✅ **Human-in-the-Loop Review** — users confirm or correct mapping before analysis runs
- 📈 **Business Analytics** — calculates the core financial and statistical metrics listed above
- 🤖 **AI / LLM-Based Insights** — turns numbers into plain-language business recommendations
- 📊 **Interactive Dashboard** — visualizes metrics through charts, graphs, and summary cards

---

## 🛠️ Tech Stack

| Layer | Technology |
|---|---|
| Frontend | Next.js, React, Tailwind CSS |
| Backend | Python, FastAPI |
| Data Processing | Pandas |
| Intelligent Mapping | LLM, RapidFuzz |
| Deployment | Vercel |

For a full architecture breakdown, project structure, and local setup instructions, see the [BizSight_Code README](./BizSight_Code/README.md).

---

## 🔄 How It Works

1. **Upload** — User uploads a CSV/Excel file.
2. **Clean** — Backend cleans and prepares the dataset.
3. **Map** — System suggests column mappings automatically.
4. **Verify** — User reviews and confirms the mapping.
5. **Analyze** — Backend calculates key business metrics.
6. **Insights** — LLM converts metrics into business recommendations.
7. **Visualize** — Dashboard displays charts, metrics, and insights.
8. **Export** — User downloads the processed analysis.

---

## 👨‍💻 Project Team

| Team Member | Role | Contribution |
|---|---|---|
| **Manahil Asif** | Team Lead | Coordinated the project end-to-end, prepared the presentation slides and all visualizations, and assisted with application testing and quality assurance. |
| **Abdul Muqeet** | Lead Developer | Designed and developed the complete application — frontend, backend, data processing, analytics, integration, and deployment. |
| **Areeba Tahir** | Live Demo & QA | Tested the application, recorded and presented the live demo, and supported presentation delivery. |
| **Faiza Batool** | Research & Documentation | Came up with the original project idea and led project research, content organization, and documentation support. |

---

## 🎯 Project Objective

Many small businesses collect large amounts of sales and customer data but lack the technical knowledge or dedicated analysts to interpret it. BizSight bridges that gap with a simple workflow:

> **Upload your data → Let BizSight analyze it → Understand your business → Make better decisions.**

---

## 🔮 Future Improvements

- Shopify / WooCommerce integration
- Direct website data extraction
- Predictive analytics & sales forecasting
- Customer segmentation
- Product-level profitability analysis
- Automated Power BI dashboard generation
- Real-time analytics
- Multi-business / multi-user accounts

---

## 📌 Project Status

**Current Status:** Functional Prototype / Hackathon Project

BizSight currently supports the full core workflow — **Upload → Cleaning → Mapping → Analysis → Insights → Dashboard** — with an architecture designed to support additional data sources and AI capabilities in future versions.

---

## 🔗 Quick Links

- 🌐 Live App: [bizzsight.vercel.app](https://bizzsight.vercel.app)
- 📄 [Product Requirements Document](./BizSight_PRD.pdf)
- 📊 [Presentation Slides](./BizSight_Presentation_Slides.pptx)
- 💻 [Source Code](./BizSight_Code)

---

**Built with Python, FastAPI, Next.js, React, Tailwind CSS, Pandas & LLM technologies.**
