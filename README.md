**Amazon Product Analytics**
**How to Run the Analysis**

    Clone the repository.
    Open the Amazon .Rmd file in RStudio.
    Knit the .Rmd file to produce the full analysis report, including visualizations and model outputs, or run the code chunks sequentially to reproduce the analysis step-by-step.
**Project Overview**

This project is a comprehensive analysis of Amazon product listings aimed at understanding pricing strategies, customer satisfaction, and market segmentation. The analysis leverages statistical and machine-learning models to explore the relationships between product features, ratings, and prices.
Dataset

    Source: Amazon Sales Dataset by Karkavelraja J.
    Description: The dataset contains product details such as product_name, category, discounted_price, actual_price, rating, and more. It provides a rich source of information for analyzing how pricing and product features relate to customer satisfaction on Amazon.

**Methodology**

    Data Collection & Preparation:
        Data was sourced from Kaggle and preprocessed to clean and format pricing information.
        Descriptive statistics and exploratory data analysis (EDA) were conducted to understand the data structure and distributions.

    Exploratory Data Analysis (EDA):
        A histogram was created to visualize the distribution of log-transformed discounted prices.
        A scatter plot was used to investigate the relationship between product ratings and prices.
        A bar chart showed the count of products across different categories.

    Statistical Modeling & Machine Learning:
        Linear Regression: Explored the relationships between product ratings, categories, and prices.
        K-means Clustering: Employed to segment the data into clusters based on ratings and prices.
        Gaussian Mixture Model (GMM): Used for advanced clustering to reveal hidden patterns in the data.

    Visualization & Insights:
        Word clouds provided an overview of frequently used terms in product descriptions.
        Violin plots highlighted the distribution of product ratings, showing a high density of ratings in the 4-5 range.
        Sentiment analysis assessed the sentiment scores of product descriptions, indicating that most are positively worded.

**Key Findings**

    Pricing Patterns: The log-transformed price distribution revealed multiple peaks, indicating clusters around certain price points.
    Ratings vs. Prices: A scatter plot showed that higher product ratings do not necessarily correlate with higher prices.
    Category Insights: Products in categories like Electronics, Computers & Accessories, and Home & Kitchen were most common.
    Clustering Results: K-means and GMM clustering identified distinct groups of products based on their pricing and ratings.

**Project Structure**

    amazon.csv: The main dataset containing product listings and attributes.
    Amazon .Rmd: The RMarkdown file containing the code for data analysis, visualization, and modeling.
    DATASCIENCE PROJECT.pptx: A presentation summarizing the project's objectives, methodology, and key insights.
    README.md: This file provides an overview of the project, its structure, and how to navigate the repository.

**How to Run the Analysis**

    Clone the repository.
    Open the Amazon .Rmd file in RStudio.
    Run the code chunks sequentially to reproduce the analysis, visualizations, and models.

**Libraries & Tools Used**

    R Packages:
        dplyr: Data manipulation.
        ggplot2: Data visualization.
        mclust: Gaussian mixture models.
        tm, sentimentr: Text mining and sentiment analysis.
        wordcloud: Creating word clouds.
    Tools:
        RStudio for code execution and visualization.
        PowerPoint for presentation.

**Summary & Learnings**

This project provided insights into consumer behavior on Amazon through data analysis and statistical modeling. It highlighted the complex relationship between pricing and ratings, the importance of product categories, and the value of clustering for market segmentation. It also served as a learning experience in applying machine learning techniques such as K-means and GMM to real-world e-commerce data.
