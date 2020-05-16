# NLP: Disney/Pixar-Movies-Happiness-Comparison

This is a NLP approach for a question which has been bugging me a lot. Which disney/pixar movies make you smile and which ones make you cry?
This is the basic topic we are going to approach

We are going to use sentiment analysis for classification of these movies based on their synopsis. Also we are going to use Topic Modelling for analysis of which topics are generakky addressed in the chosen movies.

For Sentiment Analysis we are going to use TextBlob.
For Topic Modelling we are going to use GenSim.
Plot Summaries(synopses) for the following movies were taken from IMBD. All the data files are in .txt format present in the synopses folder.

Movies used:
1. Aladdin
2. Cars
3. Finding Nemo
4. Frozen
5. Tangled
6. The Little Mermaid
7. Toy Story 3
8. Toy Story
9. Up
10. Zooptopia


## After analysis we found:
### Movie-Polarity
1. Frozen-0.094541
2. Aladdin-0.083836
3. Cars-0.077923
4. Toy Story-0.06611
5. The Little Mermaid	0.064780
6. Toy Story 3-0.049407
7. Tangled-0.041784
8. Finding Nemo-0.037587
9. Up-0.030949
10. Zootopia-0.022158

## What we gather from the data:
Apart from the inconsistencies of Frozen and Zootopia(each seemingly in opposite side of the spectrum they deserve to be in), the rest are pretty accurate. Aladdin, Cars and Toy Story are happy and cheerful movies. Up, Finding Nemo and Toy Story 3 are quite the emotional flicks. Thus we have pretty accurately categorized movies based on their plot synopsis.

So, Disney/Pixar really know how to play with the heart strings of its audience. 
