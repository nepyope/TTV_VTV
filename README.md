# Text-to-Video Synthesis

This repository contains a deep learning-based text-to-video synthesis model that allows you to generate videos from text prompts and perform video-to-video transformations. The model utilizes a combination of OpenCLIP, Gaussian Diffusion, and VQGAN autoencoder to synthesize videos from text descriptions. Original code can be found [here](https://huggingface.co/damo-vilab/modelscope-damo-text-to-video-synthesis), all credits 


This repository adds VTV functionality to [modelscope-damo-text-to-video-synthesis](https://huggingface.co/damo-vilab/modelscope-damo-text-to-video-synthesis) and optimizes memory usage by decoding frames sequentially
allowing for larger image resolution and longer video duration

## VTV

1. A cow running a marathon
<video src="samples/cow.mp4" controls></video>
2. A cow running a marathon in hell
<video src="samples/hell_cow.mp4" controls></video>
3. A dog running a marathon
<video src="samples/dog.mp4" controls></video>
