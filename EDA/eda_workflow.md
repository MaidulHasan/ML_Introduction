1. Reading in data (`parse_dates`)
2. Initial exploration (`head, shape, info, columns, nunique, dtypes` etc)
3. Datatype casting (`astype`, inspecting `max` and `min` values in numerical columns and casting datatypes accordingly, string and categorical type, `apply`, string manipulation, `rename`)
4. Data cleaning and imputation (`isna, dropna, fillna, interpolate, np.select, where, mask, query, duplicated, drop_duplicates`)
5. Data validation (consider for bias, `dtypes, info, describe, isin, value_counts, unique, nunique, select_dtypes`)
6. Data summarization (`groupby, agg, filter, transform, pivot_table, pd.crosstab, barplot`)
7. Analyzing categorical data (`select_dtypes, value_counts, unique, nunique, barplot,`)
8. Exploring categorical relationships (`barplot, kdeplot, scatterplot-hue`)
9. Analyzing numerical data (`describe, boxplot, violinplot, kdeplot, histplot, jointplot, pairplot`)
10. Handling outliers (`boxplot, quantile, loc, query, clip`)
11. Exploring numerical relationships (`correlation, heatmap, scatterplot, regplot, pairplot`)
12. Analyzing datetime data and Exploring trends/patterns over time (`pd.to_datetime, dt.year, dt.month, dt.day, dt.weekday, groupby, resample, rolling`)
13. Creating new categories (`value_counts, quantile, pd.cut, np.select, assign`)
14. Creating new features (`value_counts, np.select, assign`)
15. Hypothesis testing