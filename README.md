# Electricity-Usage

## Analysis techniques used 
__Q1: Metric Multidimensional Scaling__
* Using the distance matrix in powerDist-1.RData, perform metric multidimensional scaling (MDS).
* Plot the MDS results, using symbols/colors to represent Tariff and Group.
* Create a second plot showing total use as bubble size, using color to represent Group.
* Summarize any trends or interesting features in these two plots.


__Q2: Dendrogram and Group Associations__
* Use the distance matrix in powerDist.RData to create a dendrogram using complete linkage.
* Plot the dendrogram and label the leaves with the corresponding category.
* Cut the dendrogram to create four groups and display this on the plot.
* Create a table of these four groups and the three aggregated socio-economic groups.
* Create a separate table of the dendrogram groups and electricity tariff types.
* Examine whether the dendrogram groups are associated with the socio-economic group or tariff.

__Q3: Permanova Analysis__
* Focus on the "comfortable" category households from the comfortable.csv dataset.
* Perform a permanova analysis based on the Euclidean distance metric.
* Summarize the conclusions drawn from the analysis.

__Q4: K-means Clustering__
* Perform k-means clustering on the profiles of the "comfortable" households.
* Create graphs of the within-group sum of squares and the C-H index.
* Select the appropriate number of clusters based on the plots' features.
* Create tables of the cluster memberships and the detailed Acorn categories.
* Create a table of the cluster memberships and tariff.
* Assess any associations qualitatively.


## Data

The data used is provided in the following files:

powerDist-1.RData: Contains pairwise distances between average electricity profiles for each combination of Acorn category and electricity scheme.
AcornInfo.csv: Provides information on the factors, including the average total daily electricity use and the descriptors of the Acorn categories.
comfortable.csv: Contains data specifically for the "comfortable" category households, including their electricity profiles.

## Conclusions
This project provides an opportunity to analyze and explore the relationships between electricity tariffs, socio-economic factors, and household electricity consumption patterns. Through various analyses, including metric MDS, dendrogram clustering, and k-means clustering, insights can be gained regarding the associations between different variables and patterns observed in the data.

The code and results presented in this repository demonstrate proficiency in data analysis, visualization, and statistical techniques, making it a valuable addition to a CV or portfolio.




