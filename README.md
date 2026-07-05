# Netflix Content Analysis Dashboard (Power BI)

A Power BI project analyzing a Netflix content dataset to explore patterns in content type, genre, directors, ratings, and country of origin — combined with a DAX practice page for runtime-based calculations.

## 📊 Overview

This dashboard provides a quick, interactive view into Netflix's content library, helping answer questions like:
- How is content split between Movies and TV Shows?
- Which genres (primary categories) have the most titles?
- Which directors have the most rated content, and how are ratings distributed across them?
- How does the content mix change when filtered by country?

The project also includes a secondary "Brainstorming" page used to practice writing and validating custom DAX measures around content runtime.

## 🗂️ Dataset

The report is built on a single flat table (`Sheet1`) with fields including:

| Column | Description |
|---|---|
| `show_id` | Unique identifier for each title |
| `type` | Content type — Movie or TV Show |
| `Primary_Category` | Primary genre/category of the title |
| `director` | Director of the title |
| `rating` | Content rating (e.g., TV-MA, PG-13) |
| `country` | Country of origin |

## 📄 Report Pages

### 1. Netflix Content Analysis Dashboard
The main analytical view, featuring:
- **Pie Chart** — Distribution of content by `Type` (Movie vs TV Show)
- **Bar Chart** — Count of titles by `Primary_Category`, showing genre popularity
- **Bar Chart** — Count of `rating` values broken down by `director`
- **Slicer** — Filter the entire page by `country`

### 2. Brainstorming
An exploratory page used to test and validate DAX measures:
- A director-specific runtime calculation
- A measure identifying the highest-runtime TV Show
- A measure returning that show's duration

## 🛠️ Tools & Techniques
- **Power BI Desktop** — report design and data modeling
- **DAX** — custom measures for runtime and ranking calculations
- **Power Query** — data load and shaping from source file

## 🎯 Purpose

This project was built as part of a hands-on Power BI learning path, focused on:
- Practicing core visual types (pie charts, bar charts, slicers, cards)
- Writing and testing DAX measures beyond simple aggregations
- Structuring a report with a clear "presentation" page separate from a "working/testing" page

## 🚀 How to Use
1. Download `Animesh_netflixproject_Industrial2.pbix`
2. Open in Power BI Desktop
3. Use the country slicer on Page 1 to filter the dashboard
4. Check Page 2 for the DAX runtime measures in action

## 📌 Notes
This is an early/lean iteration of the Netflix analytics concept, focused on a single flat table and a small set of core visuals — a foundation that can be extended with additional pages (e.g., release-year trends, genre-over-time analysis, or a full data model with normalized tables).

---
*Part of a self-directed Power BI / data analytics portfolio.*
