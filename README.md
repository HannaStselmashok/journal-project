# About
Ballife - is an online lifestyle journal. There are several categories: history, sport, food, etc. Each registered user can post and comment on articles. 
There are 4 tables in the database:
- Users
- Category
- Article
- Comment
## EER Diagram
![image](https://github.com/HannaStselmashok/journal-project/assets/99286647/6631b72c-8fe6-4925-9c21-a9ae0725aa27)

# Questions to be answered
## 1. Average age of users
To find an average age of users in each category.

**Query**

![image](https://github.com/HannaStselmashok/journal-project/assets/99286647/8235d135-502d-4501-a531-2e5ec297f48a)

**Result**

![image](https://github.com/HannaStselmashok/journal-project/assets/99286647/5fdd3b95-37b7-4192-bf56-c6926d9c1449)

## 2. Popular article
To find the article with the maximum amount of comments.

**Query**

![image](https://github.com/HannaStselmashok/journal-project/assets/99286647/952b542e-2c61-42fd-88c4-d1c735ac298b)

**Result**

![image](https://github.com/HannaStselmashok/journal-project/assets/99286647/f40cdf65-0a81-4027-b6e6-405e695921a9)

PS I decided to use subquery instead of LIMIT 1 because there could be several articles with the largest number of comments.

## 3. Average age of users writing about SQL

**Query**

![image](https://github.com/HannaStselmashok/journal-project/assets/99286647/2902fb21-3e85-4ac7-8942-e7637a47b63e)

**Result**

![image](https://github.com/HannaStselmashok/journal-project/assets/99286647/0b16b3d4-f6a8-4210-9d85-87933c041fb7)

## 4. Amount of articles each author published, grouped by month

**Query**

![image](https://github.com/HannaStselmashok/journal-project/assets/99286647/9b4858f9-993e-4479-932b-691a2ef9d715)

**Result**

![image](https://github.com/HannaStselmashok/journal-project/assets/99286647/20aafb65-b842-4ed6-8a2d-52ba8dc8d1b9)

## 5. The most active author
Author(s) who wrote the largest amount of articles

**Query**

![image](https://github.com/HannaStselmashok/journal-project/assets/99286647/426c3ecb-6759-43dc-aead-c3b1321f7ce2)

**Result**

![image](https://github.com/HannaStselmashok/journal-project/assets/99286647/bf71e4de-6bd6-4040-aa87-fe322608e4df)




