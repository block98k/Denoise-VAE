# Denoise-VAE
Deep deniose autoencoder

VAE.ipynb is a pure autoencoder model used keras with tensorflow backend, it is a test.
Denoise-VAE.ipynb use keras with tensorflow backend, it is a variational autoencoder model based on the VAE.ipynb.
Denoise-AE-tf.ipynb use tensorflow, it is a autoencoder model.

# Results
<img src="result.png">
The six pictures in first row are the original pictures.
The second are the noised pictures with normal noises, each picture has 300 pixels noises.
The third are the results of the Denoise-AE-tf.
The forth are the results of median filtering, which is relized by the scipy.signal.
# Usage
```
git clone https://github.com/block98k/Denoise-VAE.git
cd ./Denoise-VAE
jupyter notebook Denoise-AE-tf.ipynb
```

# Prerequisites
**tensorflow** 1.0 or above
**numpy**
**scipy**
**jupyter**

# Acknowledgement
This is a project I used to practice autoencoder.
