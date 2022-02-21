# Grand Challenge  



### The VoxCeleb Speaker Recognition Challenge 2020 (VoxSRC-20) 

[Link](https://www.robots.ox.ac.uk/~vgg/data/voxceleb/competition2020.html) |[Paper](https://arxiv.org/abs/2012.06867)

Track 4: Speaker Diarization 

- [1st] [*Microsoft Speaker Diarization System for the Voxceleb Speaker Recognition Challenge 2020*](https://ieeexplore.ieee.org/document/9413832)

  - Assuming the maximum number of talking speakers is two, continuous speech separation (CSS) separates the audio into two channels to remove the overlapped segments in a single channel.
  
  - Segmental Speaker Embedding Extraction for every single channel, speaker clustering for two channels together to give the diarization result from one system.
  - Ensembling multiple diarization systems with different front-end/back-end components.



### MULTI-CHANNEL MULTI-PARTY MEETING TRANSCRIPTION CHALLENGE (M2MeT 2022)

[Link](https://www.alibabacloud.com/zh/m2met-alimeeting) | [Paper](https://arxiv.org/abs/2110.07393?spm=a3c0i.25445127.6216726530.1.c9821cc9MPPUjG&file=2110.07393)

Track 1: Speaker Diarization 

- [1st] [*Cross-Channel Attention-Based Target Speaker Voice Activity Detection: Experimental Results for M2MeT Challenge*](https://arxiv.org/abs/2202.02687)

  - Training TS-VAD model for single-channel data separately.
  - Adopting cross-channel attention to fuse multi-channel information, and then using channel-level global average pooling to transfer multi-channel TS-VAD front-end features to single channel, followed by a classical single-channel TS-VAD back-end model.

  

   



