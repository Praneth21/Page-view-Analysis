#  Prior Product Knowledge & Page View Analysis

This code investigates differences in product awareness and website engagement across user profiles, particularly between Teachers and Parents.

## 📁 Files

- `Page view.R`: Complete R code
- `datasets/ecommerce-data.csv`: Required input file
- `screenshots/`: Visual plots

---

## 🔍 Key Topics

- Product knowledge comparisons using `table()` and `prop.table()`
- Chi-square and binomial testing for statistical significance
- Integer approximation of page views from category labels
- T-tests and ANOVA across user types
- Visual confidence intervals via `multcomp::glht()`

---

## 🖼️ Visual Output

| Image | Description |
|-------|-------------|
| Histogram of Product Knowledge | Faceted comparison of Teacher vs Parent awareness |
| Page Views CI (All Profiles) | Tukey HSD showing significance between groups |
| CI Plot (Teachers vs Parents) | Focused 95% CI comparison of 2 groups |

---

## 🧪 Instructions

1. Add `ecommerce-data.csv` to `datasets/`
2. Open and run `assignment5.R` in RStudio
3. All plots will generate in your console, and can be exported

---

## 📫 Contact

[LinkedIn – Praneth Nandeesh](https://www.linkedin.com/in/praneth-nandeesh-789038285)
