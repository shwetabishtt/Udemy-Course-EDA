# Udemy Courses Analysis

## Introduction
The **Udemy Courses Analysis** project provides an in-depth exploration of Udemy’s diverse course offerings, focusing on key insights around subjects, pricing strategies, and subscriber engagement. Utilizing Python and data analysis libraries like Pandas, the analysis aims to highlight trends and patterns that can guide content creation and marketing strategies on the platform.

## Dataset Overview
The project begins by loading the **Udemy Courses dataset** (`Udemy Courses.csv`) into a Pandas DataFrame. This dataset covers a wide range of subjects, including:
- Musical Instruments
- Business Finance
- Graphic Design
- Web Development

Each record includes information on course title, subject, price, subscriber count, and more.

## Key Analyses

### 1. Subjects and Course Count
An initial exploration identifies the unique subjects offered by Udemy. Among them, **Web Development** is revealed as the subject with the highest course count, totaling **1,200 courses**.

### 2. Pricing Analysis
The dataset is segmented by **course pricing**:
- Distinguishing between **free and paid courses**, where **3,372 courses** are paid.
- A list of available free courses is also generated, offering insight into Udemy's freemium model.

### 3. Top and Least Selling Courses
By examining subscriber counts, the analysis pinpoints:
- **Top-selling courses** with the highest subscriber engagement.
- **Least-selling courses** to understand areas with low engagement or niche audiences.

### 4. Subject-Specific Price Filters
To offer a focused view:
- All **Graphic Design courses priced below $100** are displayed.
- **Web Development courses priced above $50** are filtered to analyze premium course offerings within this category.

### 5. Python-Related Courses
Using keyword filtering, the analysis isolates **Python-related courses** to examine the language's popularity on Udemy and provide insights into demand for programming content.

### 6. Courses Published in 2015
Lastly, a time-based filter highlights courses published in **2015**, totaling **1,014 courses** from that year. This section explores trends and engagement levels for courses launched during this period.

## Conclusion
The **Udemy Courses Analysis** provides valuable insights into Udemy's content landscape, from popular subjects to pricing and engagement patterns. These findings can assist in optimizing course offerings, refining pricing strategies, and identifying areas of high demand. This analysis serves as a resource for educators and marketers aiming to maximize reach and effectiveness on the Udemy platform.
