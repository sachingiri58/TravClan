# Hotel Bookings Analysis - Assignment Submission
## TravClan Business Analyst Internship

**Submitted By:** Candidate  
**Date:** February 2, 2026  
**Assignment:** Technical Analysis - Hotel Bookings Dataset

---

## 📦 Submission Package Contents

### 1. Analysis Code
- **hotel_analysis.ipynb** - Complete Jupyter notebook with data analysis
  - Data exploration and preparation
  - Statistical analysis
  - Root cause identification
  - Business recommendations
  - All visualizations generated programmatically

### 2. Presentation
- **Hotel_Bookings_Analysis_Presentation.pptx** - 9-slide professional presentation
  - Executive summary with key metrics
  - Three major trends identified
  - Root cause analysis
  - Strategic recommendations
  - Implementation roadmap
  - Projected impact analysis

### 3. Visualizations
Generated automatically by the notebook (8 charts total):
- booking_status_overview.png
- booking_channel_analysis.png
- room_star_analysis.png
- cancellation_deep_dive.png
- temporal_trends.png
- city_analysis.png
- promotional_pricing_analysis.png
- root_cause_analysis.png

### 4. Data Exports
CSV files with detailed analysis:
- channel_performance.csv
- room_type_performance.csv
- star_rating_performance.csv
- city_performance.csv
- monthly_trends.csv

---

## 🎯 Key Findings Summary

### Dataset Overview
- **Total Bookings:** 30,000 transactions
- **Date Range:** April 2024
- **Status Breakdown:**
  - Confirmed: 72.2% (21,672 bookings)
  - Cancelled: 20.2% (6,070 bookings)
  - Failed: 7.5% (2,258 bookings)

### Three Major Trends Identified

#### 1. **Channel Performance Disparity**
- Web bookings show 18.9% cancellation rate (BEST)
- Mobile App bookings: 19.9% cancellation
- Travel Agent bookings: 25.8% cancellation (WORST)
- **Gap:** 6.9 percentage points between best and worst

#### 2. **Cancellation Risk Factors**
- **Lead Time Impact:**
  - Cancelled bookings: 42.3 days average lead time
  - Confirmed bookings: 40.4 days average lead time
  - Longer booking windows = higher cancellation risk
  
- **Payment Method Risk:**
  - Highest risk: PayPal (21.4%)
  - Lowest risk: Credit Card (19.7%)
  
- **Stay Type Pattern:**
  - Business travel: 21.0% cancellation
  - Leisure travel: 19.9% cancellation

#### 3. **Revenue Opportunities**
- **Lost Revenue:** ₹179.66M from cancellations
- **Room Upgrade Potential:** 15% conversion rate could generate ₹3M+
- **Dynamic Pricing:** 5% revenue increase opportunity
- **Average Markup:** 30.9% (room for optimization)

---

## 🔍 Root Cause Analysis

### Why Cancellations Happen:
1. **No Financial Penalty:** Zero deposit requirement makes cancellation cost-free
2. **Long Planning Windows:** 40+ day lead times reduce commitment
3. **Agent Incentive Misalignment:** Commission structure doesn't penalize cancellations
4. **Business Travel Flexibility:** Corporate bookings have inherent uncertainty

### Why Channels Differ:
1. **Direct vs Indirect:** Web users show higher intent and ownership
2. **Agent Economics:** Agents prioritize volume over completion
3. **User Experience:** Mobile app users may be more price-sensitive

### Temporal Patterns:
- Relatively stable cancellation rates across months
- No significant seasonal variation observed
- Day-of-week booking patterns show minor variance

---

## 💡 Strategic Recommendations

### Priority 1: Reduce Cancellations (Target: -30%)
**Actions:**
1. Graduated deposit structure based on lead time
   - >45 days: 30% non-refundable deposit
   - 30-45 days: 20% deposit
   - <30 days: 10% deposit

2. Payment method incentives
   - 2% extra cashback for Credit Card/Bank Transfer
   - Payment plans for bookings >₹20,000

3. Channel optimization
   - Agent performance tracking with commission holdback
   - Focus marketing on Web channel

**Expected Impact:** ₹53.9M revenue protection

### Priority 2: Improve Profitability (Target: +15% revenue)
**Actions:**
1. Dynamic pricing
   - Surge pricing for peak days/cities
   - Last-minute booking premiums
   - Target markup increase from 30.9% to 33%

2. Upselling programs
   - Room upgrade campaigns (Standard → Deluxe)
   - Add-on services marketplace
   - Potential: 4,500 upgrades @ ₹3,000 = ₹13.5M

3. Premium tier
   - TravClan Elite membership (₹999/year)
   - Benefits: 5% discount, priority support, 1 free cancellation
   - Target: High-value customers (top 25%)

**Expected Impact:** ₹98.4M additional revenue

### Priority 3: Increase Repeat Bookings (Target: +25%)
**Actions:**
1. Loyalty program
   - Points-based: 1 point per ₹100 spent
   - Tiered benefits (Silver/Gold/Platinum)
   - Redemption: 1000 points = ₹500

2. Post-stay engagement
   - Day 3: Review request + ₹200 voucher
   - Day 30: "We miss you" + 10% discount
   - Day 90: Personalized recommendations

3. Referral program
   - Give ₹500, Get ₹500
   - Target: 10% customer acquisition via referrals

**Expected Impact:** ₹77.3M from increased repeat business

---

## 📅 90-Day Implementation Roadmap

### Phase 1: Quick Wins (Days 1-30)
- Week 1-2: Launch deposit policy
- Week 2-3: Implement payment incentives
- Week 3-4: Set up email campaigns

### Phase 2: Core Programs (Days 31-60)
- Week 5-6: Launch loyalty program
- Week 6-7: Implement dynamic pricing
- Week 7-8: Start agent performance tracking

### Phase 3: Advanced Features (Days 61-90)
- Week 9-10: Deploy upselling system
- Week 10-11: Launch premium membership
- Week 11-12: Start referral program

### Success Metrics (Track Weekly)
- Cancellation rate: Target <14.2%
- Average booking value: Target >₹17,500
- Repeat booking rate: Target >25%
- Revenue per booking: Target +15%
- Customer satisfaction: Target >4.5/5

---

## 📊 Projected 6-Month Impact

| Initiative | Impact |
|-----------|--------|
| Cancellation Reduction (30%) | ₹53.9M |
| Profitability Improvements (15%) | ₹98.4M |
| Repeat Bookings Increase (12.5%) | ₹77.3M |
| **TOTAL REVENUE INCREASE** | **₹229.6M (+35.0%)** |




*This analysis was conducted independently using Python, Jupyter Notebook, and standard data science libraries.*
