# Amazon-Product-Analysis-Report

In this project, *I have analyzed a dataset of over 1,000 products listed on Amazon*.

The dataset includes details such as product name, category, price, rating, and user reviews . Our goal is to understand customer preferences, identify purchasing patterns, and develop a recommendation system to suggest products to users based on their interests. 🧐👨‍💻

Our project consists of the following steps:

📊 **Data collection**: I have collected the Amazon products dataset from Kaggle.

🧹 **Data preparation**: I have cleaned and preprocessed the dataset for analysis.

🕵️‍♂️ **Exploratory data analysis**: I have analyzed the data to understand the distribution of products by categories, customer ratings, and reviews.

📈 **Data visualization**: I have visualized the data to identify trends and patterns.


# **Data collection**

👋 I am going to be working on a project that involves analyzing data from Amazon - you know, the huge online retailer? 🛍️ They sell everything from books 📚 to electronics 📱 to groceries 🍎, so there's a lot to look at.

📊 The dataset I'll be using has information on over 1000 products sold by Amazon, like their names, categories, prices, ratings, and reviews. I am going to be digging into this data and figuring out what it all means, and how I can use it to help Amazon and its customers.

For Amazon, analyzing this data can help them understand which products are popular and which aren't, and they can use that information to figure out how to price and market things better. For customers, having access to this data can help them decide what to buy - if they see that a product has good ratings and lots of positive reviews, they'll be more likely to buy it. 💸

**Features**

product_id - Product ID

product_name - Name of the Product

category - Category of the Product

discounted_price - Discounted Price of the Product

actual_price - Actual Price of the Product

discount_percentage - Percentage of Discount for the Product

rating - Rating of the Product

rating_count - Number of people who voted for the Amazon rating

about_product - Description about the Product

user_id - ID of the user who wrote review for the Product

user_name - Name of the user who wrote review for the Product

review_id - ID of the user review

review_title - Short review

review_content - Long review

img_link - Image Link of the Product

product_link - Official Website Link of the Product


Used the dataset from: *https://www.kaggle.com/datasets/karkavelrajaj/amazon-sales-dataset*


# Data preparation
Before we dive into the data analysis and visualization, we need to make sure our dataset is clean and properly formatted. This process is called data preparation, and it involves several steps:

2.1 **Data Inspection**: We'll start by inspecting the dataset to see if there are any missing values, duplicates, or inconsistent data. We'll also check if the data types are correct and make sure the dataset is ready for analysis.

2.2 **Data Cleaning**: Next, we'll clean the dataset by removing or correcting any errors, inconsistencies, or irrelevant information. This will make the dataset more reliable and accurate.

2.3 **Data Transformation**: After cleaning the dataset, we may need to transform the data to make it more useful for analysis. This can include scaling, normalization, or feature engineering.

2.4 **Data Saving**: Once we've prepared the data, we'll save it in a new file to avoid overwriting the original dataset. This way, we can always go back to the original dataset if we need to.


# Data Analysis (EDA) & Data visualization

3.1 Analyze the distribution of products by category using a bar plot.

3.2 Analyze the distribution of customer ratings using a histogram.


Based on the results, we can gather the following insights:

🔍 The top three main categories are Electronics, Computers & Accessories, and Home & Kitchen. This shows that these categories are popular among customers.

🔍 The number of products in the other main categories is quite low, indicating that these categories are not as popular as the top three.

🔍 Office Products, Musical Instruments, Home Improvement, Toys & Games, Car & Motorbike, and Health & Personal Care have a very small number of products, which may suggest that these categories have less demand.

🔍 Overall, the data can help businesses understand the current market trends and identify potential opportunities for growth in specific categories.


Based on the results, we can gather the following insights:

🔍 The top six subcategories are USB cables, smartwatches, smartphones, smart televisions, in-ear headphones, and remote controls. These are the most popular subcategories, and businesses could focus on providing products in these categories to attract customers.

🔍 Other popular subcategories include mixer grinders, HDMI cables, dry irons, mice, and instant water heaters. These subcategories may be less popular than the top six, but they still have a significant number of products, indicating that there is demand for them.

🔍 The data shows that there is a diverse range of subcategories in the top 30, including kitchen appliances, home electronics, and personal accessories. This highlights the importance of offering a variety of products to cater to different customer needs and preferences.

🔍 Overall, the data can help businesses identify the most popular subcategories and adjust their product offerings to meet customer demand. By focusing on these subcategories, businesses could increase their sales and improve their competitiveness in the market.


The majority of customer ratings fall within the 3-4 and 4-5 range, with a total of 1453 reviews.

There is a noticeable increase in the number of reviews in the 2-3 range compared to the lower 0-1 and 1-2 ranges.

The lowest number of reviews is found in the 0-1 range, indicating that there may be room for improvement in terms of customer satisfaction.

Overall, the distribution of customer ratings suggests that most customers are satisfied with the products, but there may be opportunities for improvement to increase the number of positive ratings.
