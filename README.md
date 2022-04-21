# Model Weights
This repo is for storing the model weights for "Self Supervised Learning for Semantic Segmentation of Archaeological Monuments in DTMs" and the corresponding repos [here](https://github.com/SSL-DTM).

It includes the following model weights:

- [semseg_DTM_random.pth](https://github.com/SSL-DTM/model_weights/releases/download/v0.0.0/semseg_DTM_random.pth): Semantic segmentation model trained with DTM inputs and random weight initialization. Each pixel is labeled as either background (0), bomb crater (1), charcoal kiln (2), burial mound (3) or mining hole (4).
- [semseg_RGB_imagenet.pth](https://github.com/SSL-DTM/model_weights/releases/download/v0.0.0/semseg_RGB_imagenet.pth): Semantic segmentation model trained with RGB hillshade inputs and initialized with pretrained imagenet weights.
- [semseg_DTM_RVGAN.pth](https://github.com/SSL-DTM/model_weights/releases/download/v0.0.0/semseg_DTM_RVGAN.pth): Semantic segmentation model trained with DTM inputs and initialized with pretrained RVGAN weights.
- [semseg_FOUR_random.pth](https://github.com/SSL-DTM/model_weights/releases/download/v0.0.0/semseg_FOUR_random.pth): Semantic segmentation model trained with four relief visualizations: Local Dominance (LD), Simple Local Relief Model (SLRM), Slope and Sky View Factor (SVF), and random weight initialization.
- [RVNet.pth](https://github.com/SSL-DTM/model_weights/releases/download/v0.0.0/RVNet.pth): Encoder-Decoder RVNet model which takes an input DTM and predicts the four corresponding relief visualizations: LD, SLRM, Slope and SVF
- [RVGAN.pth](https://github.com/SSL-DTM/model_weights/releases/download/v0.0.0/RVGAN.pth): The generator in RVGAN model which takes an input DTM and predicts the four corresponding relief visualizations: Slope, SLRM, LD and SVF.
