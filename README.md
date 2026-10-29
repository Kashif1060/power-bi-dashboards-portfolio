# Power BI Dashboard Portfolio

A collection of **6 interactive Power BI dashboards** I designed to practice turning raw data into clear business insights. Each dashboard starts with a business question and uses KPI cards, interactive filters, and visuals chosen to answer that question quickly.

**Tools:** Power BI Desktop
**Skills practiced:** Data modeling, DAX measures, Power Query data cleaning, interactive design (slicers, KPI cards), data storytelling

> **Note:** The datasets used are sample or practice data. They do not contain any confidential or employer information.

---

## Overview

| # | Dashboard | Domain | Main question |
|---|-----------|--------|---------------|
| 1 | Hospital Operations | Healthcare | Where do patients and costs concentrate? |
| 2 | HR Analytics | Human Resources | How are people, pay, and payroll distributed? |
| 3 | Online Store | E-commerce | Which products, cities, and regions drive sales and profit? |
| 4 | Sales Performance | Retail | Which categories, regions, and months lead sales? |
| 5 | Student Performance | Education | How do students perform across departments? |
| 6 | Super Store Sales | Retail | How do sales and profit vary by segment, shipping, and state? |

---

## 1. Hospital Operations Dashboard

**Business question:** Where do patient volume and treatment costs concentrate, and how many visits are completed?

**KPIs:** 500 total patients | Rs1.3M total cost

**Visuals:** Visit status, patients by gender, treatment cost by city, patient distribution by department, treatment cost by department
**Interactivity:** City and Department slicers

**Key insights:**
- Only **61%** of visits were completed, while **20%** were cancelled and **19%** were no-shows.
- **Dermatology** has the most patients (94) but one of the lowest costs (Rs129K).
- **Cardiology** is the most expensive department (Rs361K) despite having fewer patients than Dermatology.
- **Sukkur** has the highest treatment cost by city (Rs299K), followed by Lahore (Rs291K).

---

## 2. HR Analytics Dashboard

**Business question:** How are employees, salaries, and payroll distributed across departments, cities, and roles?

**KPIs:** 40 employees | Average performance 4 | Average salary Rs77K | Total payroll Rs3M

**Visuals:** Employees by department, employees by gender, average salary by department, employees by city, monthly salary by job title

**Key insights:**
- **Finance** has the highest average salary (Rs85K), while **Operations** has the lowest (Rs70K).
- **Hyderabad** and **Karachi** each have 11 employees, together holding more than half of the workforce.
- The workforce is evenly split by gender (50% male, 50% female).
- The **Finance Manager** is the highest-paid role (Rs125K per month), followed by the HR Manager (Rs120K).

---

## 3. Online Store Dashboard

**Business question:** Which products, categories, cities, and payment methods drive sales and profit?

**KPIs:** Total sales Rs2M | Total profit Rs258K | 30 orders | 239 units sold | Average order value Rs71K

**Visuals:** Profit by region, sales by product, sales over time, sales by category, sales by payment method, sales by city, profit by city

**Key insights:**
- **Electronics** accounts for roughly 70% of total sales, led by Laptops (Rs510K) and Smartphones (Rs450K).
- **Karachi** leads in both sales (Rs929K) and profit (Rs97K).
- **Sindh** contributes **64%** of profit, far ahead of Punjab (22%) and Islamabad (14%).
- **Card** is the most used payment method (48%), followed by Online (34%) and Cash (18%).

---

## 4. Sales Performance Dashboard

**Business question:** Which categories, regions, customer segments, and months generate the most sales?

**KPIs:** 400 orders | Total sales 135K | 158 customers | 867 units sold | Average order value 338

**Visuals:** Sales over time (2024), sales by region, sales by month, sales by category, sales by customer segment, top products table

**Key insights:**
- **Electronics** drives about three-quarters of sales (100K of 135K).
- **June** is the peak month (22K), followed by July (19K). **November** is the weakest (5K).
- **Oceania** (29K) and **Asia** (28K) are the top regions.
- **Regular** customers contribute the most sales (59K), while **VIP** customers contribute the least (7K).
- **Laptop Pro 15** is the top product by sales (46K from 48 units).

---

## 5. Student Performance Dashboard

**Business question:** How do students perform across departments, and how do attendance and study habits relate to results?

**KPIs:** 30 students | Highest score 97 | Lowest score 61 | Average score 81 | Average attendance 84 | Average study hours 15

**Visuals:** Students by department, average score by department, average attendance by department, students by gender, average score by semester

**Key insights:**
- Performance is consistent across departments: **Software Engineering** averages 82, while **Computer Science** and **Information Technology** average 81.
- **Software Engineering** and **Computer Science** have the highest average attendance (85).
- Students are evenly split across the three departments (33% each) and by gender (50% each).
- Scores range from 61 to 97, showing a wide gap between the lowest and highest performers.

---

## 6. Super Store Sales Dashboard

**Business question:** How do sales and profit vary by customer segment, shipping mode, payment mode, product category, and location?

**KPIs:** Sales 445K | Quantity 6K | Profit 59K | Average delivery 103

**Visuals:** Monthly sales by year, monthly profit by year, sales by segment, sales by ship mode, sales by payment mode, sales and profit by state (map), sales by sub-category, sales by category
**Interactivity:** Region slicer (Central, East, South, West)

**Key insights:**
- Sales grew from **2019 to 2020**, showing a clear upward trend.
- **Consumer** is the largest segment (48%), followed by Corporate (30%) and Home Office (22%).
- **Standard Class** is the most used ship mode (71K in sales).
- **Cash on Delivery** is the most common payment mode (41%), ahead of Online (36%) and Cards (23%).
- **Office Supplies** and **Technology** each generate about 0.16M, ahead of Furniture (0.13M).

---

## Repository Structure

```
powerbi-dashboard-portfolio/
├── README.md
├── screenshots/        # Dashboard preview images
└── dashboards/         # Power BI (.pbix) files
```

## How to Open the Dashboards

1. Download the `.pbix` file from the `dashboards` folder.
2. Open it with [Power BI Desktop](https://powerbi.microsoft.com/desktop/) (free for Windows).
3. Use the slicers and filters to explore the data.

## About Me

I'm [Your Name], a data analyst focused on building clear, decision-focused dashboards.

- LinkedIn: [your LinkedIn link]
- Email: [your email]

Feedback is welcome. If you have suggestions for improving any of these dashboards, feel free to open an issue or message me.
