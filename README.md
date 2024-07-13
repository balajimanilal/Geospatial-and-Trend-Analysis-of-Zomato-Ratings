# Geospatial-and-Trend-Analysis-of-Zomato-Ratings

The project aims to perform a geospatial and trend analysis of Zomato ratings using a dataset of restaurant reviews and ratings. The analysis involves data cleaning, transformation, and visualization to uncover insights about restaurant ratings, types, and review patterns.

# Key Findings

**Data Cleaning and Transformation:**
* Null values in the dataset were identified and managed.
* The 'rate' column was cleaned by replacing 'NEW' and '-' with NaN and converting the ratings to float type.
* The dataset was filtered to focus on specific restaurant types, such as 'Quick Bites'.

**Ratings Analysis:**
* The distribution of ratings was analyzed, and the ratings were normalized to compare the prevalence of online orders across different rating levels.
* Visualization showed the proportion of online orders for each rating level using stacked bar charts.

**Restaurant Types:**
* The 'rest_type' column was analyzed to understand the distribution of different types of restaurants.
* The dataset was filtered to focus on 'Quick Bites' restaurants for more detailed analysis.

**Review Text Analysis:**
* Reviews were tokenized and cleaned to remove stop words.
* Frequency distributions, bigrams, and trigrams were used to analyze common words and phrases in the reviews.

---

# Technologies Used
> * Pandas: For data manipulation and analysis.
> * NumPy: For numerical operations.
> * Matplotlib and Seaborn: For data visualization.
> * NLTK: For natural language processing, including tokenization and stop words removal.
> * Geopy and Folium: For geospatial analysis and visualization.
> * SQLite: For data storage and retrieval.
> * Visualization Tools: Matplotlib and Seaborn: Used to create various plots, including bar charts and stacked bar charts.
> * Folium: Utilized to create geospatial visualizations like heat maps.

# Conclusions
The analysis provided insights into how Zomato ratings are distributed and how different factors, such as restaurant type and review content, influence these ratings. By leveraging geospatial tools, the study also highlighted regional patterns in restaurant ratings. The combination of data cleaning, transformation, and visualization techniques allowed for a comprehensive understanding of the dataset and its trends.
