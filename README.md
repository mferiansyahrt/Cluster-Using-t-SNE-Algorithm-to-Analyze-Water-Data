# t-SNE-Clustering
Clustering anomalies from water data based on t-SNE algorithm using t-SNE to group spesific cluster, then use Gaussian Mixture to label each cluster.

Written in Python and uses the Scikit-Learn machine learning library.

This is unsupervised machine learning problem which purposed to see smaller clusters are identified as anomalies (Polluted water data).

The data is included on repo ("CleanedUp_DataSet_Orbi.csv"), with:
- Important Features start on first date column until the end of the column. Which "2021-11-29" column till "2022-09-02".
- "Ufid_1" and "Ufid_2" columns can be treated as index.
