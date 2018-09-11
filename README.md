# Research2Vec

Upcoming project for representing research papers as vectors / latent representations. More coming soon 

I've created a subreddit to interact with users for this project

https://www.reddit.com/r/Research2Vec/

Here are anticipated FAQ and answers

What are other research papers reccomenders and how do they compare to yours?

As far as I know:

For machine learning / cs there is http://www.arxiv-sanity.com/ which uses tf-idf

Other major ones are https://www.semanticscholar.org/ , https://scholar.google.com/ , and https://www.mendeley.com . 

I'm not sure exactly how they work but I'm guessing it's a combination of collaborative filtering, content based filtering, and graph-based reccomendations. I have not seen any indication that they are using embedding representations to represent whole papers. 

Why vector representation?

My last project in representing books as vectors worked out pretty well 
https://github.com/Santosh-Gupta/Lit2Vec

One of the advantages of having items representated as a vector is that not only can you get reccomendations for a particular items, but you can see how the reccomendations are related to each other. 

(book image from lit2vec here)

You can also just check out a particular field and see the intersections of two fields. 

(book image from lit2vec here)

Also, embeddings can have arithmetic properties
https://www.youtube.com/watch?time_continue=25&v=IbI2RJLxGZg

Although these properties were not robust in Lit2Vec although not entirely absent

(book image from lit2vec here)

But I'm hoping to improve upon lit2vec's arithmetic properties in the future with more data. 

