# semantic-inpaiting
ConvNets autoencoder and discrimator using GANs for oceanograhic images inpainting task

The main code can be found in 'Inpainting using GANs' on Jupyter Notebook format. The 'keras_adversarial' folder and the 'modelutils.py' script are needed in order to correctly execute it. This file handles the image reconstruction of images that have been artificially manipulated with 'holes' of size 10x10 (single hole) and 6x6 (multiple holes) which represents the zones that were not successfully captured by the satellite due to external perturbations such as the clouds
