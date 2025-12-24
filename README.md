# AB_Test_Results
Results of A/B Testing - Comparing pricing of Premium Plus at $9.99/month (control) vs $4.99/month (variant).

# A/B Test: Premium Plus Pricing ($9.99 vs $4.99)

**Goal:** Determine whether lowering the Premium Plus price from **$9.99** to **$4.99** increases overall revenue for a streaming platform.

## Dataset
- `AB_Test_Results.csv` (user_id, variant_name, revenue)
- Two groups:
  - **control** = $9.99/month
  - **variant** = $4.99/month

## Methods (Plain English)
1. Compute **unique users** per group.
2. Mark **converted** users (revenue > 0).
3. Calculate core metrics:
   - **Conversion Rate** = converted users ÷ unique users
   - **ARPU** (avg revenue per user) = total revenue ÷ unique users
   - **AOV** (avg order value among payers) = total revenue ÷ converted users
4. Visualize **conversion**, **ARPU**, **AOV**, and **total revenue** with bar charts.
5. Optional: sanity checks for statistical significance; break-even logic for pricing.

## Key Results (TL;DR)
- **Control ($9.99)** wins on **total revenue**, **ARPU**, and **AOV**.
- Conversion is ~**2.04%** (control) vs ~**1.8–1.83%** (variant) — **not enough** lift.
- Break-even intuition: halving price would need roughly **double** conversion (~4%); actual variant conversion is far below that.

**Recommendation:** Keep **$9.99**. Consider testing other value levers (features, bundles, trial length) instead of deep price cuts.

## Notebook
- Main analysis: `notebooks/ab_pricing_experiment.ipynb`
- View online (if GitHub rendering is slow):
  - **nbviewer:** <ADD_NBV_LINK_HERE>
  - **Binder (run in browser):** <ADD_BINDER_LINK_HERE>

## Figures
Saved in `figures/`:
- `conversion_rate.png`
- `arpu.png`
- `aov.png`
- `total_revenue.png`
- `revenue_distribution.png` (optional)

## Reproducibility
```bash
pip install -r requirements.txt
