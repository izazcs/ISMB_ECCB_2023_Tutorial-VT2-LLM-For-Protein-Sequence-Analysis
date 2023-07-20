# ISMB/ECCB 2023 Virtual Tutorial - VT2
# Protein Sequence Analysis using Transformer-based Large Language Model 
To be held as part of  31st Conference on Intelligent Systems For Molecular Biology and 22nd European Conference on Computational Biology, July 23-27, Lyon, France. 
Tutorial Dates: July 17-18, 2023 at 14:00-18:00 hrs CEST  
### Overview
In the current decade, Artificial Intelligence (AI) / Machine Learning(ML) has tremendously facilitated scientific discoveries in biomedicine. Moreover, the recent advancements in the development of large language models (a type of deep learning model that can read, summarize, translate, and generate text as we humans do) have inspired many researchers to find applications in biological sequence analysis, partly because of the similarities in the data. Attention-based deep transformer models [1,2] pre-trained in a self-supervised fashion on large corpus have dramatically transformed research in natural language processing. The attention mechanism involved in transformer models captures the long-distance relationship among words in textual data [2]. Following a similar principle in the biological domain, researchers have trained transformer-based protein language models for biological sequence analysis. For example, ProtTrans [3] was trained on UniProtKB [4] sequences for protein sequence analysis. They showed that transformer-based self-supervised protein language models effectively capture the spatial relationship among residues which is critical for understanding the functional and structural aspects of proteins. 

In this 8-hour long (divided into two sessions: July 17-18, 2023 from 14:00 to 18:00 hrs CEST) online tutorial, we aim to provide experiential training on how to build basic ML pipelines using deep learning and pre-trained transformer protein language models for biological sequence analysis. We will start with a quick introduction to Python packages (Keras, Tensorflow/Pytorch, Scipy, scikit-bio, bio-transformers) that are heavily used for ML projects. In addition, we will cover the biological concepts behind protein sequence and function. Then, we will introduce classical natural language processing, and report its recent advancements. Finally, self-supervised deep learning-based large language models (such as Transformers) will be reviewed with a particular focus on protein sequence analysis. 
References 
1. Devlin, J., Chang, M. W., Lee, K., & Toutanova, K. (2018). Bert: Pre-training of deep bidirectional transformers for language understanding. arXiv preprint arXiv:1810.04805.
2. Vaswani, A., Shazeer, N., Parmar, N., Uszkoreit, J., Jones, L., Gomez, A. N., ... & Polosukhin, I. (2017). Attention is all you need. Advances in neural information processing systems, 30.
3. Elnaggar, A., Heinzinger, M., Dallago, C., Rehawi, G., Yu, W., Jones, L., Gibbs, T., Feher, T., Angerer, C., Steinegger, M. and Bhowmik, D., 2021. ProtTrans: Towards Cracking the Language of Lifes Code Through Self-Supervised Deep Learning and High-Performance Computing. IEEE Transactions on Pattern Analysis and Machine Intelligence. 
4. UniProt Consortium, 2007. The universal protein resource (UniProt). Nucleic acids research, 36(suppl_1), pp. D190-D195. 

### Learning Objectives 
At the end of the tutorial, the participants will have understanding and practical knowledge of: 

1. How to collect, preprocess and vectorize sequence data. 
2. How to build basic ML models for sequence analysis.
3. How to implement deep learning models such as Long-Short Term Memory and Recurrent Neural Networks (LSTM and RNN) in the context of biological sequence modelling.
4. Fundamentals of transformer-based large language models. 
5. How to apply a pre-trained transformer language model for biological sequence analysis 
6. How to formulate and address biomedical problems using transformer-based large language models. 
7. What tools, frameworks, datasets, and programming libraries are available to work with transformer-based large language models for sequence analysis.

### Target Audience
The target audiences are graduate students, researchers, scientists, and practitioners in both academia and industry who are interested in applications of deep learning, natural language processing, and transformer-based language models in biomedicine and biomedical knowledge discovery. The tutorial is aimed towards entry-level participants with basic knowledge of computer programming (preferably Python) and machine learning (Beginner or Intermediate). 

### Instructions
The participants are requested to follow the following steps to prepare their work environment. 

#### Minimum Requirements:

- A computer
- High speed internet. 
- A Google Drive account. Make sure you can access Google Drive and Google Colaboratory. 
- Minimum working knowledge of Python, particularly basic looping, lists, array, tensors. A refresher on Python will be provided as a part of the tutorial. However, we recommend a quick refresher  on PyTorch and Scikit-Learn  Python packages for ML model development. 

#### Setting up the environment:

Create a folder named ISMB_ECCB_2023  in your Google Drive.
Upload the data  Folder shared with you and place it under the folder ISMB_ECCB_2023. With data folder placed correctly, the notebooks should be executable without any error. 
Upload ISMB_ECCB_2023_notebooks  folder shared with you and place it under ISMB_ECCB_2023 .

### Acknowledgements
We would like to thank all the participants for attending this tutorial session and making it a successful event. 
Greatly indebted to ISMB/ECCB 2023 Tutorial committee for accepting this tutorial for presentation. Also very thankful to the technical team of ISCB for handling issues quickly during the tutorial session.
Would like to thank School of Applied Computational Sciences at Mehary Medical College, TN, USA for the logistics support to present this tutorial. 
Would like Dr. Sayane Shome and Dr. Nima Aghaeepour  from Standford School of Medicine, and , Dr. Farzana Rahman from Kingston University, UK for the tremendous effort in preparation of these materials.  
