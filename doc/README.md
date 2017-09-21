# Project 1: 
## ql2273
### Introduction
U.S presidents’ inaugrual speeches are always hot topics after the ending of each presidential election. There are also a large amount of interesting points for text mining in the inaurgrual speeches. In this project, topics about length of sentences, clustering of emotions and wordclound will shown below.

### Length of sentences
The length of speeches and also the length of sentences in the speeches can will show us a brief perception of each speech. I use sentences as units of analysis for all these presidents’ speeches, and generate a plot showing numbers of words in a sentence each president used.

![image](figs/length_of_sentences.jpg)

As is shown above, it is not difficult to tell that president George Bush, Donald Trump, Lyndon Johnson, George W Bush and William Clinton are the top 5 presidents who would like to use short sentences in their inaugural speeches, while George Washington are most likely to use long sentences in his inaugural speech.

Here comes a question, what are those short sentences the top 5 presidents prefer to using?

1. George Bush
![image](figs/s_bush.jpg)

2. Donald Trump
![image](figs/s_trump.jpg)

3. Lyndon Johnson
![image](figs/s_johnson.jpg)

4. George W Bush
![image](figs/s_wbush.jpg)

5. William Clinton
![image](figs/s_clinton.jpg)

Obviously, words of thanks, god, bless are most likely to be existed in these five presidents' speeches, which probably tells us that they might not be talented formal speakers.

### Emotion analysis
Besides the length of sentences, the emotion is an interesting part to analyze as well.

![image](figs/emotion_trump&bush.jpg)

The plot above shows us how presidents alternate between long and short sentences and how their emotion changes between different sentiments in their speeches. It is interesting to find out those sentences made emotion change as well.

  Donald Trump
1) "No challenge can match the heart and fight and spirit of America."
2) "God bless you, and God bless America."                            
3） "America will start winning again, winning like never before."     
4） "No challenge can match the heart and fight and spirit of America."
5） "Today's ceremony, however, has very special meaning."             
6） "America will start winning again, winning like never before."     
7） "Today's ceremony, however, has very special meaning."             
8） "God bless you, and God bless America."

  George W Bush
1） "Abandonment and abuse are not acts of God;"
2） "God bless you all, and God bless America." 
3） "Where there is suffering, there is duty."  
4) "Abandonment and abuse are not acts of God;"
5) "God bless you all, and God bless America." 
6) "Abandonment and abuse are not acts of God;"
7) "Abandonment and abuse are not acts of God;"
8) "God bless you all, and God bless America."

For Donald Trump, the emotionally changed sentences are more like to be some inspiring slogans. While for George W Bush, the time he said sentences like “God bless you all” is the point he changed his emotions.


The emotion of the speech can be simply divided into two parts, positive and negative. Then I cluster these speeches into two groups.

![image](figs/cluster.jpg)

The most positive sentiment speech is made by the first president of United States of America, George Washington. The most negative sentiment speech is given by Warren Harding. We also can see most of the speeches are classified to the positive side.

### Word Cloud
![image](figs/wordc)overall.jpg)

This is the overall word cloud from all speeches. We can see the most frequent words are related to countries and politics such as “government”, “people”, “country”, “freedom”. The strong affirmative words also play important roles such as “must”, “can”, “will”. In the next steps, we will look more details into seperate speeches.

Word cloud for different presidents during different time period shows a strong relationship with events at that time.

![image](figs/wordc_mo.jpg)

The time when first term speech given by James Monroe was four years after the war in 1814, the wordcloud indicates that the speech had a significant emphasis on war-related terms, such as “invation”, “naval”, “militia”.

![image](figs/wordc_wbush.jpg)

The speech given by George W Bush in 2001 pronounced emphasis on terrorism, the wordcloud indicates that the speech had a significant emphasis on terrorism-related terms, such as “tyranny”, “fire”, “defended”.
