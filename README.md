**Quantium Chips Customer Analytics** 

Quantium, a leading data analytics company, has provided retail transaction data from a client to analyze customer purchasing behavior for chip products. The ultimate goal is to assist Julia, the Category Manager, in preparing for a strategic category review with insights backed by data.

Key business questions:
Who buys chips, and what drives their purchasing behavior?

How can we segment customers based on their spending patterns?

What insights can influence strategic retail decisions?

**Objective**

To clean, explore, and derive actionable insights from transactional data to support a data-driven commercial recommendation. This task focuses on:

Understanding current purchasing trends

Profiling customer segments

Extracting and engineering key product features

**Project Workflow**

**1.Data Loading & Initial Checks**

Loaded the transaction-level CSV dataset

Checked data types, null values, and column consistency

Identified a few format inconsistencies (e.g., units, casing)

**2.Data Cleaning**

Removed rows with missing product names or customer IDs

Corrected inconsistent formats

Filtered out clearly erroneous or outlier values (e.g., extreme prices)

**3.Feature Engineering**

Extracted BRAND from PROD_NAME using regex patterns (e.g., first capitalized word)

Parsed PACK_SIZE by identifying numeric values followed by g or G

Created new columns for brand and packet size to enable grouped analysis

**4.Exploratory Data Analysis (EDA)**

Summarized the number of products by brand and pack size

Identified top-selling chip brands and most common pack sizes

Visualized spending patterns across brands and product categories

Prepared data for customer-level analysis in next phases

**Key Insights (Initial Findings)**

A small number of brands dominate chip sales

Pack sizes vary widely — 175g and 150g are among the most popular

Pricing outliers exist, possibly due to multi-pack deals or mislabels

Brand names were inconsistently formatted in the raw data — cleaning was essential

Customers appear to have strong brand loyalty (to be explored further in segmentation)

**Final Insights & Recommendation**

After performing exploratory analysis and deriving meaningful product-level features (such as brand and pack size), we combined the transaction data with customer segment information to understand who buys chips and what drives their behavior.

**Key Findings:**
Top 3 contributing segments to chip sales:

Budget – Older Families

Mainstream – Young Singles/Couples

Mainstream – Retirees

The higher total spend from Mainstream – Young Singles/Couples and Mainstream – Retirees was not due to higher spend per transaction, but rather because there are more shoppers in these groups.

Mainstream Midage and Young Singles/Couples were found to pay more per packet on average, suggesting:

Impulse-driven purchases rather than price sensitivity.

**Strategic Recommendation**
To improve category performance, especially targeting impulse buyers, we suggest:

**Tactical Product Placement:**
Off-locate premium or smaller pack-size chip products (like Tyrrells, 150g, 170g, and 175g packets)

Position them in discretionary retail spaces where Mainstream Young Singles/Couples are more likely to shop (e.g., near self-checkout, drinks sections, end-of-aisle displays)

**Timing for Promotions:**
Focus promotional efforts in high-spending months:
December, January, March, and July
These align with holiday seasons, social events, and back-to-school periods, which likely fuel impulse snack purchases.



