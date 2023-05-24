# ClipCap: Reproducing and Enhancing Image Captioning with CLIP

This project aims to reproduce and enhance the image captioning approach presented in the ["ClipCap: CLIP Prefix for Image Captioning"](https://arxiv.org/abs/2111.09734) paper. The method proposed in the ClipClap paper utilizes the CLIP model and a mapping network to simplify image captioning. Our work focuses on replicating the models proposed in the ClipCap paper and conducting additional experiments to improve their performance. Specifically, we replaced the GPT-2 model with GPT-Neo, a more efficient language model, and explored a more sophisticated transformer-based mapping network. Evaluation on the COCO validation set was performed using metrics such as BLEU, METEOR, CIDEr, and ROUGE-L scores, providing a comprehensive assessment of the model's efficiency and effectiveness. Through our efforts, we aim to refine and optimize the image captioning framework, offering improved results compared to the models proposed in the ClipCap paper.

We have taken the starter code from [rmokady/CLIP_prefix_caption](https://github.com/rmokady/CLIP_prefix_caption).

## Example image captions generated on COCO validation set images

![](examples_coco.jpg)

## Example image captions generated on random images from the internet

![](examples_internet.jpg)

For more details on this project, [click here](https://github.com/tswaraj/ClipClap/blob/main/Report.pdf).
