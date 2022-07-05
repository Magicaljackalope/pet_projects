# classification of goods in the store
### This is this is a test task in KazanExpress
For multi-class classification was used naive bayes algorithm. Because the algorithm performs well in classification, it is easy to understand and fast to learn. The latter was important due to lack of time.

Conclusion: I made a classification based on the naive Bayesian classifier, since this classifier works best with text. I added the text data from the columns (not counting the characteristics), and then worked with this text. Removed all special characters and numbers, removed all service parts of speech and words shorter than two letters (mostly remained after the removal of numbers. Added data in which there are still service parts of speech and words shorter than two letters, so that they are taken into account, but to a lesser extent, since the remaining words occur several times.On the training sample (0.2), 78.3% received the result without taking into account the hierarchy.
The result can be improved: 
1. using other models and an ensemble of them 
2. further improving the data 
   * adding a library that corrects spelling errors 
   * adding lemmatization of words 
   * excluding words that do not carry a semantic load (discount, free, new ...) 
4. taking into account the remaining columns and working on improving their quality 
5. taking into account product photos 
6. taking into account the price of the goods 
7.  taking into account the category tree when deciding
