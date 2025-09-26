# London Airbnb Profit Maximizer: Data-Driven Pricing & Revenue Strategy

## Overview
The London short-term rental market is highly competitive. For hosts, setting an optimal price and understanding which factors truly drive bookings and revenue is complex and often based on guesswork.  

This project uses advanced data science techniques on a dataset of **57,000+ cleaned London Airbnb listings** to deliver a comprehensive, data-backed strategy for hosts to:  
- Maximize Return on Investment (ROI)  
- Achieve competitive superiority  
- Identify key pricing, revenue, and location drivers  

---

## Key Business Insights

### 1. The Quantified Superhost Advantage
- **Pricing Power:** Superhosts charge **9.1% higher prices** than Non-Superhosts  
- **Revenue Growth:** Superhosts earn **~125% more annual revenue**  
- **Why:** Superhosts offer more amenities (+32%) and receive double the monthly review volume  

### 2. Dual Determinants of Listing Performance
| Financial Metric | Primary Drivers | Actionable Takeaway |
|------------------|-----------------|---------------------|
| **Price**        | Property size, capacity, and location (latitude/longitude) | Maximize guest capacity – the single most important driver of pricing |
| **Revenue**      | Guest experience: number of reviews and review frequency | Focus on guest satisfaction and review generation to unlock higher revenue |

### 3. High-Yield Geographic "Sweet Spots"
- Traditional high-price areas such as Kensington and Westminster exist.  
- However, analysis of price-to-demand revealed that **Islington** is a top-performing neighborhood, balancing strong pricing with high booking frequency.  
- This makes Islington an ideal investment target for new and existing hosts.  

---

## Methodology
This project followed a rigorous analytics pipeline:

- **Data Engineering:** Initial dataset of 89,343 listings (88 features) was cleaned to 57,941 listings (54 features), focusing on handling extreme outliers and feature reduction.  
- **Statistical Validation:** Two-sample hypothesis tests (Welch's t-test) confirmed statistically significant differences between Superhosts and Non-Superhosts across critical metrics (Price, Revenue, Amenities, Reviews).  
- **Predictive Modeling:** Two Random Forest Regressor models were built and trained to forecast:
  - Optimal price (R-squared: 0.74)  
  - Expected annual revenue (R-squared: 0.78)  
  These enabled feature importance analysis and actionable insights.  

---

## Deliverables & Stakeholders
The final insights were delivered as a strategic resource for direct business application:

- **Stakeholders:** New Hosts, Existing Hosts seeking optimization, and Property Management Firms.  
- **Final Product:** A dynamic Power BI Dashboard presenting these findings visually.  
  - Allows hosts to apply recommendations instantly.  
  - Supports strategic planning around guest capacity, amenity investment, and localized pricing strategies.  

---

## Tech Stack
- **Language:** Python  
- **Analytics & ML:** pandas, NumPy, scikit-learn (Random Forest), SciPy (Hypothesis Testing)  
- **Visualization & Reporting:** Power BI  

---
