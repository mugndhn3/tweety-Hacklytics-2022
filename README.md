# tweety-Hacklytics-2022
Tweety - an NLP based tool used to study the replies to tweets created by Harini Narasimhan, Michael Murillo-Martinez, Mugundhan Murugesan  

## Inspiration  
Expression: One of the first steps of mental health and well being​A common fear among people posting on social media is that someone will have a strong negative reaction to something you share.​These comments have a negative impact on the mood of the user. What if there are negative comments on a user posting about mental health problems. It may push them over the edge.​

## What it does  
The tool finds tweets about Mental Health and collects replies for each tweet. If the tweet has an overall of negative replies, a chatbox replies to the user tweet with a positive message to help them feel better.

## How we built it  
We used Python to scrape tweets and replies and used NLP neural network model to predict the negativity of the replies with their confidence values. Then, we used selenium to create a bot that can navigate the tweets with negativity and can reply with a positive message to that tweet.

## Challenges we ran into  
Scraping the replies to each tweet was very challenging and time-consuming.

## Accomplishments that we're proud of  
We were able to navigate tweets based on the topic "Mental Health" and scrape comments for each of the tweets.

## What we learned  
We learned that there are some tweets where people express negativity and that needs to be addressed. We learnt a ton of new libraries, packages and tools such as Deepnote and Selenium.

## What's next for Tweety  
Generalizing the tool to study the user tweet replies on any topics Expanding it to other social media sites. Develop a virtual chatbot that can reply positively to the tweets of users with more negativity.

## Built With  
deepnote  
machine-learning  
natural-language-processing  
nerodia  
python  
selenium  
sentiment-analysis-online  
