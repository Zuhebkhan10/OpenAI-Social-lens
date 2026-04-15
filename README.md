
OpenAI Social Lens: Instagram Audience Analytics

Overview:  
This project focuses on transforming unstructured social media profile data into a structured format using Python. It simulates a real-world data analytics workflow including data cleaning, 
transformation, and basic analysis.

Problem statement:
Raw social media data is often messy and unstructured, making it difficult to analyze. This project aims to:

Clean and preprocess raw text data,
Convert it into structured format (JSON),
Extract meaningful insights,

Features:
Reads unstructured text data from file

Parses individual profile information

Cleans and standardizes data (handles K/M values)

Performs analysis (max posts, followers, following)

Outputs structured JSON data

Tech Stack :
Python,
File Handling,
String Processing,
JSON

Workflow (ETL Process):
    Extract
    Load raw data from text file

Transform:
    Split profiles
    Parse fields (username, posts, followers, etc.)
    Convert K/M values into numeric format
    
Load:
    Store as list of dictionaries (JSON-like format)

Sample output:
{
'username': '_anujsinghal', 

'no_of_posts': 1785,

'no_of_followers': 681000, 

'no_of_following': 248, 

'name': 'Anuj Singhal',

'type_of_page': 'Digital creator', 

'bio': 'Managing Editor, CNBC-Awaaz.
}

Key Insights:

Identify profile with maximum posts

Identify profile with maximum followers

Identify profile with maximum following

How many category do we have how many people do we have.

