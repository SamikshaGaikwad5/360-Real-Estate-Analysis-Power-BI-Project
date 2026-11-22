# Real Estate Business Analytics Dashboard

An interactive **Real Estate Analytics Dashboard** designed to monitor property inventory, sales performance, lead generation, agent productivity, and marketing effectiveness. The report brings key business KPIs and detailed visual analysis together to support data-driven decisions across the real estate business.

> **Project scope:** This README is based on the dashboard pages shown in the project PDF. The PDF does not specify the source dataset, exact data-cleaning steps, database, or complete technology stack. Add those details in the relevant sections below before publishing if they apply to your project.

---

## Dashboard Overview

The report is organized into five analytical areas:

| Dashboard page | Business area | What it helps analyze |
|---|---|---|
| 1. Property Analytics | Property inventory | Property availability, bookings, sales, property types, BHK, locations, price segments, and area |
| 2. Sales Analytics | Sales and revenue | Revenue, sales volume, discounts, year-over-year growth, target achievement, payment status, and agent sales |
| 3. Lead & CRM Analytics | Lead management | Lead volume, qualification, site visits, bookings, conversions, sources, status, and lead funnel |
| 4. Agent Performance | Agent productivity | Agent-wise leads, sales, revenue, target achievement, conversion rate, and productivity |
| 5. Marketing Analytics | Marketing effectiveness | Marketing spend, leads generated, conversions, cost per lead, ROI, and channel performance |

## Key Features

- KPI cards for quick monitoring of important business measures.
- Interactive slicers/filters to explore the report by dimensions such as year, city, location, property type, BHK, price category, agent, lead source, lead status, campaign, channel, and specialization.
- Comparative charts for property types, locations, price segments, agents, and marketing channels.
- Trend analysis for monthly sales, revenue, leads, and agent performance.
- Funnel analysis to understand movement from leads through later stages of the sales process.
- Tabular/matrix views for detailed agent, location, and property-category comparisons.
- Cross-filtering through dashboard selections, where configured in the report.

## Dashboard Pages and Analysis

### 1. Property Analytics

This page provides an overview of the property inventory and its status.

**KPIs shown in the PDF:**
- Total Properties
- Available Properties
- Booked Properties
- Sold Properties
- Property Sell-Through %
- Average Property Area

**Analysis shown:**
- Property inventory status
- Property count by property type
- Property distribution by price segment
- Property inventory by city
- Inventory by BHK configuration
- Average property area by property type
- Residential versus commercial distribution
- Average property size by city

**Business questions supported:**
- How many properties are available, booked, or sold?
- Which property types or BHK configurations have the largest inventory?
- How is inventory distributed across cities and price categories?
- Which property categories have a higher average area?

### 2. Sales Analytics

This page focuses on sales volume, revenue, discounts, and target performance.

**KPIs shown in the PDF:**
- Total Revenue
- Total Sales
- Average Sale Value
- Total Discount
- Revenue YoY Growth
- Target Achievement
- Revenue per Agent
- Sales per Agent

**Analysis shown:**
- Monthly sales trend
- Monthly revenue and year-over-year growth
- Revenue by property type and city
- Top agents by revenue
- Agent sales and target-achievement table
- Revenue by price segment
- Revenue by discount category
- Average deal value by city
- Sales by payment mode
- Revenue by payment status
- Location-wise property-category breakdown

**Business questions supported:**
- How are sales and revenue changing over time?
- Which cities and property types contribute most to revenue?
- Which agents generate the highest revenue and sales?
- How does actual performance compare with agent targets?
- What are the distributions of payment modes and payment statuses?

### 3. Lead & CRM Analytics

This page tracks the lead pipeline from initial enquiry to conversion.

**KPIs shown in the PDF:**
- Total Leads
- Qualified Leads
- Site Visit Leads
- Booked Leads
- Converted Leads
- Lead Conversion %

**Analysis shown:**
- Lead conversion funnel
- Monthly lead-generation trend
- Lead conversion rate by source
- Leads by source
- Agent-wise lead and conversion table
- Lead source versus property-category breakdown
- Lead distribution by age group
- Total revenue by location
- Lead-stage distribution by city

**Business questions supported:**
- How many leads reach each stage of the pipeline?
- Which lead sources generate more leads or conversions?
- How does lead activity change month by month?
- How do lead outcomes vary by city, agent, or property type?
- At which stages might the business need to improve follow-up?

### 4. Agent Performance

This page evaluates agent productivity and contribution to business results.

**KPIs shown in the PDF:**
- Total Agents
- Total Leads
- Converted Leads
- Lead Conversion %
- Total Revenue
- Target Achievement

**Analysis shown:**
- Top agents by revenue
- Top agents by number of sales
- Monthly agent revenue trend
- Agent lead-to-sale funnel
- Sales volume by experience category
- Agent target versus actual revenue
- Agent lead conversion rate
- Agent productivity: leads versus revenue
- Agent target-achievement ranking
- Branch/city-level performance summary
- Agent-wise property-category sales breakdown

**Business questions supported:**
- Which agents contribute the most revenue and sales?
- How does agent performance compare with targets?
- Do conversion rates differ across agents or experience categories?
- How does performance vary across branches or cities?

### 5. Marketing Analytics

This page evaluates marketing investment and the leads and conversions generated by different channels and campaigns.

**KPIs shown in the PDF:**
- Marketing Spend
- Marketing Leads
- Marketing Conversions
- Marketing Conversion Rate
- Cost per Lead
- Marketing ROI

**Analysis shown:**
- Marketing spend by channel
- Leads generated by channel
- Marketing conversions by channel
- Conversion rate by channel
- Cost per lead by channel
- Marketing revenue by channel

**Business questions supported:**
- Which channels generate the most leads and conversions?
- Which channels have a higher conversion rate?
- How much does it cost to generate a lead through each channel?
- Which channels contribute more revenue relative to marketing investment?

---

## Key Metrics

The dashboard displays the following measures. Their exact formulas should be checked against the measures in the report/model before treating them as official business definitions.

| Metric | General meaning |
|---|---|
| Property Sell-Through % | Share of the relevant property inventory that has been sold |
| Average Sale Value | Average value per recorded sale |
| Revenue YoY Growth | Revenue growth compared with the corresponding prior-year period |
| Target Achievement | Actual performance compared with the assigned target |
| Lead Conversion % | Share of leads that become converted leads |
| Cost per Lead (CPL) | Marketing spend divided by the number of leads generated |
| Marketing ROI | Return generated relative to marketing investment; confirm the exact calculation used in the report |

## Tools and Technologies


- **Dashboarding:** Power BI **
- **Data preparation:** [ Power Query / Excel / Python]
- **Data storage:** [CSV / Excel / SQL database]




## Repository Structure
```text
real-estate-business-analytics/
│
├── README.md
├── dashboard/
│   └── [dashboard file, e.g. Real_Estate_Analytics.pbix]
├── data/
│   └── data files/
├── screenshots/
│   ├── property-analytics.png
│   ├── sales-analytics.png
│   ├── lead-crm-analytics.png
│   ├── agent-performance.png
│   └── marketing-analytics.png
└── documentation/

```

## Insights and Business Value

The dashboard is designed to help stakeholders:

- Monitor property inventory and sales status.
- Compare revenue and sales performance across cities and property categories.
- Track the lead pipeline and identify stages where conversion may be improving or dropping.
- Compare agent performance with targets.
- Evaluate marketing channels using leads, conversions, cost per lead, and ROI.
- Explore performance through interactive filters rather than relying only on static totals.

These are the intended uses of the dashboard. Add specific findings only after validating them against the underlying data and filter context.

