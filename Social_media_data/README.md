### README: Fake Social Media Activity Dataset

---

## **Fake Social Media Activity Dataset**

### **Description**
This project generates a realistic dataset simulating social media activities, including user profiles, posts, likes, and comments. The dataset can be used for data analysis, testing machine learning models, or exploring social media interactions.

### **Features**
- Generate **user profiles** with names, usernames, emails, and bios.
- Create **posts** with content and timestamps.
- Simulate **likes** on posts by random users.
- Add **comments** on posts, including the user who commented, the post, and the timestamp.
- Save all generated data to **CSV files** for easy access and analysis.

---

### **Technologies Used**
- **Python**: Programming language used for data generation and file handling.
- **Faker**: Library for generating realistic fake data.
- **CSV**: Format for storing and accessing the generated data.

---

### **Dataset Structure**

#### **1. Users**
File: `users.csv`

| **Field**     | **Description**                      |
|---------------|--------------------------------------|
| `user_id`     | Unique identifier for the user.      |
| `name`        | Full name of the user.               |
| `username`    | Social media username.               |
| `email`       | Email address of the user.           |
| `bio`         | Short bio or description of the user.|

---

#### **2. Posts**
File: `posts.csv`

| **Field**     | **Description**                      |
|---------------|--------------------------------------|
| `post_id`     | Unique identifier for the post.      |
| `user_id`     | ID of the user who created the post. |
| `content`     | Content of the post.                 |
| `timestamp`   | Date and time the post was created.  |

---

#### **3. Likes**
File: `likes.csv`

| **Field**     | **Description**                      |
|---------------|--------------------------------------|
| `like_id`     | Unique identifier for the like.      |
| `user_id`     | ID of the user who liked the post.   |
| `post_id`     | ID of the liked post.                |

---

#### **4. Comments**
File: `comments.csv`

| **Field**       | **Description**                     |
|-----------------|-------------------------------------|
| `comment_id`    | Unique identifier for the comment.  |
| `user_id`       | ID of the user who commented.       |
| `post_id`       | ID of the commented post.           |
| `comment_text`  | Content of the comment.             |
| `timestamp`     | Date and time the comment was made. |

---

### **How to Run the Project**

1. **Install Required Libraries**:
   Ensure Python is installed. Install the Faker library:
   ```bash
   pip install faker
   ```

2. **Run the Script**:
   Execute the script to generate the dataset:
   ```bash
   python social_media_dataset_generator.py
   ```

3. **Output Files**:
   The following CSV files will be generated:
   - `users.csv`
   - `posts.csv`
   - `likes.csv`
   - `comments.csv`

---

### **Use Cases**
- Testing social media algorithms.
- Analyzing user interactions on social media platforms.
- Training machine learning models on social media data.
- Simulating social network activities for academic purposes.

---

### **Customization**
You can adjust the number of users, posts, likes, and comments by modifying the following variables in the script:
- `num_users`: Number of users.
- `num_posts`: Number of posts.
- `num_likes`: Number of likes.
- `num_comments`: Number of comments.

---

### **Example**
A sample dataset will include:
- Users: 50 profiles with realistic names and bios.
- Posts: 200 posts with content and timestamps.
- Likes: 500 likes by users on random posts.
- Comments: 300 comments with text and timestamps.

---

