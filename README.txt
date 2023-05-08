# srl-challengesetSemantic Role Labelling (SRL) is an NLP task used to identify and classify the predicate-argument roles within a text. Some models have been developed to execute this particular task - such as SRL BERT and SRL BiLSTM. We compared and evaluated these models by running them through a challenge dataset. This dataset comprises of 6 tests each containing 10 instances, totalling 60 instances. These tests are designed to challenge the models on specific SRL capabilities, such as being able to handle long-range dependencies, active/passive sentences and verb alternation. Out of the two models, BERT was the most successful by passing 3 out of the 6 tests. In addition  to executing these experiments, we also suggest a way to test the SRL models on text belonging to the music domain i.e. lyrics from opera librettos.

###########

This reporistory contains:

utils.ipynb - A Notebook containing the challenge dataset and test functions for the BiLSTM and BERT models

main.ipynb - A Notebook where the test functions of both models can be run and automatically create a text file with the data instances and their predicted labels

data_results - a readable TSV file containing all the instances and results of the BiLSTM and BERT models

Instructions:
- Upload and open main.ipynb on Google Colab
- Click on the Folder icon on the left side of the Notebook, click the Mount Drive icon to connect to Google Drive
- Upload utils.ipynb
- Run all cells on main.ipynb to print out results and create text files containing the data instances and their predicted labels

Requirements:

Google Colab
Jupyter Notebook



