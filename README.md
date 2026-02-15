# CodeBook: Pure Python Social Media Analytics 💻

This project serves as a comprehensive Data Science technical challenge for **CodeBook**, a social media platform for developers. The goal was to build a functioning recommendation engine using **Pure Python** only—strictly avoiding libraries like Pandas or NumPy to demonstrate foundational algorithmic thinking.

## 🚀 Key Features
* **Custom Data Pipeline:** Built a robust JSON loader to handle user data dumps and connection maps.
* **Algorithmic Data Cleaning:** Implemented logic to handle missing values, remove duplicate friend entries, and prune inactive users with zero connections.
* **"People You May Know" Engine:** Developed a friend recommendation algorithm based on mutual connection density.
* **"Pages You Might Like" Engine:** Built a collaborative filtering system that suggests pages based on shared user interests.

## 🛠️ Technical Concepts Applied
* **Advanced Data Structures:** Intensive use of Nested Dictionaries and Sets for efficient $O(1)$ lookups in the social graph.
* **Functional Logic:** Applied list comprehensions and lambda-based sorting for ranking recommendations.
* **Data Integrity:** Used standard Python `json` and `io` modules to ensure persistent data cleanliness.

## 📊 How It Works
1. **The Recommendation Logic:** The engine identifies mutual friends between non-connected users.
2. **The Scoring System:** Suggestions are ranked by the number of mutual connections—higher mutual counts result in higher recommendation priority.
3. **Collaborative Filtering:** If two users share a common liked page, the engine suggests the remaining pages from one user to the other.

## 💻 Environment
* **Language:** Python 3.x (Pure)
* **IDE:** Jupyter Lab / Kiraenv
