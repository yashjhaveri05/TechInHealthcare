Main Task: To correctly assign each enzyme to one of the 6 EC top-level classes. 

Dataset Obtained From https://github.com/snap-stanford/GraphRNN

Approach: Represent the enzymes as graphs. For each enzyme, their node attributes are used as their features. The graph network they are a part of is also represented as its feature. After this, the enzyme interaction data and the feature list of each enzyme is passed through a GCN model to get the embeddings for each of the enzymes. Following this, the embeddings are passed through a classifier for training a model. LightBGM and RandomForest Classifier are used for this task.

Open to Suggestions