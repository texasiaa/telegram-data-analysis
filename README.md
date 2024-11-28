# Telegram Data Exploratory Analysis

This project is aimed at analysing personal data in Telegram, the data here're chats, messages and users. 
In the research are used NLP analysis, sentimental analysis, TF-IDF analysis and basic data analysis.

## Structure
- collecting&preparing the data
- analysis

## Collecting&preparing the data 

1. Request an API from Telegram
2. Download the data
- For downloadind your data use code here [https://github.com/SanGreel/telegram-data-collection](https://github.com/SanGreel/telegram-data-collection)
3. Turn the data into dataframe
- For grouping the data use code here [https://github.com/SanGreel/telegram-dialogs-analysis-v2](https://github.com/SanGreel/telegram-dialogs-analysis-v2)

## Analysis
### content:
1. Most active days of the week
2. Most active hours of the day
3. Hours of sleep analysis
4. Most common people, which messages were forwarded
5. Distribution of forwarded messages over the time
6. Types of forwarded messages
7. People who've been texted the most to at the begining of full-scale invasion
8. Most common emojis
9. Number of people who hide vs unide their phone number
10. Number of private messages received on holidays 
11. Changes in activity during exams period
12. Activity dynamics depending on year seasons
13. Most common channels which messages were forwarded by specific person
14. Average length of the message
15. Average duration of the conversation
16. Most common words used/received
17. Most common phrases used/received 
18. Most common messages' reactions
19. TF-IDF analysis
20. Sentimental analysis 
21. Most common cuss words used

## Further work

1. Project improvement ideas
- do some more sentimental analysis
- more analysis for convo duration
- a new lib for visualization
- take more samples of data

2. Analysis ideas
- download more info (does user have pfp/description/channel pinned etc.) for analysis
- types of channels (theme)
- built graph that shows people connections through groups
- news channels analysis

## Sources
1. [Ukrainian stopwords](https://github.com/skupriienko/Ukrainian-Stopwords/tree/master)
2. [Lemmatization dicts](https://github.com/SanGreel/tone-dict-ukrainian/tree/master/dicts)
3. [Cusswords list (modified)](https://github.com/Behiwzad/swearify/tree/master)


## Author

Maria Cherkasova
