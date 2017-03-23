# Pig
I attached data files in CSV format for manupulation.
this is collection of some example solution of following problems

1. Write a Pig Latin query that outputs the login of all users in NY state. Expected Output format is:
                           User Login	| User Name |	State
                           
2. (5 points) Write a Pig Latin query that returns all the tweets that include the word 'favorite', ordered by tweet id.
  Expected format is:                              
                        tweet id	| Tweeted Message | 	User Login
                        
3. Write the equivalent join as in previous question using Pig Latin.
    Expected Output:
       User Login	| User Name | 	State	| tweet id	| Tweeted Message	| User Login
       

4. Write a Pig Latin query that returns the number of tweets for each user name (not login). You should output one user per line, in the following format: 
             User Name | number_of_tweets
             
5. Write a Pig Latin query that returns the number of tweets for each user name (not login), ordered from most active (maximum number of tweets) to least  (minimum number of tweets) active users. You should output one user per line, in the following format
           User Name | number_of_tweets
           
6. Write a Pig Latin query that returns the name of users that posted at least two tweets. You should output one user name per line.

7. Write a Pig Latin query that returns the name of users that posted no tweets. You should output one user name per line.
 
