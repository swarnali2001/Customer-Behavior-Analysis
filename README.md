

## 🟦 STAR Interview Presentation: Customer Shopping Behavior Analysis

### ⭐ Situation  
A retail dataset containing 3,900 customer transactions across multiple product categories was analyzed to uncover behavioral patterns, segment customers, and evaluate the impact of discounts and subscriptions. The objective was to generate actionable insights that could guide marketing, product positioning, and customer retention strategies.

---

### 🎯 Task  
The project aimed to simulate a full-cycle analytics workflow by:
- Cleaning and preparing the dataset for analysis  
- Extracting behavioral and financial insights using SQL  
- Segmenting customers based on purchase history  
- Visualizing key metrics through a Power BI dashboard  
- Recommending strategies to improve revenue and engagement

---

### ⚙️ Tech Stack & Workflow  
- **Python (pandas, matplotlib):** Used for data cleaning, feature engineering, and exploratory analysis  
- **PostgreSQL:** Enabled structured querying to answer business questions  
- **Power BI:** Delivered an interactive dashboard for stakeholder-style presentation  
- **Feature Engineering:**  
  - Age was binned into `age_group` categories  
  - Purchase history was used to derive `purchase_frequency_days`  
- **Data Quality:**  
  - Missing review ratings were imputed using category-wise medians  
  - Redundant fields like `promo_code_used` were removed after consistency checks  
- **Integration:**  
  - Cleaned data was loaded into PostgreSQL for deeper transactional analysis

---

### 🔍 Insights & Impact  

#### 🧠 Customer Segmentation  
- 80% of customers were classified as **Loyal**, indicating strong retention potential  
- Repeat buyers with more than 5 purchases were significantly more likely to be **subscribers** (958 vs. 2518)

#### 💰 Revenue Drivers  
- **Male customers** generated over twice the revenue of female customers ($157K vs. $75K)  
- **Young Adults** led revenue contribution across age groups ($62K), followed by Middle-aged and Adults

#### 🎯 Product Performance  
- **Top-rated items** included Gloves (3.86), Sandals, and Boots—ideal for promotional campaigns  
- **Best-sellers by category:** Jewelry (Accessories), Blouse (Clothing), Sandals (Footwear), Jacket (Outerwear)

#### 🎁 Discount Dynamics  
- 839 customers used discounts yet spent above average—indicating discount-driven high-value behavior  
- Products like **Hat, Sneakers, and Coat** had the highest discount dependency (≈50%)

#### 🚚 Shipping Preferences  
- **Express shipping** users spent slightly more on average ($60.48 vs. $58.46)—suggesting upsell potential

#### 📊 Subscription Analysis  
- Subscribers represented 27% of the customer base and showed higher repeat purchase rates  
- Promoting subscription benefits could help convert high-frequency buyers

---

### ✅ Result  
The Power BI dashboard consolidated all key metrics and was designed for stakeholder-style reporting. Based on the analysis, the following strategic recommendations were made:

- Promote subscriptions to repeat buyers  
- Launch loyalty programs to retain high-frequency customers  
- Refine discount strategies to protect margins  
- Prioritize top-rated products in marketing campaigns  
- Target high-revenue age groups and express-shipping users  

---

