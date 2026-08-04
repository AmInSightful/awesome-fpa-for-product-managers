# Forecast Model Template

A practical forecasting framework for Product Managers to estimate future product performance, revenue impact, resource needs, and business outcomes.

Forecasting helps PMs answer:

- What is likely to happen?
- What assumptions drive the outcome?
- Where are the biggest uncertainties?
- How should we allocate resources?

---

# Forecasting Framework

```
Business Drivers

↓

Assumptions

↓

Forecast Model

↓

Scenarios

↓

Decision
```

---

# 1. Forecast Overview

## Forecast Name

Example:

```
Enterprise AI Product Revenue Forecast
```

---

## Forecast Period

Define:

- Monthly
- Quarterly
- Annual
- Multi-year

Example:

```
Jan 2026 - Dec 2028
```

---

## Purpose

Examples:

- Product investment decision
- Annual planning
- Resource allocation
- Revenue planning
- Capacity planning

---

# 2. Driver-Based Forecasting

Strong forecasts are built from business drivers.

Avoid:

```
Next year revenue = +20%
```

Prefer:

```
Customers

×

Conversion

×

Price

×

Retention

=

Revenue
```

---

# 3. Customer Forecast

## Starting Customers

Current customer base.

---

## New Customers

Drivers:

- Marketing campaigns
- Sales pipeline
- Product-led growth
- Market expansion

Formula:

```
New Customers

=

Leads

×

Conversion Rate
```

---

## Churn Forecast

Formula:

```
Churned Customers

=

Customers

×

Churn Rate
```

---

## Ending Customers

Formula:

```
Ending Customers

=

Starting Customers

+

New Customers

-

Churned Customers
```

---

# 4. Revenue Forecast

## Subscription Revenue

Formula:

```
Customers

×

Average Revenue Per Customer
```

---

## Usage Revenue

For consumption products:

```
Usage Volume

×

Price Per Unit
```

Examples:

- API calls
- Transactions
- Storage
- Compute

---

## Expansion Revenue

Sources:

- Upselling
- More seats
- Higher usage
- New products

---

# Total Revenue

Formula:

```
New Revenue

+

Expansion Revenue

-

Lost Revenue

=

Net Revenue
```

---

# 5. Cost Forecast

## Product Costs

Include:

- Engineering
- Product
- Design
- Data

---

## Infrastructure Costs

Include:

- Cloud
- AI models
- Storage
- Networking

---

## Go-To-Market Costs

Include:

- Sales
- Marketing
- Customer Success

---

# 6. Scenario Planning

Never rely on a single forecast.

Create:

```
Best Case

Base Case

Worst Case
```

---

# Best Case

Assumptions:

- Higher adoption
- Faster growth
- Lower churn
- Better margins

Example:

```
Growth: +50%

Churn: 2%
```

---

# Base Case

Most realistic scenario.

Based on:

- Historical data
- Market research
- Current pipeline

---

# Worst Case

Assumptions:

- Lower demand
- Higher costs
- Competitive pressure

---

# Scenario Table

| Scenario | Customers | Revenue | Margin |
|---|---:|---:|---:|
| Best Case | 50K | $10M | 80% |
| Base Case | 35K | $7M | 75% |
| Worst Case | 20K | $4M | 65% |

---

# 7. Forecast Accuracy

Track:

## Forecast Error

Formula:

```
Actual

-

Forecast
```

---

## Accuracy Rate

Formula:

```
1 -

|Actual - Forecast|

/

Actual
```

---

# 8. Product Forecast Examples

---

# New Feature Forecast

Estimate:

Inputs:

- Eligible users
- Adoption rate
- Conversion
- Revenue impact

Example:

```
1M users

×

5% adoption

×

$20/month

=

$1M monthly revenue
```

---

# AI Product Forecast

Include:

## Revenue

- Subscribers
- Usage
- Enterprise contracts

---

## Costs

- Model inference
- Compute
- Data processing

---

## Economics

Track:

- Cost per request
- Revenue per user
- AI gross margin

---

# Marketplace Forecast

Drivers:

## Supply

- Providers
- Availability
- Capacity

## Demand

- Customers
- Orders
- Transactions

## Economics

- GMV
- Take rate
- Contribution margin

---

# 9. Forecast Review Questions

## Assumptions

- Are assumptions realistic?
- What evidence supports them?

---

## Drivers

- Which variables matter most?
- What can change the outcome?

---

## Risks

- What could make this wrong?
- What should we monitor?

---

# 10. Executive Forecast Summary

Use this format:

```
Forecast:

Period:

Key Assumptions:

Expected Outcome:

Main Risks:

Decision Needed:
```

---

# PM Forecasting Checklist

☐ Clear forecast objective

☐ Key drivers identified

☐ Assumptions documented

☐ Multiple scenarios created

☐ Risks analyzed

☐ Actual results tracked

☐ Model updated regularly

---

# Recommended Tools

Build forecasts using:

- Excel
- Google Sheets
- SQL
- Python
- Power BI
- Tableau

---

# Key Takeaways

Forecasting is not about predicting the future perfectly.

It is about creating better decisions under uncertainty.

Strong Product Managers use forecasts to connect:

```
Product Strategy

+

Business Assumptions

+

Financial Outcomes
```
