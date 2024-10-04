# Travel Agency Booking Data Clustering

This repository contains code for clustering travel agency booking data to identify distinct customer segments based on their travel preferences. The analysis includes:

**Index:**

* [Data Exploration and Preprocessing](#data-exploration-and-preprocessing)
* [Feature Engineering](#feature-engineering)
* [Statistical Analysis](#statistical-analysis)
* [Clustering](#clustering)
* [Visualization](#visualization)
* [Dependencies](#dependencies)
* [Usage](#usage)


**Data Exploration and Preprocessing:**
* Loading and inspecting the dataset
* Handling missing values
* Data type conversion
* Correlation analysis

**Feature Engineering:**
* Creating new features like `duration` and `days_in_advance` to capture relevant travel patterns

**Statistical Analysis:**
* Analyzing booking rates and performing statistical comparisons across different channels

**Clustering:**
* Standardizing the data
* Implementing K-means clustering with different numbers of clusters
* Using the Elbow Method and Silhouette Coefficient to determine the optimal number of clusters
* Profiling and interpreting the resulting clusters

**Visualization:**
* Creating histograms and heatmaps to visualize data distributions and correlations
* Using Principal Component Analysis (PCA) to visualize clusters in a 2D space

**Dependencies:**
* pandas
* numpy
* statsmodels
* scipy
* sklearn
* matplotlib
* seaborn

**Usage:**
1. Clone the repository: `git clone https://github.com/your-username/travel-booking-clustering.git`
2. Install the required packages: `pip install -r requirements.txt`
3. Run the Jupyter notebook: `jupyter notebook travel_booking_clustering.ipynb`
