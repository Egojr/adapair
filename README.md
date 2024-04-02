# Multilevel Sentence Embeddings

This repository contains some of the implementation of the paper: [Multilevel Sentence Embeddings for Personality Prediction](https://www.jstage.jst.go.jp/article/pjsai/JSAI2023/0/JSAI2023_1U5IS2b02/_pdf/-char/ja)

By combining AdaCos loss and a Pairwise Cosine Loss we show how to train sentence embeddings following a hierarchical structure.
We provide sample scripts to reproduce the training, evaluation and visualization of the results shown for the MNLI dataset.

For training models refer to the train_triplet and train_adacos_pairwise scripts.  
For evaluation and visualization refer to the test_viz script.   
Sample outputs are shown for testing, to reproduce them yourself train and save the models first.   
