# ab_project

#### This project was made by Samuel Oliveira.

## 1. Business Problem.

The Electronic House is an online retail store selling computer products for homes and offices. Customers can buy products such as mice, monitors, keyboards, computers, laptops, HDMI cables, headphones, webcam cameras, among others, through an online platform and receive these products at the comfort of their homes.

The UX design team has been working on a new sales page aiming to increase the conversion rate of one of the store's product, a bluetooth keyboard. The product manager states that the conversion rate of the current sales page has been 13% on average over the past year. The goal is to increase the conversion rate by 2%. Thus, the new sales page would be deemed successful if it achieves a conversion rate of 15%. The bluetooth keyboard is sold for R$ 4,500.00, either as a lump sum or in 12 interest-free installments.

Before replacing the old sales page with the new one, the product manager wants to test the new page's effectiveness on a smaller customer group to reduce conversion drop risks if the new page underperforms the current one.

## 2. Business Assumptions.

The hypothesis is that the new sales page will increase the sales conversion rate by 2%.

## 3. Solution Strategy

The strategy to address this challenge was:

**Step 01. Data Description:**

The data was loaded and an initial description was performed to understand the structure and format of the data. The dataset consists of 294,478 rows and 5 columns.

**Step 02. Feature Engineering:**

Conversion rates were calculated for the control and treatment groups. Moreover, the necessary sample size for the A/B test was determined based on established testing parameters. The total number of emails to send was 94,380, divided evenly into control and treatment groups of 47,190 each. The total sample size for the A/B test was 9,438, divided evenly into control and treatment groups of 4,719 each.

**Step 03. Data Filtering:**

Users who appeared in both groups were removed to avoid contamination of the results.

**Step 04. Exploratory Data Analysis:**

An analysis of the control and treatment groups was carried out, and the conversion rate was calculated for each group. The conversion rate for the control group was approximately 11.55%, while the conversion rate for the treatment group was around 12.91%.

**Step 05. Data Preparation:**

The data was prepared for the hypothesis test.

**Step 06. Feature Selection:**

The relevant features for the hypothesis test were selected.

**Step 07. Statistical Hypothesis Testing:**

A hypothesis test was conducted to determine if the conversion rate of the new page was significantly different from the conversion rate of the current page. The p-value from the test was approximately 0.081, leading to the decision to fail to reject the null hypothesis.

**Step 08. Result Interpretation:**

The results of the hypothesis test were interpreted, and the decision was made to either accept or reject the null hypothesis. The Gross Merchandise Volume (GMV) for the period was R$ 167,713,650.00, with the new sales page estimated to increase the GMV to R$ 193,515,750.00, indicating an expected lift of 15.38%.

# LICENSE

# All Rights Reserved - Comunidade DS 2022
