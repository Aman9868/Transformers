 By default, this pipeline selects a particular pretrained model that has been fine-tuned for sentiment analysis in English. The model is downloaded and cached when you create the classifier object. If you rerun the command, the cached model will be used instead and there is no need to download the model again.

There are three main steps involved when you pass some text to a pipeline:

The text is preprocessed into a format the model can understand.
The preprocessed inputs are passed to the model.
The predictions of the model are post-processed, so you can make sense of them.
Some of the currently available pipelines are:

feature-extraction (get the vector representation of a text)

fill-mask

ner (named entity recognition)

question-answering

![image](https://user-images.githubusercontent.com/60923869/148576480-83b287f1-bcf6-40af-9a01-d7f7f78b5e5d.png)


sentiment-analysis

summarization

text-generation

translation

zero-shot-classification
