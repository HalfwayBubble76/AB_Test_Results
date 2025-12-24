
# A/B Test Analysis: Premium Plus Pricing ($9.99 vs $4.99)

## 📌 Summary
Lowering the Premium Plus subscription price from **$9.99** to **$4.99** did **not** increase overall revenue.  
- Control group generated **~2× more revenue** than the variant.  
- Conversion rates were similar and far below the break-even point.  
**Recommendation:** Keep the $9.99 price.

---

## ✅ Key Metrics

| Metric            | Control ($9.99) | Variant ($4.99) |
|-------------------|-----------------|-----------------|
| Unique Users      | 3,931           | 3,934           |
| Converters        | 80              | 71              |
| Conversion Rate   | 2.04%           | 1.83%           |
| Total Revenue     | $643.00         | $351.47         |
| ARPU              | $0.16           | $0.09           |
| AOV               | $8.04           | $4.95           |

---

## 🧠 Business Insight
Cutting the price in half would require roughly **double the conversion rate (~4%)** to break even.  
Actual variant conversion was **~1.8%**, far below that threshold.

---

## 📊 Visualizations
![Conversion Rate](figures/conversion_rate.png)
![Total Revenue](figures/total_revenue.png)
![ARPU](figures/arpu.png)
![AOV](figures/aov.png)

*(Charts generated in Python using Matplotlib/Seaborn. See notebook for code.)*

---

## 📂 Project Structure
``

├── README.md
├── requirements.txt
├── data/
│   └── AB_Test_Results.csv
├── notebooks/
│   └── ab_pricing_experiment.ipynb
├── figures/
│   ├── conversion_rate.png
│   ├── total_revenue.png
│   ├── arpu.png
│   └── aov.png
└── LICENSE

## 🔍 Analysis Steps
1. Load and clean dataset.
2. Compute:
   - Unique users per group
   - Conversion rate
   - ARPU (Average Revenue Per User)
   - AOV (Average Order Value)
3. Visualize metrics with bar charts.
4. Interpret results and provide recommendation.

---

## 📓 Notebook
- notebooks/AB_Test_Results.ipynb
- [https://nbviewer.org/github/YOUR_USERNAME/YOUR_REPO/blob/main/notebooks/ab_pricing_experiment.ipynb](https://nbviewer.org/github/HalfwayBubble76/AB_Test_Results/blob/main/AB_Test_Results.ipynb)


---

## ⚙️ Requirements
Install dependencies:
```bash
pip install -r requirements.txt

pandas >= 2.0
numpy >= 1.24
matplotlib >= 3.7
seaborn >= 0.12


## ✅ License
MIT License © 2025 Tim Manuel

---

## 🔗 Connect
- [LinkedIn]([https://www.linkedin.com/in/timothy-manuel-a70112149/]

