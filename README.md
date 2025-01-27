# Trending Products on E-Commerce Website

## Project Overview

This project focuses on extracting and analyzing data from the [Amazon Best Sellers](https://www.amazon.com/Best-Sellers/zgbs/) page to uncover key insights about trending products. The analysis provides an understanding of customer behavior, popular product categories, and brand performance.

### Key Findings

1. **Impact of Reviews on Sales**  
   - As the number of reviews increases, the sales of a product tend to increase significantly.

2. **Relationship Between Reviews and Seller Rank**  
   - Products with the highest number of reviews tend to rank closer to #1 in the seller rankings.

3. **Top Categories**  
   - **Parent Category:** *Clothing, Shoes & Jewelry*  
   - **Subcategory:** *Men's Mules & Clogs*  
     (Products in these categories with more reviews are purchased more frequently.)

4. **Top 10 Brands**  
   - The top brand is **Ring**, followed by others identified in the analysis.

5. **Top 10 Products**  
   - The leading product is **Crocs Unisex Adult Classic Clog**.

6. **Trends Over Time**  
   - Products released earlier (e.g., 2004) show lower sales in recent months, while newer products (e.g., 2024 releases) demonstrate higher sales growth.  
   - Based on this trend, products released in 2025 are expected to achieve the highest sales.

7. **Geographical Insights**  
   - A geographical analysis highlights the number of distinct brands across countries.  
   - For instance, China has 126 distinct brands, the highest among all countries.

### Tableau Public Dashboard

For an interactive visualization of the findings, please visit the [Tableau Dashboard](https://public.tableau.com/app/profile/mominur.rahman/viz/TrendingProductsonE-CommerceWebsite/Dashboard).

---

## Project Usage Guide

To replicate or extend this analysis, follow the steps below:

### Prerequisites
Ensure Python is installed on your machine.

### Steps to Run the Project

1. **Clone the Repository**  
   ```bash
   git clone https://github.com/mominurr/Trending-Products-on-E-Commerce-Website.git
    ```
2. **Create a Virtual Environment**

    ```bash
    python -m venv myvenv
    ```
3. **Install Dependencies**

    ```
    pip install -r requirements.txt
    ```
4. **Run the Scraper Script**

    Execute the script to scrape data from Amazon.
    ```bash
    python scripts/scraper.py
    ```
- The scraped data will be saved as ``data/Amazon Best Sellers.csv``.
5. **Process the Data**

    Open and run the data_preparation.ipynb notebook to handle missing and duplicate values.

- The cleaned data will be saved as ``data/Preprocessed Amazon Best Sellers.csv``.

## Additional Resources
**Tableau Dashboard**: For detailed visualizations, visit the [Dashboard](https://public.tableau.com/app/profile/mominur.rahman/viz/TrendingProductsonE-CommerceWebsite/Dashboard).

**Author**: [Mominur Rahman](https://mominur.dev/)