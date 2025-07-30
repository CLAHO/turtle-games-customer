# Turtle Games Customer Analytics

**Author**: Suleiman Chun Lum Andy Ho  
LSE – Data Analytics Career Accelerator

This project explores customer behavior, review sentiment, and loyalty trends using data provided by Turtle Games, a retailer of books, board games, video games, and toys. Using Python and R, we uncover insights through clustering, sentiment analysis, and predictive modelling to improve customer targeting and business performance.

---

## Objectives

- Understand key drivers of loyalty points using regression and decision trees.
- Segment customers based on spending and demographics using K-Means clustering.
- Identify trends and customer sentiment from product reviews.
- Recommend targeted marketing strategies and loyalty scheme redesigns.

---

## Key Findings

- **Decision tree model (R² = 0.91)** outperformed MLR (R² = 0.84) in predicting loyalty points.
- **Customers with high remuneration and high spending score** earn the most loyalty points.
- Some high-spending customers still receive low loyalty rewards — a system gap.
- **Sentiment analysis** showed that most reviews are positive and help identify best/worst-rated products.
- K-Means clustering reveals 5 customer segments, enabling better marketing focus.

---

## Methodology

### Tools Used:
- **Python**: pandas, seaborn, scikit-learn, nltk, matplotlib, TextBlob, VaderSentiment
- **R**: dplyr, factoextra, ggplot2, openxlsx
- **Excel**: initial data review

### Techniques:
- Data cleaning and validation
- Multi-linear regression
- Decision tree modeling
- K-means clustering
- Review sentiment analysis (VADER/TextBlob)

---

## Repository Structure

/data/ # Raw and cleaned customer and review data
/scripts/ # Python & R scripts for analysis and modelling
/visualisations/ # Figures: regression, clustering, sentiment charts
/report/ # Technical report PDF
README.md


---

## Sample Visualisations

> _(Add `.png` figures in /visualisations and link them like this)_

- ![Decision Tree Output](visualisations/decision_tree.png)
- ![KMeans Clustering](visualisations/kmeans_clusters.png)
- ![Sentiment Histogram](visualisations/sentiment_distribution.png)

---

## Recommendations

| Recommendation                                                              | Priority |
|-----------------------------------------------------------------------------|----------|
| Use decision tree models over MLR for predicting loyalty points             | ✅ High  |
| Redesign loyalty scheme to reward all high spenders, not just high earners | ✅ High  |
| Segment customers by spending/remuneration for targeted promotions         | ✅ High  |
| Incorporate sentiment analysis to identify high/low performing products    | ✅ High  |
| Improve data: unique product IDs, product categories, purchase dates       | ⚠️ Medium |

---

## Author

**Suleiman Chun Lum Andy Ho**  
[LinkedIn](https://www.linkedin.com/in/scla-ho/) | [GitHub](https://github.com/CLAHO)

---

## References

- Turtle Games dataset (simulated for academic use)
- [TextBlob](https://textblob.readthedocs.io)
- [VADER Sentiment](https://github.com/cjhutto/vaderSentiment)
- [Scikit-learn](https://scikit-learn.org)



