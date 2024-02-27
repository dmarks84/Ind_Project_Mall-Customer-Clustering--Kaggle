# Ind_Project_Mall-Customer-Clustering--Kaggle

## Screenshot
![screenshot](https://github.com/dmarks84/Ind_Project_Mall-Customer-Clustering--Kaggle/blob/main/mall_screenshot.png)

## Summary
I worked with the Mall Customer Segmentation Dataset, which provided a various instances of shoppers of different ages, incomes, etc.  I first reviewed the data and used paired plots to determine that gender was not a greaty differentiator/indicator of customer segmentation.  I then employed three different Scikit-learn unsupervised clustering algorithms: K-Means, DBSCAN, and Mean Shift to determine if customer segmentation as a function of the other features-- Age and Income-- was possible and/or clear.  With K-Means, I plotted inertia for different numbers of clusters to hone in on potential elbow points, and I ran through several combinations of min_samples and epsilon for DBSCAN.

## Results
Both K-Means and Mean Shift settled on a cluster number of 5 when looking at the Score as a function of Income.  They overlapped substantially in their assignment of segment/cluster, leading to clear indication behind the "meaning" of each segment:
 - **Label 0** is "mid" income and "mid" spending
 - **Label 1** is "high" income and "low" spending
 - **Label 2** is "high" income and "high" spending
 - **Label 3** is "low" income and "low" spending
 - **Label 4** is "low" income and "high" spending

## Skills (Developed & Applied)
Programming, Python, Pandas, Dataframes, Unsupervised-ML, Clustering, DBSCAN, K-Means, Mean Shift, Scikit-learn, Technical Communication
