# Partner Demand Calculator - FY 2027

An interactive demand planning tool for partners to calculate the required demand generation activity to meet their FY 2027 cloud bookings targets.

## What It Does

Partners enter six inputs and the calculator derives the full demand funnel:

| Input | Description |
|-------|-------------|
| Cloud Bookings Target (kEUR) | Total bookings target for FY 2027 |
| Existing Pipeline (kEUR) | Qualified pipeline already in place |
| Average Deal Size (kEUR) | Won and Booked pipeline / Number of opportunities won |
| Opportunity Conversion Rate (%) | Pipeline Won and Booked / Total Pipeline Created |
| MQL to SQL Conversion Rate (%) | Marketing Leads that convert to Sales Opportunities |
| TAM to MQLs Rate (%) | Target Accounts that become Marketing Qualified Leads |

**Outputs (all rounded up, no decimals):**
- Bookings from Existing Pipeline
- Remaining Budget to Retire
- Volume of Won/Booked Required
- Sales Pipeline (Demand Target)
- Volume of SQLs Required
- Volume of MQLs Required
- Total Addressable Market (TAM)

## Features

- Single self-contained HTML file with no external dependencies
- Runs entirely in the browser with no data transmitted externally
- Real-time demand funnel visualization
- PDF export with section-level page-break protection
- Responsive design (desktop, tablet, mobile)
- Print-friendly layout

## How to Use

1. Open `index.html` in any modern browser (Chrome, Edge, Firefox, Safari)
2. Enter your partner name and input parameters
3. Click **Calculate** to see results and the demand funnel
4. Click **Download PDF** to save a clean report

## Deployment

This repository is configured for [GitHub Pages](https://pages.github.com/). The calculator is published at:

```
https://<your-username>.github.io/demand-calculator/
```

## Privacy

All calculations run locally in the browser. No data is collected, transmitted, or stored on any server.

## Contact

Partner Ecosystem Success | Partner Business Development

---

*This tool is provided for planning purposes only. All calculations are indicative and based on the inputs provided.*
