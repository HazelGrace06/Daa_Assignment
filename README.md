# Daa_Assignment

Problem Definition: Create a data set of set of words. [Minimum 50 words]
Accept a word as input from keyboard. Find the best five possible words similar to input word
from the data set.

About this program: This is a project based on LCS Algorithm, and finds 5 words similar to input word.
The user has to i/p a word, and this algorithm finds 5 words similar to the i/p word, 
based on the concept of LCS(Longest Common Subsequence).


A Sample Output of the following code is:

Enter a word: exponent

['hello', 'good', 'hi', 'hey', 'nice', 'innumeration', 'apple', 'apply', 'exchange', 'mango', 'futile', 'exponential', 'letter', 'alphabet', 'sentence', 'meaning', 'lesson', 'review', 'help', 'learn', 'watch', 'observe', 'write', 'salvation', 'returning', 'summation', 'integration', 'encyclopedia', 'thesauraus', 'dinosour', 'search', 'find', 'calendar', 'xylophone', 'sublimal', 'respiration', 'technology', 'algorithms', 'prepositions', 'conjugation', 'experienced', 'conversational', 'controversial', 'adaptation', 'wikipedia', 'stationary', 'solitude', 'spacious', 'questionnaire', 'connosieur']

The LCS of each word is:

[2, 1, 0, 1, 2, 3, 2, 1, 4, 1, 1, 8, 2, 3, 4, 3, 3, 2, 2, 2, 1, 2, 1, 2, 3, 2, 3, 3, 1, 1, 1, 1, 2, 5, 0, 4, 2, 2, 4, 3, 5, 4, 3, 3, 2, 2, 2, 2, 4, 3]

The LCS of each word in Descending order is:

[8, 5, 5, 4, 4, 4, 4, 4, 4, 3, 3, 3, 3, 3, 3, 3, 3, 3, 3, 3, 2, 2, 2, 2, 2, 2, 2, 2, 2, 2, 2, 2, 2, 2, 2, 2, 2, 1, 1, 1, 1, 1, 1, 1, 1, 1, 1, 1, 0, 0]

The 5 words similar to the input word are:

exponential
xylophone
experienced
exchange
sentence
