🐱 LexNet Cat Diffusion — Residual Encoder-Decoder Diffusion Model
A from-scratch implementation of a diffusion-based image generator using a residual U-Net-style architecture. Trained to generate 64×64 cat images conditioned on sinusoidal timestep embeddings.


📁 Files
diffusion.ipynb — diffusion training loop & sampling

modeltest.ipynb — loading of lexnet_v1.h5 and subsequent usage

lexnet_v1.h5 — model weights

⚠️⚠️⚠️Data⚠️⚠️⚠️
Due to file size limits on GitHub, the training dataset is not included in this repository.

If you'd like to run the notebooks:

1. Download the dataset from https://www.kaggle.com/datasets/andrewmvd/animal-faces
2. Google drive docking in diffusion.ipynb is commented out. However, if you load the cat folder in animalfaces and read those images into img_tensors, the code will be operational

Dataset format: JPG images of size 64x64
