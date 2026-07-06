# Movie Budget Analysis

An exploratory data analysis and linear regression project examining the relationship between film production budgets and worldwide box office revenue.

## Overview

This project analyzes a dataset of film production budgets and box office revenue to understand how spending on a film relates to what it earns. Using Python, Pandas, Seaborn, and scikit-learn, the analysis covers overall financial patterns, notable outliers, historical trends, and a comparison of regression model performance across different eras of filmmaking.

## Technologies Used

- Python
- Pandas
- Seaborn
- Scikit-learn (Linear Regression)
- Matplotlib

## Key Findings

**1. Average return on budget**
The average film costs around $31M to produce and returns roughly 3x that (~$89M) in worldwide revenue.

**2. Risk at the bottom quartile**
Films in the bottom quartile of the dataset consistently lose money — averaging a $5M budget against just $3.8M in worldwide revenue.

**3. Extreme outliers**
The highest production budget in the dataset was $425M, while the highest worldwide revenue recorded was $2.78 billion.

**4. Domestic vs. worldwide revenue gap**
512 films show $0 domestic revenue, compared to 357 with $0 worldwide revenue. The difference is explained by films released internationally but never screened in the United States — for example, *Don Gato, el inicio de la pandilla* earned ~$4.5M internationally on an $80M budget, but made $0 domestically.

**5. Nearly 4 in 10 films lose money**
37.2% of all films in the dataset fail to recoup their production budget at the box office — before marketing costs are even factored in.

**6. Budgets have exploded since the 1980s**
Production budgets remained relatively low and stable until the 1970s, then grew rapidly through the 1980s and 2000s. Film output also scaled up dramatically, especially post-2000.

**7. Films before 1970 are rare in this dataset**
Only 153 films predate 1970. The most expensive production from that era was *Cleopatra*, with a $42M budget — a massive sum for its time.

**8. Budget is a weak predictor of revenue for older films**
Regression analysis on pre-1970 films shows a weak fit — many low-budget films significantly outperformed high-budget ones, and the regression line fails to capture the relationship well.

**9. The model fits much better for modern films**
When applied to more recent films, the regression shows a notably tighter fit and narrower confidence interval. The model predicts a film with a $150M budget would earn just under $500M.

## Conclusion

Production budget has some relationship with box office revenue, but that relationship is far from guaranteed — nearly 40% of films lose money outright, and the predictive strength of budget varies significantly by era. Modern films show a much stronger budget-to-revenue relationship than older films, suggesting the economics of filmmaking have become more predictable — and higher stakes — over time.
