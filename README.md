# Task 4 — Data Storytelling & Statistical Validation

## Files
- `sales_dataset.xlsx` — input dataset
- `analysis.py` — reproducible analysis and hypothesis test
- `Task4_Final_Presentation.pptx` — final stakeholder deck
- `hypothesis_testing_summary.md` — statistical test write-up
- `presentation_script.md` — 7–10 minute speaking script
- `requirements.txt` — Python dependencies

## Quick Start
1. Install Python 3.10+
2. Open this folder in VS Code
3. Run: `pip install -r requirements.txt`
4. Run: `python analysis.py`
5. Open `Task4_Final_Presentation.pptx` and present/export as needed.

## Key Results
- Total revenue: ₹139,399,439.65
- Distinct orders: 992
- AOV: ₹140,523.63
- Repeat-customer rate: 5.49%
- Top category: Electronics — ₹50,778,581.70
- Welch t-test p-value: 0.4137 (not significant at 0.05)

## Business Story
Electronics is the largest revenue category, but statistical testing does not show a significant difference in average order value versus other categories. The clearest business opportunity is customer retention: only about 5.5% of unique customers repeat in this dataset. The recommended strategy is to protect high-revenue products while building repeat-purchase programs and validating future decisions statistically.
