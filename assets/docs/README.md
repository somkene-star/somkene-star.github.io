# Objective

- What is the key pain point?
The Head of Marketing is looking to identify the leading YouTubers in 2024 to determine the most suitable influencers for running marketing campaigns for the remainder of the year.

- What is the ideal solution?
To create a dashboard that provides insights into the top UK YouTubers in 2024 that includes their

- subscriber count
- total views
- total videos, and
- engagement metrics
  
This will help the marketing team make informed decisions about which YouTubers to collaborate with for their marketing campaigns.

# User story

As the Head of Marketing, I want to use a dashboard that analyzes YouTube channel data in the UK. This dashboard should enable me to identify the top-performing channels based on metrics like subscriber count and average views. With this information, I can make more informed decisions about which YouTubers are the best fit for collaboration, thereby maximizing the effectiveness of each marketing campaign.


# Data source

What data is needed to achieve our objective?
We need data on the top UK YouTubers in 2024 that includes their
- channel names
- total subscribers
- total views
- total videos uploaded

Where is the data coming from? The data is sourced from Kaggle (an Excel extract),
[see it here](https://www.kaggle.com/datasets/bhavyadhingra00020/top-100-social-media-influencers-2024-countrywise?resource=download)


# Design
## Dashboard componet required

What should the dashboard contain based on the requirements provided?
To determine the contents of the dashboard, we need to identify the key questions it should answer:

- Who are the top 10 YouTubers with the most subscribers?
- Which 3 channels have uploaded the most videos?
- Which 3 channels have the most views?
- Which 3 channels have the highest average views per video?
- Which 3 channels have the highest views per subscriber ratio?
- Which 3 channels have the highest subscriber engagement rate per video uploaded?

# Development
## Pseudocode

- What's the general approach in creating this solution from start to finish?
  
  1. Get the data
  2. Explore the data in Excel
  3. Load the data into SQL Server
  4. Clean the data with SQL
  5. Test the data with SQL
  6. Visualize the data in Power BI
  7. Generate the findings based on the insights
  8. Write the documentation + commentary
     Publish the data to GitHub Pages

# Data Exploration Notes

At this stage, we're examining the data for errors, inconsistencies, bugs, unusual or corrupted characters, etc.

- Initial Observations:
- . Data Coverage: There are at least four columns containing the data necessary for our analysis, indicating that we have     sufficient information without needing to contact the client for additional data.
- b. Channel ID Column: The first column contains what appears to be channel IDs, separated by an "@" symbol. We need to extract the   channel names from these IDs.
- c. Language Discrepancies: Some cells and header names are in a different language. We need to verify if these columns are required and, if so, address the language differences.
- d. Excess Data: The dataset contains more data than needed, so some columns will need to be removed.









