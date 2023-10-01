# AB-Testing-ANOVA
# <span style="font-family:cursive;">WHAT IS THE ANOVA(Analysis of Variance) ? </span>

ANOVA (Analysis of Variance) is a statistical test used to compare the means of two or more groups to determine if there is a significant difference between them. ANOVA analyzes the variation within each group and compares it to the variation between the groups.

The ANOVA test is based on the null hypothesis that there is no significant difference between the means of the groups being compared. The test calculates a statistical value called the F-statistic, which is the ratio of the variance between the groups to the variance within the groups. If the F-statistic is large enough and the p-value is small enough (usually set to 0.05 or less), then we reject the null hypothesis and conclude that there is a significant difference between the means of the groups.

ANOVA is widely used in various fields such as social sciences, biology, engineering, and business to compare means of different groups and to identify factors that may affect the variation between them.
## <span style="font-family:Broadway;">**Description of the Dataset**</span>
A fast-food chain plans to add a new item to its menu. However, they are still undecided between three possible marketing campaigns for promoting the new product. In order to determine which promotion has the greatest effect on sales, the new item is introduced at locations in several randomly selected markets. A different promotion is used at each location and the weekly sales of the new item are recorded for the first four weeks
​
**Columns** </br>
 **MarketID**: unique identifier for market</br>
 **MarketSize**: size of market area by sales</br>
 **LocationID**: unique identifier for store location</br>
 **AgeOfStore**: age of store in years</br>
 **Promotion**: one of three promotions that were tested</br>
 **week**: one of four weeks when the promotions were run</br>
 **SalesInThousands**: sales amount for a specific LocationID, Promotion, and week</br>
​
