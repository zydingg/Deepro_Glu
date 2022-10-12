# Deepro_Glu
Title: Deepro-Glu Combination of Convolutional Neural Network and Bi-LSTM Models Using ProtBert and Biological Features to Identify Lysine Glutarylation Sites

Lysine glutarylation (Kglu) is a newly discovered post-translational modification of proteins with important roles in mitochondrial functions, oxidative damage, etc. Established biological experimental methods to identify glutarylation sites are often time-consuming and costly. Therefore, there is an urgent need to develop computational models for efficient and accurate identification of glutarylation sites in large-scale data sets. In this study, we hypothesized that the ensemble deep learning network model can further enrich the handcrafted features and the peptide features encoded by natural language processing(NLP). The hypothesis was tested with an ensemble deep learning model which consists of two sub-models. The first sub-model used one-dimensional convolutional neural network(1D CNN) to capture the protein information from the ProtBert language model, and the second sub-model used  bidirectional long short-term memory network (Bi-LSTM) to learn the sequence information from the handcrafted features. 


    
### Deepro_Glu uses the following dependencies:
* python 3.6 
* pytorch 
* scikit-learn
* numpy


### Guiding principles:
* The data contains training dataset and testing dataset.
* File 







#### Note:
This code is for the article 'Deepro-Glu Combination of Convolutional Neural Network and Bi-LSTM Models Using ProtBert and Biological Features to Identify Lysine Glutarylation Sites' Please feel free to contact me if you need any further information and help, email : dingzhaoyuan@zzuli.edu.cn
