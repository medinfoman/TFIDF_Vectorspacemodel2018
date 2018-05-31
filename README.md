# TFIDF_Vectorspacemodel2018
##(https://github.com/medinfoman/TFIDF_Vectorspacemodel2018)
## This is an project to test IR model for the term project.
### Data: Pride and prejudice (chapter 2,3,4,5,6,7,9,11,13,15,17)
### Questions: 10 for dev, 11 for test

### This project results out the ranks of the chapters as answers for the user's keywords.
### TF_IDF & Vectorspace model was used for to decide the methods.

### This project composed of 5 ipynb files.
### (some program contains Korean for comments)
### Run them with following steps:
* preprocessing_1getChapters.ipynb: to find chapters of each line of the book
* preprocessing_2.ipynb: tokenization, remove stop words. 
* TF-IDF_1docs.ipynb: can calculate TF*IDF of the book
* Vector Space Model_devsetQ.ipynb : can answers for the questions of dev set based of TF*IDF & Cos similarity
* Vector Space Model_testsetQ.ipynb : can answers for the questions of test set based of TF*IDF & Cos similarity

### To make the program work ordinarily, needs some python packages

### first activate your conda virtual environment like this
### source activate <env_name>

### Then install packages: 
### To control dataframe
conda install -c anaconda pandas

### To control excel files
conda install openpyxl

### To use stopwords
conda install -c anaconda nltk




