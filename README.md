# Project3-Udacity-Data-Scientist

This project involves Recommendation Engines. These are the algorithms used to make suggestions or recommend things to you based on past purchases or usage, or based on what other users are buying or downloading. For example, think of early Point of Sales systems that would tell cashiers to make suggestive sales like “if they are purchasing nails suggest a new hammer as well.” Nowadays, apps like Netflix have Recommendation Engines in place which suggest movies that you might also enjoy based on what you have been streaming or enjoying in the past or based on what is most popular with other users.

<img src='https://media-cldnry.s-nbcnews.com/image/upload/t_fit-1240w,f_auto,q_auto:best/streams/2013/November/131113/2D9672564-attachment.jpg'/>
Source: https://www.nbcnews.com/technolog/netflix-makeover-brings-improved-search-recommendations-2d11582698 Netflix makeover brings improved search and recommendations by Devin Coldewey

---
This project involves analyzing the interactions users have with articles on the IBM Watson Studio platform and making recommendations to them about new articles I think they will like by creating a Recommendation Engine. The bulk of the work involves my analysis of the data in the Jupyter Notebook: Recommendations_with_IBM.ipynb. At one point I also considered building a web application to the IBM Cloud that showcases many of the lessons we learned in previous projects, however, I abandoned that idea and will apply this instead on my 4th and final Capstone project. For this project I wil be showing the following lessons learned:

* Code Functionality & Readability: This Github repository showing Code Quality, Code Functionality, passing tests in the Juypter Notebook, and well-documented code using functions and classes as necessary
* Data Exploration: The Jupyter Notebook Recommendations_with_IBM.ipynb shows how I explored that data and came up with a way to do futher Content Based recommendations, including a "take 2" redo where we had to go back and rethink our strategy
* Rank Based, Collaborative Filtering, and Matrix Factorization Recommendations: The Jupyter Notebook Recommendations_with_IBM.ipynb will futher show the different kinds of recommendation strategies I have learned and tests of this logic

As in my previous project, I have also documented the work in the blog below:

My BLOG is HERE: https://hmelendez001.github.io/2021/12/22/Udacity-Data-Scientist-Nanodegree-Project-3.html

# Libraries Used
| Library | Description |
| :--- | :--- |
| Numpy | This is where numerical constants like np.nan came from|
| Pandas | This is the work horse behind our analysis for reading in the DataFrame from the CSV file and performing various data analysis and preparation |
| Pickleshare | This is the utility used to store the trained and optimized model for reuse by the UI web application dashboard |
| Pillow | A dependency for Word Cloud |
| Wheel | A dependency for Word Cloud |
| Wordcloud | This was used to generate the word clouds for determining top words used in content recommendation |

# Files in this Repository
| File | Description |
| :--- | :--- |
| data | The directory contaning the raw data for this project |
| data > articles_community.csv | The raw data containing the article content including full name, description, etc. |
| data > user-item-interactions.csv | The raw data containing the individual user to IBM article interactions |
| project_tests.py | The module used to test the results of our analysis |
| top_10.p | Picke file used by project_tests.py to check the results of the analysis |
| top_20.p | Picke file used by project_tests.py to check the results of the analysis |
| top_5.p | Picke file used by project_tests.py to check the results of the analysis |
| README.md | The file you are currently reading |
| Recommendations_with_IBM.html | The HTML version of the executed Jupyter Notebook |
| Recommendations_with_IBM.ipynb | The Jupyter Notebook containing the analysis and code for this project |
| requirements.txt | The required pip install versions of each dependent module |
| runtime.txt | The minimum python version runtime |
| wordcloud-1.8.1-cp39-cp39-win_amd64.whl | Included the pre-compiled, binary only, version of wordcloud otherwise we get an error when we pip install wordcloud with python 3.6 and higher of error: Microsoft Visual C++ 14.0 or greater is required |

# Summary of the results
The IBM Cloud article recommendation engine analysis was a great learning exercise in Rank Based, Collaborative Filtering, and Matrix Factorization Recommendations.
  
Given more time I would have created a Flask web application dashboard to showcase the recommendation engine and either deployed to the IBM Cloud or Heroku like we did with our prior project 2. Instead I have decided to put the time and effort into the final Project 4 or the final Capstone Project.

# Acknowledgements
Several code snippets came from previous lessons in our Udacity Data Scientist program. Also, where employed I have credited various contributors from StackOverflow.com, geeksforgeeks.org at https://www.geeksforgeeks.org/, https://www.tutorialspoint.com/ for sample plotly graphs, and the Data Science Stack Exchange at https://datascience.stackexchange.com. A big thank you to our instructors and all those involved in the Udacity program.
