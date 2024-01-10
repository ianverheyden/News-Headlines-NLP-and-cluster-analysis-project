# Purpose:
Fetches headlines scraped from Google News and subjects them to cluster analysis, outputting the key natural language words that best represent the headlines in each cluster. 
To be used for short term or long term analysis of news trends, however can be easily modified for other applications. 

## Methods: 
  * Use of Requests library to fetch html from Google News API
  * Html parsing using Beautiful Soup
  * List of headlines are then cleaned, vectorized, lemmatized, and stemmed.
  * Determination of optimum number of clusters using elbow analysis and comparison of silhouette scores. 
  * Clustering analysis using Sklearn.cluster library's KMeans algorithm.
  * Resulting clusters subjected to dimensionality reduction (PCA) and are visualized in 3 factor space.
  * Label each cluster centroid with the list of most representative words, according to TFID frequenecy.
 
## Example Results: 
https://github.com/ianverheyden/News-Headlines-Web-Scraping-Cluster-Analysis-and-Visualization/assets/126430109/a769f6e6-7b9c-4c23-8bd1-e7228ee92898

![Screenshot 2024-01-10 at 2 07 41 PM](https://github.com/ianverheyden/News-Headlines-Web-Scraping-Cluster-Analysis-and-Visualization/assets/126430109/6341f5f3-0024-4336-ba3b-9f4bb32d43ff)
![Screenshot 2024-01-10 at 2 08 08 PM](https://github.com/ianverheyden/News-Headlines-Web-Scraping-Cluster-Analysis-and-Visualization/assets/126430109/e0ead0e8-6f6d-4978-b63d-1d431dd60ea2)
![Screenshot 2024-01-10 at 2 15 15 PM](https://github.com/ianverheyden/News-Headlines-Web-Scraping-Cluster-Analysis-and-Visualization/assets/126430109/4d9466be-3b79-4d02-a4da-f947e8956a32)
