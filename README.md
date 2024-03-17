This project is a attempt to use potencial of Bert language model in order to create a functional chatbot which will answer philosophical questions.

First file (good_chatbot_aurelius.ipynb) is a combination of haystack framework and bert language model. The role of haystack framework is to build a local server for text to DensePassageRetriever and then to bert model after asking a question in the prompt. All models (DPR and Bert) are not fine tuned on data, so the accuracy results are below acceptable point. Furthermore the data are written in old English, so pretrianed Bert has some problems with "understanding" the context of question.

In the second file there is a code responsible for question generation on the basis of Marc Aurelius meditation book.
