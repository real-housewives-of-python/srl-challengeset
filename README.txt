Semantic Role Labelling (SRL) is an NLP task used to identify and classify the predicate-argument roles within a text. Some models have been developed to execute this particular task - such as SRL BERT and SRL BiLSTM. We compared and evaluated these models by running them through a challenge dataset. This dataset comprises of 6 tests each containing 10 instances, totalling 60 instances. These tests are designed to challenge the models on specific SRL capabilities, such as being able to handle long-range dependencies, active/passive sentences and verb alternation. Out of the two models, BERT was the most successful by passing 3 out of the 6 tests. 

#####CODE######

This repository contains:

utils.ipynb - A Notebook containing the challenge dataset and test functions for the BiLSTM and BERT models

main.ipynb - A Notebook to print out the failure rate of each test, print out the failed samples and create a text file 
with the data instances and their predicted labels

data_results - a readable TSV file containing all the instances and results of the BiLSTM and BERT models

srl_results.txt - a readable text file with the BiLSTM predicted labels for each instance

bert_results.txt - a readable text file with the BERT predicted labels for each instance

Instructions:
- Upload and open main.ipynb on Google Colab
- Click on the Folder icon on the left side of the Notebook, this will open a sidebar. Click the Mount Drive icon to connect to Google Drive
- Upload utils.ipynb through the sidebar icon labelled 'Upload to session storage'
- Run all cells on main.ipynb to print out results and create text files containing the data instances and their predicted labels

Requirements:

Google Colab
Jupyter Notebook



