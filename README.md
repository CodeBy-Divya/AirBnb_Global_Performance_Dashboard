
# Airbnb Global Listings & Market Analysis Dashboard

An interactive Power BI dashboard analyzing Airbnb's global presence, pricing strategy, and customer satisfaction across major cities — built to answer real business and strategy questions a stakeholder would ask.

## Dataset

**Source:** [Airbnb Listings & Reviews — Maven Analytics Data Playground](https://mavenanalytics.io/data-playground/airbnb-listings-reviews)

Download the dataset from the link above and place the raw files in the `/data` folder before running the project.

## Project Workflow

This project follows a structured 6-step BI development process:

1. **Data Set** — Sourced the right dataset for the business questions being asked.
2. **Study Data Set** — Explored and understood all columns, data types, and relationships in the raw data.
3. **Questions** — Defined the key business questions to answer (client-driven, self-driven, and AI-assisted question generation).
4. **Data Cleaning** — Prepared and cleaned the data for graph-building (handled nulls, duplicates, formatting issues).
5. **Data Modeling** — Built relationships between tables to support cross-filtering and accurate aggregations.
6. **Visualisation** — Built the dashboard: wrote DAX measures, chose appropriate chart types, and designed the layout.

## What Questions Does This Dashboard Answer?

### Big Picture / Overview
*(Before diving into charts, what should a stakeholder know?)*
- How big is Airbnb's presence across major global cities?
- How has Airbnb grown over time and where did it peak?
- Which cities contribute most to Airbnb's overall business?
- Are listings concentrated or evenly spread across cities?

### Market Share by City
*(Business + strategy questions)*
- Which cities dominate Airbnb listings globally?
- Are a few cities driving most of the supply?
- How much of the total market do top cities control?
- What is the cumulative contribution of cities like Paris, NYC, and Sydney?
- Is Airbnb supply fragmented or highly concentrated?

> **This answers:** *"Where should Airbnb focus its growth, regulation, or marketing efforts?"*

### Property Type & Pricing
*(Customer behavior + pricing logic)*
- Which property types are most commonly listed?
- Are hotel rooms more expensive than Airbnb stays?
- Why might travelers prefer Airbnb over hotels in certain cities?
- Does pricing explain higher adoption in cities like Paris?

> **This explains:** *why Airbnb wins in certain markets.*

### Ratings & Customer Satisfaction
*(Quality & experience questions)*
- Which cities deliver the best overall guest experience?
- Which cities are underperforming on ratings?
- Are low ratings driven by cleanliness, value for money, or communication?
- Is high supply always equal to high quality?

> **This answers:** *"Where is Airbnb doing well and where is it failing customers?"*

## Tools & Tech Stack
- **Power BI** — dashboard, DAX measures, data modeling
- **Excel / Power Query** — data cleaning and transformation
- *(add SQL/Python here if you used them for cleaning/prep)*



