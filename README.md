# Coders of Delhi 🧑‍💻

Coders of Delhi is a non-UI, JSON-based social media backend built entirely in Python. It simulates friend suggestions using mutual connection logic — think “People You May Know,” but for coders.

## 📌 Features

- Pure Python (no external libraries)
- JSON file-based data storage
- Suggests users based on mutual friends
- Simple, beginner-friendly logic
- Built while learning from Code With Harry’s Data Science course

Each user has:

-An id
-A list of friends (referencing other user IDs)
-Liked Pages

🧠 Logic Overview
1. *People You May Know*
-Checks direct friends
-Finds mutual friends
-Ranks suggestions by mutual count

2. *Pages You Might Like*
-Compares liked pages with other users
-Suggests new pages based on overlap
-Ranks pages by number of shared interests

📚 Credits
Built while following Code With Harry’s Data Science course.
Inspired by the logic behind real-world social networks.
