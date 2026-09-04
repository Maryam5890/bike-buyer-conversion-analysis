**Bike Buyer Conversion Analysis**

An end-to-end Excel project analyzing customer data for a bike retailer, built to answer a
simple business question: who actually buys bikes, and what separates a buyer from a
non-buyer?


**What’s in this project**

Raw data — 1,026 customer records: demographics (age, gender, marital status,
education, income, occupation), household info (children, home ownership, cars),
commute distance, region, and whether they purchased a bike.
Cleaned working sheet — data validated and enriched with a derived Age Range
column (Young / Middle Age / Old Buyer) using nested IF logic, so age can be analyzed
as a category instead of just a raw number.

Pivot tables — cross-tabs of average income by gender and purchase outcome, plus
supporting breakdowns by region, education, and marital status.

Interactive dashboard — a single-page dashboard combining bar, line, and pie charts,
with three linked slicers (Marital Status, Region, Education) so a viewer can filter every
chart at once without touching a single formula.


**Why this project**

Most sample dashboards just decorate data. This one is built to be interrogated — the
slicers let you slice the customer base by segment and watch the averages shift in real time,
which is closer to how a stakeholder actually uses a report in a meeting.

**Skills demonstrated**

Data cleaning and validation in Excel
Nested conditional logic (IF) for feature engineering
PivotTables and PivotCharts
Cross-filtering with slicers connected to multiple pivot tables
Dashboard layout and design for non-technical end users

**A note on the data:**
This dataset is a well-known public bike-buyer dataset used for
BI/analytics practice. Nothing in it is proprietary or personal.

**Key Insights & Business Recommendations**

Women convert better than men (41.1% vs. 32.4%) — marketing spend aimed at male
customers may be underperforming and worth re-evaluating.
Single customers convert far more than married customers (54.1% vs. 42.9%) —
campaigns built around individual lifestyle/independence may resonate more than
family-oriented messaging.
Pacific region outperforms North America (58.9% vs. 43.3% conversion) — regional
demand differs sharply, so a one-size-fits-all sales strategy is leaving conversions on
the table in underperforming regions.
Education level matters — customers with only partial high school convert far worse
(26.3%) than every other education group, suggesting this segment may need a
different offer, price point, or messaging entirely.
Business takeaway: the highest-converting customer profile is a single woman in the
Pacific region — that’s the segment to prioritize in targeted campaigns, while North America
and lower-education segments need a revised approach rather than the current one.

**Possible next steps**

Break out commute distance and cars-owned as their own filterable segments, since
they’re currently in the raw data but not surfaced on the dashboard
Test whether income or age is the stronger predictor of purchase by comparing
conversion rates across both dimensions side by side
