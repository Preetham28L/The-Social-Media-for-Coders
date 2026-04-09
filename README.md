Social Network Recommendation System
📌 Project Overview

This project simulates a social networking platform where users can:

Connect with friends 
Like coding-related pages 
Get intelligent recommendations

The system provides:

- People You May Know (based on mutual friends)
- Pages You Might Like (based on shared interests)
Features
People You May Know
Suggests new friends using mutual connections
Ranks users based on number of shared friends
Pages You Might Like
Recommends pages based on common interests
Uses similarity between users’ liked pages
Handles Real-World Data Issues
Missing values (null)
Duplicate entries
Inconsistent data
Dataset Description

The dataset contains:

Users (25–30 records)
id: Unique user ID
name: User name (may contain duplicates or nulls)
friends: List of friend IDs
liked_pages: List of page IDs
Pages
id: Unique page ID
name: Page name (e.g., GitHub, LeetCode)

Dataset includes:
- Duplicate users
- Null values
- Repeated entries (to simulate real-world messy data)
- Technologies Used
- Python

Example Usage:
- People You May Know
Enter User ID to find 'People You May Know': 1
People You May Know: [5, 6, 7]
- Pages You Might Like
Enter User ID to find 'Pages You Might Like': 1
Recommended Pages: [104, 106, 107]
Jupyter Notebook 📓
JSON (for dataset storage)
Pandas (for data handling)
