## Feedback

You haven't given me write permissions on this repo, so here's a new file.

### Acquire
Looking the acquire data, it appears you pulled very few tweets, so that's going to be a 
problem. Also, you include "MBA" in your search terms, which is going to have millions of 
false positive hits, since that's the name of a degree. (Although, I'm not sure if the search
terms need to match on any or all.)

### Model

Smart idea to use the Kaggle amazon reviews for training. It might make sense to use labels
other than 0/1 so that it's clearer which one is positive and which is negative. 

83% accuracy doesn't seem bad to me. 

### Sentiment Analysis

Yeah, something bad happened! I'm not sure what it is, since you have a complicated multi-step 
process. In step 2, try classifying a tokenized sentence that you've written, like "I love my new Macbook Air". 
If that classifies correctly, then try it in step 3 to make sure your pickling is working as you expected it.
Then go find tweets that are clearly positive and negative and run them through your classifier. If it's still
working as expected then you probably solved the problem. It's also worth checking your tokenization procedure, since
you're getting punctuation in your "most informative features". 

You could theoretically call this complete, but I'd like to see a revision if you have time. 
