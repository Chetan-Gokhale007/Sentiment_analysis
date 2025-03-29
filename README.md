Sentiment Analysis of Delivery Apps (Blinkit, Zepto, Jiomart)
This project performs sentiment analysis on customer reviews of three popular delivery apps in India: Blinkit, Zepto, and Jiomart. The analysis aims to understand customer satisfaction, identify key areas for improvement, and compare the performance of these platforms.

Project Structure


reviews.csv: The dataset containing customer reviews.
From Rating to Reality: A Deep Dive into User Feedback on Blinkit, Zepto, and Jiomart.ipynb: The Jupyter notebook containing the code for data loading, preprocessing, sentiment analysis, and visualization.


README.md: This file providing an overview of the project.


Data Source
The dataset used for this analysis is sourced from Kaggle: [Blinkit vs Zepto vs Jiomart Reviews]. It includes customer reviews, ratings, and platform information.

Methodology
Data Loading and Preprocessing: The dataset is loaded using Pandas, and the review text is cleaned by removing stop words, punctuation, and performing lemmatization.


Sentiment Analysis: Sentiment scores are calculated for each review using VADER (Valence Aware Dictionary and sEntiment Reasoner). Reviews are categorized as positive, negative, or neutral based on their sentiment scores.


Visualization: The results are visualized using various plots, including bar charts, line charts, and word clouds.
Key Findings


Overall Sentiment: The majority of reviews across all platforms are negative, indicating a need for improvement in customer satisfaction.
Rating vs. Sentiment Alignment: There is a significant mismatch between customer ratings and the sentiment expressed in their reviews. Many users provide positive ratings despite writing negative reviews.


Common Themes: Common negative themes in reviews include delivery issues, service quality, pricing, and product availability.
Platform Comparison: Zepto receives the highest volume of reviews, but it also has a high proportion of negative reviews. Blinkit and Instamart have relatively fewer reviews but comparable sentiment distributions.


Conclusion
This analysis reveals valuable insights into customer sentiment towards Blinkit, Zepto, and Jiomart. The delivery platforms should focus on addressing the key concerns highlighted in the negative reviews to enhance customer satisfaction and loyalty.
