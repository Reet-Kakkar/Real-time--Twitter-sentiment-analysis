# Real-time--Twitter-sentiment-analysis
This project performs real-time sentiment analysis on Twitter data using Twitter API keys. It collects tweets based on specified keywords, processes the text data, and classifies sentiment as positive, negative, or neutral. The analysis helps understand public opinion and trends around topics in real-time.

# Explanation 

In this project, I performed real-time sentiment analysis on tweets related to specific topics, such as cryptocurrencies, using the Twitter API.I got API secret key and other necessary tokens for real-time sentiment analysis, by creating a Twitter Developer account and registering on Twitter Developer Portal. After setting up the app, I was able to access the API Key, API Secret Key, Access Token, and Access Token Secret, which are required to authenticate and interact with the Twitter API for data collection.Then, preprocessed the data to clean the text, and then applied sentiment analysis using the Flair library. The sentiment of each tweet is classified as positive, negative, or neutral, providing insights into public opinion and trends related to a particular topic. The results are printed in real-time to monitor sentiment changes continuously.

# Conclusion
This project successfully shows how we can analyze real-time Twitter data to understand people's opinions on topics like crypto (which I used in this code). By using the Twitter API and Flair’s pre-trained sentiment analysis model, we can quickly sort tweets into positive, negative, or neutral categories. This approach allows us to track trends and get insights into what people are saying about certain subjects. 

# Future work
In the future, this project can be expanded by adding **A/B testing** to compare different strategies and see which ones work better for targeting specific audiences or understanding how different types of tweets affect sentiment. We could also improve the way we show sentiment trends over time by using better **visualization tools**. The sentiment analysis model could be made even more accurate by training it with **specific datasets** related to the topic. Additionally, connecting this project to **real-time dashboards** or **alert systems** would help businesses to react quickly to changes in public sentiments
