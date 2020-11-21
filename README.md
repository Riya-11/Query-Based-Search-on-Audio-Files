## Query Based Search on Audio Files

### Motivation and Idea
Searching for a phrase or text in a corpus of audio files manually is cumbersome.

#### Idea 
A method that allows a user to fetch a list of audio files sorted by relevance given a search query. We plan to do this via 3 stages
- Speech to text conversion
- Keyword extraction and preprocessing for information retrieval (store the text as documents)
- Retrieve relevant files given a query keyword
