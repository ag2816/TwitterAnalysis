<h1>TwitterAnalysis</h1>

A blog post about this code can be found here: https://medium.com/dataexplorations/thoughts-on-visionzero-first-steps-with-the-twitter-api-and-word2vec-for-text-analysis-e766ed6b55ab

<h2>Overview</h2>
The goal of this analysis was to use the Twitter API to retrieve tweets about #VisionZero and run basic Text Analysis on the retrieved tweets.
I used
<ul>
  <li>Twython -- to search for recent tweets</li>
  <li>NTLK TweetTokenizer -- to split the tweets up into individual words, remove stop words, punctuation etc</li>
  <li>sklearn CountVectorizer -- to create a matrix of all the words used and whether or not they appear in each tweet</li>
  <li>wordcloud -- to create a wordcloud diagram of the most commonly used words</li>
  <li>Gensim Word2Vec -- to analyze the similarity of the words used in the tweets</li>
  <li>TextBlob -- for sentiment anslysis on the tweets</li>
 </ul>
