# Applied Biostatistics – Psoriasis Detection

This project explores the use of logistic regression for detecting psoriasis based on clinical and histopathological features. It was conducted as part of an applied biostatistics assignment during spring semester 2024.

## Project Structure

```
.
├── data/                   # Raw dataset and metadata
│   ├── dermatology.data
│   ├── dermatology.names
│   └── col_names.txt
├── notebooks/              # R Markdown analysis notebook
│   └── logistic_regression.Rmd
├── report.pdf              # Final rendered report
└── README.md               # Project documentation
```

## Summary

- **Data**: Dermatology dataset from the UCI Machine Learning Repository.
- **Goal**: Build a logistic regression model to predict psoriasis cases.
- **Methods**: Data cleaning, multicollinearity analysis (VIF), feature selection (Lasso), model evaluation.
- **Tools**: R, R Markdown

## References

- Güneş et al., 1998 – "Learning differential diagnosis of erythematosquamous diseases using voting feature intervals"
- [UCI Dermatology Dataset](https://archive.ics.uci.edu/dataset/33/dermatology)
