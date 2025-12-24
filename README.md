
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
![Conversion Rate](<img width="766" height="566" alt="conversion_rate" src="https://github.com/user-attachments/assets/f6c92c67-46c5-44e7-8951-bef5f095d591" />)
![ARPU](<img width="766" height="566" alt="arpu" src="https://github.com/user-attachments/assets/026f5752-8bd5-48ff-a311-242c97403e60" />
)
![AOV](<img width="766" height="566" alt="aov" src="https://github.com/user-attachments/assets/1015d265-91f0-401c-ba18-33e9ca73dc10" />
)

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
- [https://nbviewer.org/github/HalfwayBubble76/AB_Test_Results/blob/main/AB_Test_Results.ipynb]


---


## ✅ License
MIT License © 2025 Tim Manuel

---

## 🔗 Connect
- [LinkedIn]([https://www.linkedin.com/in/timothy-manuel-a70112149/]

## ⚙️ Requirements
To run this project, you will need **Python 3.x** and the following libraries:

* **Pandas**: For data manipulation and analysis.
* **NumPy**: For scientific computing and array handling.
* **Matplotlib / Seaborn**: For creating the visualizations and plots.

### Installation
You can install all dependencies using pip:
```bash
pip install pandas numpy matplotlib seaborn
