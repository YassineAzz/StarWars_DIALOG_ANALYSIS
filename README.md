Your tasks:
1. Find the characters with the most dialogues in each episode of The Original
Trilogy (Episodes IV, V, VI).
2. Plot the number of dialogues according to the character for each episode (i.e.
plot the above findings).
3. Add a new column “episode” to the three datasets (to distinguish between the three
episodes) and concatenate them into one dataset.
4. Discover the frequency distribution of words in The Original Trilogy.
5. Create a Frequency Distribution plot of the most repeated words in The Original
Trilogy.
6. Perform text-mining operations to prepare your dataset for further text analysis. (Use
the NLTK library)
a. Convert to lower case, word tokenization, removing stopwords, lexicon
normalization (lemmatization), etc.
b. Add the resulting array list to the dataset as a new column, “new_script”.
7. Repeat steps 4 & 5 but check the frequency distribution of the “new_script” this time.
8. Use Word Clouds to visually represent the most repeated words for Darth Vader and
Yoda. (Use the provided word cloud masks, make a single word cloud for each
character.)
9. Discover the most relevant words in The Original Trilogy script. The TF-IDF model contains
information on the more important and less important words (relevance).
10. Perform sentiment analysis on the movie scripts.


In Python, you will find that the most common way to perform sentiment analysis is employing a 
Naïve Bayes Classifier, where you build the model (but you are not necessarily required to build 
one here). You could make use of libraries to perform your sentiment analysis. Check out “Sentic” 
or the quite ironically named library, “VADER” (or any other library you prefer).
In the Star Wars universe, the Sith (like Darth Vader or Emperor Palpatine) are associated with 
negative feelings such as anger, fear, hate, etc. Conversely, the Jedi (like Luke Skywalker or Yoda) 
teach its followers to not give in to feelings of anger toward other lifeforms, which would help 
them resist fear and prevent them from falling to the Dark Side of the Force. Do you notice 
differences between the Dark Side characters and the Light Side characters according to your 
previous sentiment analysis? Explain your insights!
