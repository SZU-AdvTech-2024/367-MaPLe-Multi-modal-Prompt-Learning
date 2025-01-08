## Conclusions:

Based on the original code of MaPLe, the following improvements were made:

* Firstly, the input prompts of MaPLe were modified to an average form of multiple template prompts. (Corresponding to modifications in the file `multimodal-prompt-learning-main/trainers/maple.py`).
* Secondly, shared adapter parameters were added between the text encoder and the image encoder. (Corresponding to modifications in the file `multimodal-prompt-learning-main/clip/model.py`).
