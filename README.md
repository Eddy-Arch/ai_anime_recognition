# AI Anime Image Recognition
The following is an example of a custom
image recognition dataset + model example
that i based off of some TensorFlow Lite examples I found on the internet.

A *FULL* writeup and in depth explanation is available on my blog:

[Eddster's blog](https://eddster.xyz/p/ai-powered-anime-character-recognition/)

It takes in an image, and identifies the subject in the image.
![Misaka](https://raw.githubusercontent.com/Eddy-Arch/ai_anime_recognition/master/output.jpg)

## Specifics:

To be more specific, I trained the model on images from the
"Toaru no magical index" anime, and decided to have the model
try and identify two characters from the anime.

The characters being:
- Misaka mikoto
- Accelerator

I created a custom dataset based on images from the anime (no copyright
infringment intended)
And trained the efficient model on it.

It can now identify with around 70% accuracy pictures with
misaka/accelerator.

For example, if i show it a picture with accelerator it will be able to
identify him, and vise versa with misaka.

# Modify for your own use
Feel free to modify the code as you wish.

- Toarutrain.py = "Used to train the model on the dataset"
- identifytoaru.py = "Does the identification on the image"

# Usage
```python3 identifytoaru.py "https://yourimage.png```
