# Topic modeling

Here we consider three ways of topic modeling.

1- Latent Dirichlet Allocation (LDA)\n
2- Non Negative Matrix Factorization (NMF)\n

While LDA and NMF have differing mathematical underpinning, both algorithms are able to return the documents that belong to a topic in a corpus and the words that belong to a topic. LDA is based on probabilistic graphical modeling while NMF relies on linear algebra. Both algorithms take as input a bag of words matrix (i.e., each document represented as a row, with each columns containing the count of words in the corpus). The aim of each algorithm is then to produce 2 smaller matrices; a document to topic matrix and a word to topic matrix that when multiplied together reproduce the bag of words matrix with the lowest error.

Both algorithms take a document collection as input and return the main words in a topic and the documents that belong to a topic?—?a feature that makes the output interpretable. NMF and LDA also support overlap between topics (i.e. documents can belong to multiple topics).

3- Google Colab: a customized collaborative Jupyter Notebook that can be hosted on Google Drive.
Scikit-Learn library including two topic modeling algorithms is installed by default on Google Colab.

To use Google Colab, Go to https://colab.?research.?google.com/github/aneesha/googlecolab_topicmodeling/blob/master/colab_topicmodeling.ipynb

The Colab Notebook will open. You will only be able to use the Colab Notebook after you save it to your Google Drive folder. Click on the File menu and select “Save a copy to Drive…”.

Next you will need to locate the Colab Notebook on your Drive filesystem. Click on the File menu and select “Locate on Drive”.

The folder will usually be called “Colab Notebooks”. Create a new Google Sheet and import your text data. The text data requires two columns namely id and text.

