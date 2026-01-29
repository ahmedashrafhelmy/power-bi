# power-bi
How to deal with Null
Handling NULL Values in Data Analysis
Why NULL Values Matter ?
1-Distort averages and key metrics
2-Lead to misleading trends and conclusions
3-Reduce the accuracy of machine learning models

Types of Missing Data:
MCAR – Missing Completely At Random
 Missing values occur randomly with no clear pattern.
 Common approach: mean/median imputation or dropping rows if the number is small.
MAR – Missing At Random
 Missing values depend on another variable in the dataset.
 Common approach: model-based imputation or adding a missing indicator column.
MNAR – Missing Not At Random
 Missing values depend on the value itself.
 Common approach: using domain knowledge.

 Common Imputation Methods:
 Numerical Data
      Mean or Median (median preferred with outliers)
Interpolation for time-series data
      Model-based methods such as KNN or regression
Categorical Data
      Mode or Creating an “Unknown” category
Time Series Data
      Forward fill (last observed value)
      Backward fill (next observed value)
Quick Decision Guide
      Few missing values → drop rows
      More than 50% missing in a column → consider dropping the column
Key Takeaway
      Always understand why values are missing before filling them.
       Correct handling of NULLs protects data quality and leads to more reliable insights.
 
