# Paper List



### 2021

-  [2021.01] *[BW-EDA-EEND: streaming END-TO-END Neural Speaker Diarization for a Variable Number of Speakers](https://ieeexplore.ieee.org/document/9414371)* 
    -  BW-EDA-EEND (Block-Wise EDA + Transformer Encoder)
    -  Block-level recurrence in the hidden states to carry information from block to block, making the algorithm complexity linear in time.

- [2021.02] [*Online End-To-End Neural Diarization with Speaker-Tracing Buffer*](https://ieeexplore.ieee.org/document/9383523/)*
  - STB (speaker-tracing buffer) to store previous acoustic features and predictions
  
  - Solve permutation ambiguity by ordering current predictions with previous ones in the buffer
- [2021.03] [*Integrating End-to-End Neural and Clustering-Based Diarization: Getting the Best of Both Worlds*](https://ieeexplore.ieee.org/document/9414333) 
  - Jointly learning diarization results and speaker embeddings in a chunk  (assuming the number of speakers in a short window is not bigger than 2)
  - Using learnt speaker embeddings to cluster across the whole utterance, to solve the problems of long recodings
- [2021.04] [*Advances in Integration of End-to-End Neural and Clustering-Based Diarization for Real Conversational Speech*](https://www.isca-speech.org/archive/interspeech_2021/kinoshita21_interspeech.html)
  - Extension of the [2021.03] with more experiments



### 2020 

- [2020.01] [*Speaker Diarization with Region Proposal Network*](https://ieeexplore.ieee.org/document/9053760)
  
  - RPNSD
  -  Inspired by Faster R-CNN, jointly learn speech segment proposal and speaker embedding
  
- [2020.02] [*End-to-End Speaker Diarization for an Unknown Number of Speakers with Encoder-Decoder Based Attractors*](https://www.isca-speech.org/archive/interspeech_2020/horiguchi20_interspeech.html)
  
  - EDA (Encoder-Decoder based Attractor) + SA-EEND
  
  - Using neural network to predict the number of speakers
  
    


### 2019

- [2019.01] [*End-to-End Neural Speaker Diarization with Permutation-Free Objectives*](https://www.isca-speech.org/archive/interspeech_2019/fujita19_interspeech.html) 
  - BLSTM-EEND
  - Modelling speaker diarization as sequential multi-label classification tasks
- [2019.02] [*End-to-End Neural Speaker Diarization with Self-Attention*](https://ieeexplore.ieee.org/abstract/document/9003959)
  -  SA-EEND (Self-Attentive EEND)









