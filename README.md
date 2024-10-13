
# Stock Movement Analysis Based on Social Media Sentiment

This project analyzes stock movements by scraping data from Reddit, performing sentiment analysis on the posts, and identifying relationships between stock mentions and sentiment polarity.

The project involves scraping Reddit data using the asyncpraw library, performing sentiment analysis with vaderSentiment, and potentially applying topic modeling with LatentDirichletAllocation from scikit-learn. 


## Setup Instruction
Prerequisites:-

Python 3.7 or above.
Reddit API credentials (required for scraping Reddit data)
## Dependencies:

1:- praw
2:- asyncpraw
3:- pandas
4:- vaderSentiment
5:- nest_asyncio (for handling asynchronous tasks in Jupyter)
6:- scikit-learn

To run this project, you'll need to install the following Python packages:

pip install praw asyncpraw pandas vaderSentiment nest_asyncio scikit-learn

## Getting Reddit API Credentials

1:- Go to Reddit's Developer Page and create an application.
2:- Obtain the following:
    client_id
    client_secret
    user_agent
## How to Run

1:- Clone this repository:
    git clone <repo_url>

2;- Navigate to the project directory:
    cd <repo_directory>

3;- Open the Jupyter notebook:
    jupyter notebook Stock_Movement_Analysis_Based_on_Social_Media_Sentiment.ipynb

4:- In the notebook, update the Reddit API credentials in the code block where asyncpraw.Reddit is initialized:
reddit = asyncpraw.Reddit(
    client_id="your_client_id",
    client_secret="your_client_secret",
    user_agent="your_user_agent"
)

5:- Run all cells to scrape Reddit data, perform sentiment analysis, and analyze stock movements.


