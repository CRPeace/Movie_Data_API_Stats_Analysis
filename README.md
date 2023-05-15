# Movie Data Analysis, Hypothesis Testing and Data Visualizations
---
### Analysis and statistical testing of select factors that contributed to the financial success of US movies 2000-2022.
---
### <mark>**Quick Summary** 
* The analysis revealed that ***movies rated for general audiences (G to PG-13) financially outperformed movies for mature audiences.***
*  The analysis revealed the ***specific revenue drop during 2020-2021 due the pandemic*** when compared to 2018-2019.
* The analysis also suggests that ***movies with common words in their titles underperform in terms of revenue.***
---

### Data Background:
* ### This project uses data from [IMDB](https://www.imdb.com/) (Internet Movie Database), combined with data obtained via API from [TMDB](https://www.themoviedb.org/?language=en-US) (The Move Database).
* ### The data were combined, cleaned, and filtered to select movies released in the US during the period 2000-2022, where sufficient financial data were present.
    
## Data Visualizations
![](https://github.com/CRPeace/Movie_Data_API_Stats_Analysis/blob/09f1e1af5124093153acb7d165a54915f9cd57a0/Data%20Viz/Movies%20by%20Rating.png)

* This visualization displays average revenue when the movies are grouped by MPAA rating.  We can see that movies for general audiences vastly outperform movies for mature audiences.  
* A Kruskal-Wallis ANOVA revealed the findings were statistically significant.
---
![](https://github.com/CRPeace/Movie_Data_API_Stats_Analysis/blob/09f1e1af5124093153acb7d165a54915f9cd57a0/Data%20Viz/Movie%20Title%20Samples.png)
* This visualization shows that movies that include common words in their titles (excluding words such as 'and', 'of', 'the', etc.) did not perform as well as movies whose titles used words less common in the dataset.
* A Kruskal-Wallis ANOVA revealed the findings were statistically significant.
---
![](https://github.com/CRPeace/Movie_Data_API_Stats_Analysis/blob/09f1e1af5124093153acb7d165a54915f9cd57a0/Data%20Viz/Pandemic%20Effect.png)
* This visualization highlights the dramatic loss in average revenue due to the COVID-19 pandemic.

---
### For further information

For any additional questions, please contact CPeaceData@gmail.com
