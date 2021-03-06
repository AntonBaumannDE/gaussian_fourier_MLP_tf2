# Fourier Features Let Networks Learn High Frequency Functions in Low Dimensional Domains

Replicated some JAX snippets in TF2 to see how passing the input through Fourier feature mappings performs on different images and parameters. 
This method enabled the NERF implementation by Mildenhall et al. to render photorealistic scenes. 
However, it can also be applied to other problems such as 2D-image regression. 

Based on:
Matthew Tancik, Pratul P. Srinivasan, Ben Mildenhall, Sara Fridovich-Keil, Nithin Raghavan, Utkarsh Singhal, Ravi Ramamoorthi, Jonathan T. Barron, & Ren Ng (2020). Fourier Features Let Networks Learn High Frequency Functions in Low Dimensional Domains. NeurIPS 2020 (spotlight).

Project-page with links to the original code and the paper: 
https://bmild.github.io/fourfeat/

## Image regression results:

<img src="images/ground_truth.png" width="30%" height="30%"><img src="images/Inference_without_Fourier_features.png" width="30%" height="30%"><img src="images/Fourier_features_result.png" width="30%" height="30%">

Image-source: https://cdn.pixabay.com/photo/2016/02/12/23/49/monkey-1197100_960_720.jpg

## Application overview from the cited paper:

![alt text](images/tancik_et_al_abstract.png)
