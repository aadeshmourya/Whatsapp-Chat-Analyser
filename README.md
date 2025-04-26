# Whatsapp-Chat-Analyser

## Overview
The WhatsApp Chat Analyzer is a Python-based tool for analyzing chat data exported from WhatsApp. It provides various functionalities for preprocessing the data, extracting insights, and generating visualizations to better understand communication patterns and trends within the chat.

## Modules
1. **preprocessor.py**: Contains functions for preprocessing raw chat data, extracting essential information such as messages, dates, and user details, and structuring the data into a pandas DataFrame.

2. **helper.py**: Includes helper functions for statistical analysis, visualization generation, and other data processing tasks required for chat analysis.

3. **app.py**: Implements a web interface using Streamlit for the WhatsApp Chat Analyzer, allowing users to upload chat data files and interactively explore insights and visualizations.

## Libraries Used
- `pandas`: For data manipulation and analysis.
- `matplotlib`: For creating visualizations such as plots and charts.
- `seaborn`: For enhancing the aesthetics of visualizations.
- `urlextract`: For extracting URLs from chat messages.
- `wordcloud`: For generating word cloud visualizations.
- `emoji`: For handling emojis in chat messages.
- `collections`: For counting occurrences of elements in lists.
- `streamlit`: For building web applications with Python.

## Functions (app.py)
1. **fetch_stats(selected_user, df)**: Fetches statistics such as message count, word count, media messages, and links shared for the selected user or overall.

2. **most_busy_users(df)**: Identifies the most active users in the chat.

3. **create_wordcloud(selected_user, df)**: Generates a word cloud visualization based on chat messages for the selected user or overall.

4. **most_common_words(selected_user, df)**: Identifies the most common words used in chat messages for the selected user or overall.

5. **emoji_helper(selected_user, df)**: Extracts emojis used in chat messages for the selected user or overall.

6. **monthly_timeline(selected_user, df)**: Creates a timeline visualization of chat activity per month for the selected user or overall.

7. **daily_timeline(selected_user, df)**: Creates a timeline visualization of chat activity per day for the selected user or overall.

8. **week_activity_map(selected_user, df)**: Generates a map of chat activity by day of the week for the selected user or overall.

9. **month_activity_map(selected_user, df)**: Generates a map of chat activity by month for the selected user or overall.

10. **activity_heatmap(selected_user, df)**: Generates a heatmap of chat activity by day and hour for the selected user or overall.

## Implementation
To implement the project:
1. Clone the repository to your local machine.
2. Install the required libraries using `pip install -r requirements.txt`.
3. Run the `app.py` script to launch the web interface for the WhatsApp Chat Analyzer.
4. Upload chat data files and interactively explore insights and visualizations.

## Uses
- Social network analysis
- Customer feedback analysis
- Team collaboration optimization
- Sentiment analysis
- Personal insights and reflection
  
