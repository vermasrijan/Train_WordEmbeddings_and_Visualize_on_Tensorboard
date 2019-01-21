# Train Word Embeddings and Visualize Tensorboard

![](https://s3-ap-south-1.amazonaws.com/av-blog-media/wp-content/uploads/2017/06/06062705/Word-Vectors.png)

## Usage
Word embeddings are a way of representing words in a vector form, in which similar, or neighbouring words have vectors close to each other (in terms of magnitude, and direction). <br/>

They are been extensively used for Language Models, dealing with Translation problem and is a hot field in the domain of NLP. <br/>

Given above Jupyter Notebook is divided into 2 parts: -<br/>
1. Train from scratch Hindi Text data using Word2Vec (300 dimension for each word), and then <br/>
2. Visualizing (3D) your hindi words using Tensorboard<br/>

Let us start with the first problem, training your own embedding layer from scratch:- <br/>
a) Some quick resources to understand how words are represented- [Andrew Ng NLP videos](https://www.youtube.com/watch?v=YgpI2aROLlo&list=PLZnyIsit9AM7HBPn6m06ddzw_N9zGk--2)<br/>
b) Look at the picture given below to see how words are represented- <br/>

![](https://cdn-images-1.medium.com/max/1600/1*mLrheV1nGz7XemDAVRcZ4A.png)

c) Follow [this](https://medium.com/data-science-group-iitr/word-embedding-2d05d270b285) blog to get a clear understanding for word embeddings. <br/>

![](https://cdn-images-1.medium.com/max/1600/1*YAGrtIpuRyA87iQHIwuPVA.jpeg)

## Dependencies
Numpy <br/>
Tensorflow<br/>
Logging<br/>
Gensim<br/>
Sklearn<br/>
Matplotlib<br/>
Pandas<br/>
Seaborn<br/>

## Dataset
Dataset(for hindi text) can be downloaded from various sources - <br/>
1. [Bilingual Sentence Pair](http://www.manythings.org/anki/)
2. [IIT-Bombay Dataset](http://www.cfilt.iitb.ac.in/iitb_parallel/iitb_corpus_download/)<br/>
3. [HindEnCorp 0.5](https://lindat.mff.cuni.cz/repository/xmlui/handle/11858/00-097C-0000-0023-625F-0)<br/>
4. [Indian parallel Corpora](https://github.com/joshua-decoder/indian-parallel-corpora)<br/>

## 2. Tensorboard Visualization 

![](https://cdn-images-1.medium.com/max/1600/1*_80rvfEBcGWDxNJE0rFJHA.gif)<br/>

# Acknowledgements
A big Thank you to the whole team of [Messy Fractals](https://messyfractals.wordpress.com/), especially [Dhanya P](https://www.linkedin.com/in/dhanyap/?originalSubdomain=in) and [Arvind Sivdas](https://www.linkedin.com/in/arvindsivdas/?originalSubdomain=in) for letting me work under them, for this project . <br/>

# References
The credits for this code go to the user [spro](https://github.com/spro/practical-pytorch/blob/master/seq2seq-translation/seq2seq-translation.ipynb). I have merely made some changes in it for dealing with Hindi text.
