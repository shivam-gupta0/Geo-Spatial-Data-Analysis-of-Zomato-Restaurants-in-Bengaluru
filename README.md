# Geo-Spatial-Data-Analysis-of-Zomato-Restaurants-in-Bengaluru
This data analysis project focuses on analyzing data from Zomato, a popular online food delivery platform, using SQLite as the database. The project includes various scripts for data cleaning, exploratory data analysis, and data visualization. The primary objective of this project is to explore the relationships between different factors such as restaurant rating, cost, online ordering, and more, with the aim of providing valuable insights for both customers and restaurant owners.<br>
The project investigates the correlation between a restaurant's rating and its online order option. By creating frequency tables, the project determines the number of restaurants with specific ratings (e.g., 0, 1, 1.2, 1.4, 1.6) and whether they accept online orders or not. Analyzing these frequency tables helps identify any potential correlation between rating and online order acceptance.
<br>
# Installation <br>
To run this project, you need to have Python 3 and the following libraries installed:

numpy <br>
matplotlib<br>
seaborn<br>
sqlite3<br>
pandas<br>
plotly<br><br>
You can install these libraries using pip.<br><br>

# Usage<br>
Clone the repository<br>
Open the Jupyter notebook Zomato_analysis.ipynb in Jupyter Notebook or Google Colab<br>
Run the cells to see the analysis<br><br>

# Data<br>
The data used in this project is available in the zomato_rawdata.sqlite file.<br><br>

# Plots<br>
The following are some of the plots that are included in the project:<br>


**Top 20 Restaurant Types in Bangalore**<br>

![4](https://github.com/shivam-gupta0/Geo-Spatial-Data-Analysis-of-Zomato-Restaurants-in-Bengaluru/assets/85798077/abf73089-dc8f-4627-99fb-d3c6cfae41ac)<br><br>


**Top 20 Restaurants by Average Rating**<br>
![newplot1](https://github.com/shivam-gupta0/Geo-Spatial-Data-Analysis-of-Zomato-Restaurants-in-Bengaluru/assets/85798077/8bba077a-c577-41c3-9907-5057b039ca81)<br><br>



**A stacked bar chart showing the frequency of restaurants accepting or not accepting online orders at different ratings.**<br>

![3](https://github.com/shivam-gupta0/Geo-Spatial-Data-Analysis-of-Zomato-Restaurants-in-Bengaluru/assets/85798077/c8ffe95e-405e-4637-a5b2-5346588587ac)
<br><br>

**A scatter plot showing the relationship between the cost for two people and the rating of the restaurant.**<br>

![5](https://github.com/shivam-gupta0/Geo-Spatial-Data-Analysis-of-Zomato-Restaurants-in-Bengaluru/assets/85798077/9fa19d64-28ea-424d-9ff4-cd903938116e)


<br><br>

**Top 20 Famous Restaurant Chains in Bangalore by Number of Outlets**<br>

![download (4)](https://github.com/shivam-gupta0/Geo-Spatial-Data-Analysis-of-Zomato-Restaurants-in-Bengaluru/assets/85798077/9a112e85-4b7a-40ca-a0e6-c9afd7bb3bfc)<br><br>


**Trigram Analysis of customer reviews**<br>
![9](https://github.com/shivam-gupta0/Geo-Spatial-Data-Analysis-of-Zomato-Restaurants-in-Bengaluru/assets/85798077/41c576b3-1514-4f3d-aae9-9980ea904a2d)


**Distribution of cost for 2 people**<br>

![8](https://github.com/shivam-gupta0/Geo-Spatial-Data-Analysis-of-Zomato-Restaurants-in-Bengaluru/assets/85798077/502ee134-91ce-4a2f-9e64-ec07ed0218f4)<br><br>


**Top 10 Most Popular Cuisines in Bangalore.**<br>
![7](https://github.com/shivam-gupta0/Geo-Spatial-Data-Analysis-of-Zomato-Restaurants-in-Bengaluru/assets/85798077/ceb40fb2-f259-4676-8ba3-f1142d940908)



**Wordcloud of dishes liked by cuisines.**<br>

![download (1)](https://github.com/shivam-gupta0/Geo-Spatial-Data-Analysis-of-Zomato-Restaurants-in-Bengaluru/assets/85798077/c897db39-0476-4462-8020-61c012e059c9) <br><br>

**Top 10 Restaurant Locations by Number of Restaurants.**

![download (3)](https://github.com/shivam-gupta0/Geo-Spatial-Data-Analysis-of-Zomato-Restaurants-in-Bengaluru/assets/85798077/a5b1dd5c-6b30-4ab8-8988-5bb868114b1c)


**Geographical analysis** <br>
![Screenshot 2023-05-15 180905](https://github.com/shivam-gupta0/Geo-Spatial-Data-Analysis-of-Zomato-Restaurants-in-Bengaluru/assets/85798077/ec5f7a3d-c9de-4201-965d-13f7518e1245)


# Conclusion and Insights:<br>

Restaurant Locations: The project reveals that Bangalore's central area, including BTM, HSR, and Koramangala 5th block, has the highest concentration of restaurants, with BTM having the most significant number of restaurants. This information can assist entrepreneurs in identifying potential locations for their new ventures.<br>

Online Order and Rating Correlation: The scatter plot analysis shows that highly-rated restaurants mostly accept online orders, indicating a positive correlation between rating and online order acceptance. Additionally, restaurants accepting online orders tend to be more budget-friendly.<br>

Cost Distribution: The bar plot illustrates the distribution of approximate costs for two people, giving insights into the cost range of restaurants in Bangalore. This information can help customers plan their dining experiences based on their budget.<br>

Popular Cuisines: By analyzing the data, the project identifies the most popular cuisines in Bangalore. This insight can be valuable for customers seeking specific culinary experiences.<br>

Restaurant Chains: The project highlights popular restaurant chains in Bangalore, such as Empire, Beijing Bites, and Mani's Dum Biryani. Exploring these chains further can provide valuable insights into successful restaurant operations.<br>

Customer Reviews: The project analyzes customer reviews and identifies frequently mentioned terms related to food, taste, service, and specific dishes. This information can help restaurant owners understand customer preferences and improve their offerings.<br>

Geographic Insights: The heatmap analysis provides insights into the density and distribution of restaurants across Bangalore. Central Bangalore emerges as a hotspot for dining out, while the number of restaurants decreases as we move away from the central area. This observation can guide restaurant entrepreneurs in choosing suitable locations for their ventures.<br>

Overall, this data analysis project sheds light on various aspects of the restaurant industry in Bangalore. The insights gained from this analysis can be valuable for customers, restaurant owners, and potential entrepreneurs looking to make informed decisions and improve their experiences in the dynamic food scene of Bangalore.<br>

# Credits
The data used in this project was sourced from Kaggle.<br>

The inspiration for this project came from the Zomato Data Analysis project on Kaggle.<br>
