# Sentiment and Conversational Trends among Reddit users regarding South Korea 
## Analysis of the subset of 'self-contained' posts 

#### Project Objective:
This project aimed to analyze Reddit post titles mentioning South Korea and their associated comments, retrieved using the Reddit API. The analysis focused on insights related to the recently lifted martial law.


#### Data Retrieval
- Data was fetched using the **PRAW** library.
- The dataset consists of **unlabeled data**, requiring preprocessing and analysis to extract meaningful insights.
- Instructions for reproducing the results:
  - Use your own Reddit credentials to fetch data via the provided code.
  - Alternatively, work with the pre-saved CSV files.

#### Key Analysis Tasks
1. **Text Analysis**:  
   - Pre-processed Reddit post titles to identify the ten most common words.  
   - Applied **single linkage hierarchical clustering** to the titles, identifying eight distinct clusters.  

2. **Sentiment Analysis**:  
   - Focused on comments containing the term **'martial'**.  
   - Used the **VADER sentiment analysis tool** to compute normalized, weighted composite sentiment scores.  
   - Visualized sentiment scores over time.  

#### Technical Details
- **Environment**:  
  - Apple M3 chip  
  - 16GB RAM, 256GB SSD  
  - 8-core CPU (4 performance cores, 4 efficiency cores)  
  - 8-core GPU  

- **Tools & Libraries**:  
  - Python 3.11  
  - Jupyter Notebook
