# master-thesis-project-vioce-cloning
In this project, I provide the code for X-vector encoder, D-vector encoder and AdaIN-VC encoder. These encoder can extract 128-dimensional effective speaekr embeddings which is used in speaker adapation method. For each encoder, I provid the 100 samples of speaker embedding from 10 speakers. 

The pretrained models for each encoder are provided in this link (https://drive.google.com/drive/folders/17pWEqa8mvuEEOjC7_0YFjrDWv9-ohQh-?usp=sharing)

The pretrained models of FastSpeech2 for mandarin fine tuning with different speaker embeddings are provided in this link (https://drive.google.com/drive/folders/13Ede8WM_jehXOOqk5vNugW65nNjjVOpy?usp=sharing)

The pretrained models of Tacotron 2 for mandarin is provided in this link (https://drive.google.com/drive/folders/1fw5pSK4FyvTpXhiBTD8AokMDRAdgp8Ls?usp=sharing)

I submit the code for visualization the speaker embeddings. This code first reduces the dimension of the speaker embeddings and uses TSNE tool to visualize them.

I submit the code for getting mel-spectrogram from audios.

I submit the samples of synthesized speech using three methods.
