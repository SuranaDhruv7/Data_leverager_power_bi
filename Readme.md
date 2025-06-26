# 📊 Project1 Power BI Dashboard

## 📝 Overview

This Power BI project (`Project1.pbix`) is a comprehensive, interactive data visualization report built to deliver deep insights through elegant design, smart data modeling, and advanced DAX measures. The dashboard is crafted with meticulous attention to detail, emphasizing usability, storytelling, and interactivity.

---

## ⏱️ Time Taken

| Phase                     | Description                                            |
|--------------------------|---------------------------------------------------------|
| Data Extraction & Prep   | Loading & cleaning datasets, checking integrity
| Data Modeling            | Creating star schema, relationships, hierarchies
| DAX Measures             | Writing custom KPIs, ratios, time intelligence
| Visualization            | Designing report pages, charts, KPIs, slicers           
| Interactivity & Filters  | Drill-throughs, bookmarks, tooltips
| Testing & QA             | Validating results, performance tuning                  
| 📌 **Total**             |                                                        

---

## 🗂️ Project Structure

This `.pbix` file consists of several structured components:

### 🔹 1. Report Pages
Each page is designed with user experience in mind:
- **Homepage** – Navigation and high-level KPIs
- **Sales Overview** – Key metrics: Revenue, Quantity, Returns
- **Regional Analysis** – Sales by region with maps & filters
- **Customer Insights** – Segmentation by behavior or demographics
- **Time Intelligence** – Year-over-Year, Month-over-Month changes
- **Drill-through Page** – Focus view by clicking on a data point

### 🔹 2. Data Model
Built using a clean **star schema**:
- **Fact Tables**:
  - `Sales_Fact`: Quantities, revenue, return info
- **Dimension Tables**:
  - `Date_Dim`: Calendar, month, year
  - `Product_Dim`: Category, sub-category, brand
  - `Customer_Dim`: Region, segment, age group
  - `Region_Dim`: Country, state
- Relationships configured with appropriate cardinality and cross-filtering.

### 🔹 3. DAX Measures
Custom measures were created for in-depth analysis:
- **Time Intelligence**: YTD, MTD, MoM, YoY growth
- **Performance Metrics**: Profit %, Return Rate, Average Basket Size
- **Ranking Logic**: Top N Products/Regions
- **Conditional Formatting Rules**

### 🔹 4. Visuals
Crafted using a variety of charts and slicers:
- Bar & Column Charts
- Line & Area Graphs
- Cards, KPIs, and Multi-row Cards
- Matrix Tables with dynamic drill-down
- Smart slicers (date, product, region)

### 🔹 5. Navigation & Interactivity
- **Drill-throughs** for detail-level pages
- **Page tooltips** for compact info on hover
- **Bookmarks & Buttons** for page navigation
- **Responsive Layouts** for different screen sizes

### 🔹 6. Security & Optimization
- Role Level Security (RLS) settings (via `SecurityBindings`)
- Performance tweaks using optimized DAX & filters
- Metadata and Version control included

---

## 🚀 Key Highlights

- ✅ Built with enterprise-grade modeling standards
- 📈 High-performance calculations using advanced DAX
- 🧠 Easy to understand yet powerful dashboards
- 🌍 Region-wise and customer-wise segmentation
- 🕐 Fully functional time intelligence framework
- 🔍 Drill-down and drill-through features to explore deeply

---

## 📦 Files Inside

> Unpacked `Project1.pbix` reveals the following critical files:

| File               | Description                                |
|--------------------|--------------------------------------------|
| `Report`           | Visual layout and report page definitions  |
| `DataModel`        | Data schema, tables, DAX logic             |
| `DiagramLayout`    | Data model diagram view                    |
| `Metadata`         | Descriptions, formatting, properties       |
| `Settings`         | Report settings like theme, locale         |
| `SecurityBindings` | Security roles and access control config   |

---

## 🔄 Future Improvements

- Add Q&A visuals using natural language query
- Integrate mobile layout view
- Enhance storytelling with tooltip report pages
- Use Azure Analysis Services or Direct Query for live data

---

## 📬 Feedback

Feel free to reach out or fork the project for collaboration or improvements. This dashboard was built to be scalable, efficient, and insightful.

---