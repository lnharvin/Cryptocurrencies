# Cryptocurrencies

## Background

Martha is a senior manager for the Advisory Services Team at Accountability Accounting, one of your most important clients. Accountability Accounting, a prominent investment bank, is interested in offering a new cryptocurrency investment portfolio for its customers. The company, however, is lost in the vast universe of cryptocurrencies. So, they’ve asked you to create a report that includes what cryptocurrencies are on the trading market and how they could be grouped to create a classification system for this new investment.

The data Martha will be working with is not ideal, so it will need to be processed to fit the machine learning models. Since there is no known output for what Martha is looking for, she has decided to use unsupervised learning. To group the cryptocurrencies, Martha decided on a clustering algorithm. She’ll use data visualizations to share her findings with the board.

## Results

* Deliverable 1: Preprocessing the Data for PCA
  * [Crypto_Code](/crypto_clustering.ipynb)
* Deliverable 2: Reducing Data Dimensions Using PCA
  * [crypto_df](/images/crypto_df_shape.PNG)
* Deliverable 3: Clustering Cryptocurrencies Using K-means
  * ![Elbow Curve](/images/elbow_curve.PNG "Elbow Curve")
  * [Predictions](/images/K-means_predictions.PNG)
  * ![hvplot table](/images/hvplot_table.PNG "hvplot table")
* Deliverable 4: Visualizing Cryptocurrencies Results
  * ![3D-Scatter](/images/scatter_3d.png "3D-Scatter")
  * ![hvplot scatter plot](/images/hvplot_scatter2.png)
  
BitTorrent is showing as an outlier in my data; going to have to address that.


Module 18
