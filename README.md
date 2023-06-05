# DesCap: Descriptive Captioning

Nice to open Descriptive Captioning module.

Descriptive Captioning means, you can get sentence not only the object focused but also adjective, adverb. The starting point of our technique is [BLIP](https://github.com/salesforce/BLIP)(Bootstrapping Language-Image Pre-training for Unified Vision-Language Understanding and Generation) The upgraded point from original BLIP is the preprocessing part especially preserving the pixel and spatial information

We also open the pretrained model trained with MS COCO train dataset. Two kinds of traine models, and each one means trained from the empty model, and another is trained from the [BLIP](https://github.com/salesforce/BLIP) pretrained. Although the necessary size of image in the model is 384, but users do not have to control or change the image size.

# Approach
![image](https://user-images.githubusercontent.com/68425947/209453711-c9416d4f-6ee8-45fd-b24f-dfec307d4722.png)


# Inference demo:
Run our interactive demo using Colab notebook (no GPU needed). The demo includes code for:

# Trained checkpoints:
|data|Trained Model|image size|
|----|-------------|----------|
|MS COCO 2017 (Trained)|Download|384|
|CC3M (Conceptual Captions)|Download|384|
|Visual Genome|Download|384|
|SBU Captions|Download|384|
