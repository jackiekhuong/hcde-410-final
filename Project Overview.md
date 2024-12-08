# Creating the Perfect Ice Cream

## Goals + Motivation:

The goal of this project is to understand what customers like about specific brands and flavors of ice cream in order to make thoughtful recommendations for future flavor profiles that are well-accepted and have the potential to become fan favorites. As a self-proclaimed ice cream enthusiast with over 20 years of ice-cream reviewing experience, I aim to use insights from data analysis and customer sentiment to guide these suggestions. By focusing on the top 10% of flavors, I will identify key ingredients, popular mix-ins, and the language that resonates most in flavor descriptions. While some ingredients are essential for making a cohesive ice cream product, this project will also highlight the "nice-to-haves" that elevate flavors to the next level. Through this study, I hope to provide practical, data-driven insights into both the technical and sensory aspects of ice cream creation, offering inspiration for crafting flavors that could become future favorites among consumers.

## Research Questions:
1. What are the common components of top-rated ice cream flavors?
2. How do different components interact to create highly-rated combinations?

## Hypotheses:
- Flavors like vanilla or chocolate may pair well with swirls like caramel or fudge.
- Creative mix-ins, such as cookie dough or chocolate chips, could enhance specific base flavors.
- `The combination of ingredients, rather than one perfect flavor, is likely the key to creating highly-rated ice cream.

## Previous Research
Currently there are very few if any academic papers published on the topic of finding the single best ice cream flavor. However, there are studies that have been done on more niche categories such as the best flavors within the "Better for You" category (L.R. Sipple). There are also studies that have been done on determining the best vanilla ice cream, or analyzing aspects of ice cream such as taste and texture. The past research, specifically the one analyzing the best in the "Better for You" category provides good insight in adgacent ways I could measure customer perception of ice cream. Overall there is a lot of research surrounding the fat content and relative mixture to create the "Best Ice Cream", however is little about the best flavor combination with regards to base flvor, swirls, and mix-ins which is what I aim to explore.

In terms of non-academic journals there have been a number of articles raking different ice-cream flavors. One in particular I found which influence my hypothesis was one from the Internation Dairy Foods Association, "Ice Cream Trends Survey with America’s Top Flavors, Toppings, and Ways to Eat Ice Cream". This article provided initial insight into current flavor trends and preferences for toppings which could potentially be related to mix-in preferences. They found Chocolate to be popular among their study participants as well as caramel as a swirl.

### Citation:
1. L.R. Sipple, C.M. Racette, A.N. Schiano, M.A. Drake,
    Consumer perception of ice cream and frozen desserts in the “better-for-you” category,
    Journal of Dairy Science,
    Volume 105, Issue 1,
    2022,
    Pages 154-169,
    ISSN 0022-0302,
    https://doi.org/10.3168/jds.2021-21029.
    (https://www.sciencedirect.com/science/article/pii/S0022030221010006)
2. International Dairy Foods Association. "What's the Scoop? IDFA Releases New Ice Cream Trends Survey with America's Top Flavors, Toppings, and Ways to Eat Ice Cream."
   International Dairy Foods Association, 14 July 2021, www.idfa.org/news/whats-the-scoop-idfa-releases-new-ice-cream-trends-survey-with-americas-top-flavors-toppings-and-ways-to-eat-ice-cream.

## Data Selection
The dataset for this project is sourced from Kaggle and includes ice cream products from well-known brands such as Ben & Jerry’s, Häagen-Dazs, Breyers, and Talenti. The dataset contains flavor names, descriptions, ingredients, ratings, and customer reviews. This data will be analyzed to identify the most successful ingredient combinations and how they contribute to high ratings.

## Methods:
### Data Cleaning and Preprocessing
The data will first be filtered to focus on top-rated ice creams (those in the top 10%). Missing values will be handled, and duplicates will be removed. Additionally, flavor descriptions will be preprocessed (lowercased, punctuation removed) to make them suitable for analysis.

### Identifying Key Ingredients:
A frequency analysis will be performed to identify the most common base flavors, mix-ins, and swirls. Visualizations, like bar charts, will help reveal these trends and allow comparisons between brands. Co-occurrence analysis will be conducted to determine how often different ingredients appear together, highlighting successful ingredient pairings.

### Ingredient Interaction Analysis:
Based on the frequency and co-occurrence insights, I'll analyze how certain ingredients interact to form well-loved combinations. This step will uncover pairings such as vanilla with caramel or chocolate with fudge, suggesting how combinations of flavors contribute to high ratings.

## Step-by-Step Process:

1. Clean and filter the dataset for top-rated ice creams.
2. Identify common ingredients (base flavors, mix-ins, swirls) and their frequencies.
3. Analyze co-occurrence of ingredients to find successful pairings.
4. Examine language in top-rated ice cream descriptions for common positive words.
5. Provide insights into ingredient combinations that are likely to result in high ratings.


## Unknowns and dependencies
One specific concern that should not be overlooked is that some of the data was collected through a promotion which could be a confounding factor of whether or not this is the true sentiment of the person. This should be addressed as a short coming of my study. 
