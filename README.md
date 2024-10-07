# NLIS
 natural-language-image-search
> 伟大的框架来自于模仿

### Introduction
Search photos on Unsplash using natural language descriptions. The search is powered by OpenAI's Clip model
adn the Unsplash Dataset.

### How It Works?

OpenAI's CLIP neural network is able to transform both images and text into the same latent space, where they can be compared using a similarity measure.

For this project, all photos from the full Unspash Dataset were downloaded and processed with CLIP.

The pre-computed feature vectors for all images can then be used to find the best match to a natural language search query

### How To Run?

```
pip install -r requirements.txt

