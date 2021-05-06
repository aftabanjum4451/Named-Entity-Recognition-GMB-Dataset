# Named Entity Recognition
![](images/ner-image.png)

In Natural Language Processing (NLP) an Entity Recognition is one of the common problem. The entity is referred to as the part of the text that is interested in. In NLP, NER is a method of extracting the relevant information from a large corpus and classifying those entities into predefined categories such as location, organization, name and so on. Information about lables:

- geo--> Geographical Entity

- org--> Organization

- per--> Person

- gpe--> Geopolitical Entity

- tim--> Time indicator

- art--> Artifact

- eve--> Event

- nat--> Natural Phenomenon

## Dataset
(https://www.kaggle.com/abhinavwalia95/entity-annotated-corpus)

## Project Highlight

- Preprocess text data
- Build and train Flair Model: Bi-directional LSTM and CRF
  - Glove Embedding
  - Stacked Embeddings: Glove, forward and backward Flair embeddings
- Evaluate our model on the test set
- Run the model on your own sentences!

## How to Run The Code
All the code and comments are listed the jupyter notbook (NER model file.ipynb)


