
#  BOOK RECOMMENDATION SYSTEM

![image](NAME.jpeg)


## BUSINESS UNDERSTANDING
## OVERVIEW
In the era of exponential data growth, the emergence of more sophisticated systems leveraging big data has become increasingly prevalent. Among these systems, recommendation systems have proven to be valuable information filtering tools, enhancing search results by providing users with more relevant items based on their search queries or browsing history. Major technology companies have embraced recommendation systems across various applications: YouTube utilizes them to determine the next autoplay video, while Spotify employs them to curate personalized "Made for You" daily mixes.
In line with this project's objectives, we aim to harness the power of data analysis to recommend the best books to users. By examining user behaviors, both individual and collective, we can derive insights that enable us to deliver tailored book recommendations that align with their interests and preferences.
The underlying principle of this project is to leverage data-driven techniques to understand user preferences and behaviors. By analyzing user interactions, historical data, and patterns, we can uncover valuable insights that inform our recommendation system. This allows us to present users with a curated list of book suggestions that are highly likely to resonate with their tastes.


### Main Objective
To develop a book recommendation system that provides personalized suggestions to users based on behaviors and preferences of similar users..

### Specific Objectives

1. To analyze top book sales per city
  
2. To find the most popular books so as to infer genres
   
3. To find most popular authors
   
4. To find the voting frequency of the users

## DATA UNDERSTANDING
Our dataset is from [here](http://www2.informatik.uni-freiburg.de/~cziegler/BX/

The Book-Crossing dataset comprises three files:

1. Users: Contains anonymized user data, including user IDs (User-ID), demographic information (Location, Age), and NULL values for missing demographic data.
2. Books: Provides information about books, including ISBNs, book titles (Book-Title), authors (Book-Author), year of publication (Year-Of-Publication), publishers (Publisher), and URLs to cover images on Amazon.
3. Ratings: Contains book rating information, including explicit ratings on a scale of 1-10 (Book-Rating) and implicit ratings expressed as 0.

## MODELS IMPLEMENTED

The following models are implemented in this project:

1. KNNWithMeans

2. Nearest Neighbours

3. SVD SVDpp

4. SVD


## EVALUATION
The project's success criteria is determined by achieving a Root Mean Squared Error (RMSE) of 3.30. 

## FINDINGS
1. `Skewed Ratings`: The ratings distribution is highly skewed, with a significant portion of ratings being zero. This indicates that a large number of users may not have provided explicit ratings for the books.
   
2. `Prevalence of Higher Ratings`: Higher ratings, particularly rating 8, appear to be more prevalent among users. This implies that a considerable number of users have given positive ratings to the books they have read.
   
3. `User Interaction and Location`: The city of Toronto has the highest count of user interactions with the book community website. This could be influenced by factors such as the city's population size and the popularity of reading among its residents. Other states have relatively similar user counts, indicating a relatively balanced user distribution.
   
4. `User Location Privacy`: The "n/a" category represents users who interacted with the book crossing website but preferred to keep their locations private.
   
5. `Popular Authors` may  indicate the popularity of specific genres associated with these authors, such as horror for Stephen King and romance for Nora Roberts.
   
6. `Popular Books`: Some books stand out in readership suggesting its popularity among readers. Factors like author reputation, book quality, and engaging storytelling may contribute to its popularity.

## RECOMMENDATIONS

1. `Encourage Explicit Ratings`: Since a significant portion of ratings is zero, it is important to encourage users to provide explicit ratings for the books they have read. This can be done by implementing rating prompts, offering incentives, or providing a user-friendly rating system.
   
2. `Highlight Highly Rated Books`: Identify and showcase books that have received high ratings.
   
3. `Tailor Recommendations by Location`: Since user interaction varies across different locations, consider providing personalized book recommendations based on the user's location.
   
4. `Genre-based Recommendations`: Take advantage of the popularity of specific authors and genres. Recommend books by popular authors like Stephen King for users interested in horror or Nora Roberts for those who enjoy romance.
   
5. `Promote Popular Books`: Highlight the books that have stood out in readership and gained popularity. These books have shown to resonate with readers, and promoting them can increase their visibility and attract more readership.
   
6.  `Stocking their book repository`: Considering the popularity of certain books and authors, it would be beneficial to stock libraries with similar content that aligns with the preferences of the target audience.

   ## CONCLUSIONS
 The optimised SVD model performed better than the other models with a Root Mean Squared Error of 3.30.
 
- Features such as genres and author popularity greatly influence book purchases.
  
- While our models scaled well its worth noting that we could have done better by implementing a content-based recommender system to solve for the "cold start " problem (where a new user has no history).
  
- We also faced the challenge of insufficient data which would have greatly improved model performance.

### Author and Acknowledgement:
Special thanks to our Moringa School Data Science Technical Mentors for their guidance throughout the project. We would also like to acknowledge the contributions of the Elites team members:

- Ronald Nyagaka
- Sharon Atieno
- Pamela Awino
- [Isaac Muturi](https://github.com/Isaac-Ndirangu-Muturi-749)
- Leonard Rotich
- Paul Musau
