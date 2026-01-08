# Flipkart_Refrigerator-Using-WebScraping
Flipkart Refrigerator Data Analysis

This project analyzes refrigerator product data scraped from Flipkart to uncover pricing trends, brand performance, customer ratings behavior, and relationships between key features. The goal is simple: turn raw e-commerce data into insights that actually explain what drives price, demand, and perceived value.

📁 Project Files
Flipkart_Refriderator.ipynb — main notebook with cleaning + analysis Raw dataset is loaded inside the notebook (scraped Flipkart product data)

🔍 Objectives
Clean messy e-commerce product data. Explore feature relationships (price, capacity, ratings, discount, brand). Identify what most strongly influences price. Segment refrigerators by price ranges (₹20,000–₹50,000 focus window). Provide clear, business-style insights — not just charts.

🧹 Data Cleaning
Key fixes applied: Removed duplicates and irrelevant columns Converted price/discount fields to numeric Standardized brand names Filled missing values logically (not blindly) Stripped whitespace and formatting characters

If any cleaning step feels like a guess instead of a rule — document it. Analysts lose credibility when transformations are unclear.

📊 Core Analysis ➤ Correlation Insights (No Visualization Only) Price vs Capacity — strong positive relationship Price vs Rating — weak correlation (customers don’t only pay for “stars”) Discount vs Price — often negative (higher-priced models get higher absolute discounts) Correlation doesn’t prove cause — it tells you where to look deeper.

➤ Group-By Insights
By Brand: average price, rating, and discount comparison By Capacity Range: capacity tiers vs pricing By Price Buckets: which brands dominate each segment

🧠 Key Takeaways
Bigger refrigerators almost always cost more — no surprise — but the rate of price increase jumps after certain capacity thresholds. Higher price does not guarantee better ratings. Brands compete aggressively in the ₹20k–₹50k range — this is the “decision battlefield.” Discounts are used strategically to make mid-range models look more appealing. If your presentation doesn’t clearly say why these insights matter, it’s incomplete.

AUTHOR :Bandari Sireesha

▶️ How to Run
Clone the repo Install requirements (Pandas, Matplotlib/Seaborn, NumPy) Open the notebook: jupyter notebook Flipkart_Refriderator.ipynb Run all cells

🚀 Possible Improvements (You should actually do these)
Add price prediction model (simple regression) Analyze reviews text instead of only ratings Automate scraping and update the dataset monthly Build a Power BI or dashboard layer Right now this is a solid EDA — but not yet a decision tool.
