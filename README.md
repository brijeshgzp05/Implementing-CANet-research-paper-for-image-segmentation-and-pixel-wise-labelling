# Implementing-CANet-research-paper-for-image-segmentation-and-pixel-wise-labelling
## This repository is based on paper --> Class-Agnostic Segmentation Networks with Iterative Refinement and Attentive Few-Shot Learning by Chi Zhang, Guosheng Lin, Fayao Liu, Rui Yao, Chunhua Shen. 
   Link --> https://arxiv.org/abs/1903.02351
  
  #### Steps include:
  1. Creating a mask from information embedded in corresponding json file.
  2. Created custom data loader.
  3. Custom layers were implemented as per described in paper except channel shuffling stuff.
  4. Loss function used : Dice loss
  5. Metrics used was: IOU score
  6. The model was trained with Adam optimizer for 20 epochs only due to computation limits and got a iou score of 0.23.
