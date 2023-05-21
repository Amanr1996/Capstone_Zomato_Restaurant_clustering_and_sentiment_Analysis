# Project Name - Zomato Restaurant Clustering and Sentiment Analysis.
## Project Type - Unsupervised
## Contribution - Individual

## Project Summary -
Zomato is an Indian restaurant aggregator and food delivery start-up founded by Deepinder Goyal and Pankaj Chaddah in 2008. Zomato provides information, menus, and user reviews of restaurants, and also has food delivery options from partner restaurants in select cities.

India is quite famous for its diverse multi-cuisine available in a large number of restaurants and hotel resorts, which is reminiscent of unity in diversity. The restaurant business in India is always evolving. More Indians are warming up to the idea of eating restaurant food whether by dining outside or getting food delivered. The growing number of restaurants in every state of India has been a motivation to inspect the data to get some insights, interesting facts, and figures about the Indian food industry in each city. So, this project focuses on analyzing the Zomato restaurant data for each city in India.

There are two separate files, and the columns are self-explanatory. Below is a brief description:

Restaurant names and Metadata - This could help in clustering the restaurants into segments. Also, the data has valuable information about cuisine and costing which can be used in cost vs. benefit analysis Restaurant reviews - Data could be used for sentiment analysis. Also, the metadata of reviewers can be used for identifying the critics in the industry.

## Problem Statement:

The Project focuses on Customers and Company, We have to analyze the sentiments of the reviews given by the customer in the data and made some useful conclusions in the form of Visualizations. Also, cluster the zomato restaurants into different segments. The data is visualized as it becomes easy to analyze data in an instant. The Analysis also solves some of the business cases that can directly help the customers find the Best restaurant in their locality and for the company to grow up and work in the fields they are currently lagging in.

This could help in clustering the restaurants into segments. Also, the data has valuable information about cuisine and cost which can be used in cost vs. benefit analysis

Data could be used for sentiment analysis. Also, the metadata of reviewers can be used for identifying the critics in the industry

## Steps that are performed:

* Importing libraries
* Loading the dataset
* Shape of the dataset
* Dataset information
* Handling the duplicate values
* Handling missing values.
* Undeerstanding the columns
* Variable description
* Data wrangling
* Data visualization
* Storytelling and experimenting with charts.
* Text preprocessing,
* Latent Dirichlet Allocation
* Sentiment analysis
* Challenges faced
* Conclusion.

## Conclusion
Based on the implementation of **K-means clustering**, the project successfully achieved its goals of clustering and sentiment analysis. The clustering aspect of the project provided valuable insights into the grouping of restaurants based on their features. By analyzing various attributes such as location, cuisine type, price range, and customer ratings, the project was able to identify distinct clusters of restaurants. This information can be highly beneficial for both users and businesses.

For users, the clustering results enable them to make informed decisions when choosing a restaurant. By understanding the characteristics of each cluster, users can easily identify restaurants that align with their preferences. For example, if a user prefers affordable family-friendly restaurants, they can refer to the cluster that specifically caters to this category. This empowers users to save time and effort in finding suitable dining options.

On the other hand, businesses can leverage the clustering results to gain insights into their competition and target customer segments. By understanding which features contribute to successful clusters, businesses can optimize their offerings to attract specific customer groups. For instance, if a cluster of highly-rated upscale restaurants exists, other businesses can learn from their success and adapt their strategies accordingly.

In addition to clustering, the sentiment analysis part of the project provided valuable insights into user sentiments expressed in restaurant reviews. By analyzing the text data, the sentiment analysis technique employed was able to classify reviews into positive, negative, or neutral categories. This information allows businesses to gauge the overall satisfaction level of their customers and identify areas for improvement.

Businesses can use the sentiment analysis results to identify patterns in customer feedback and address any recurring issues or concerns. For example, if a particular cluster of restaurants consistently receives negative sentiments regarding slow service, the businesses in that cluster can prioritize improving their service speed to enhance customer satisfaction.

Moving forward, there are several potential areas for future work in this project. One area of improvement involves implementing more advanced clustering algorithms. K-means clustering, while effective, has certain limitations, such as sensitivity to initial centroid selection and difficulty in handling non-linear data. Exploring alternative clustering algorithms, such as hierarchical clustering or density-based clustering, could provide more accurate and robust clustering results.

Furthermore, incorporating additional features beyond the existing attributes, such as images and menus of the restaurants, can enhance the clustering and sentiment analysis processes. Images can provide visual cues that contribute to clustering patterns, while menus can offer insights into specific restaurant features that impact customer sentiments. Integrating these data sources would offer a more comprehensive understanding of restaurants and improve the accuracy of the analysis.

Lastly, exploring the relationships between the clustering and sentiment analysis results can provide deeper insights into customer preferences and sentiments across different clusters. Analyzing how specific features within each cluster correlate with positive or negative sentiments can uncover valuable patterns and potentially guide businesses in making targeted improvements.

Overall, the project successfully achieved its goals of clustering and sentiment analysis, offering valuable insights for both users and businesses. By implementing more advanced clustering algorithms, incorporating additional features, and exploring the relationships between clustering and sentiment analysis, future work can further enhance the accuracy and applicability of the project's findings.
