# Food AI: Cross-modal Representation Learning and Food Recipe Retrieval
Code for the CS 536: Machine Learning project at Rutgers University. Inspired by the CVPR paper [Learning Cross-Modal Embeddings for Cooking Recipes and Food Images](https://ieeexplore.ieee.org/document/8099810)

-----------------------------------------
### Work Done

* Built a system for retrieval of food recipes given images of corresponding food
* Beat the CCA baseline top-10 recall for recipe retrieval in the original im2recipe paper by 20 percentage points by using  ResNet and BERT feature extractors and introducing cross-modality through a shared embedding layer
* Implemented a second approach using triplet loss trained neural networks and attained median retrieval rank of 1 and  top-10 recall of 82.49% for 1,000 random food images

***

### Tech Stack

* Python 3
* PyTorch
* Hugging Face
* seaborn

***

### Report and Presentation 

You can access the report [here](https://github.com/kunjmehta/cross-modal-retrieval-food-ai/blob/main/cs536_s22_group_15_final_report.pdf) and presentation 
[here.](https://github.com/kunjmehta/cross-modal-retrieval-food-ai/blob/main/cs536_s22_group_15_final_presentation.pdf)

### Research Papers Referred

* [Learning Cross-Modal Embeddings for Cooking Recipes and Food Images](https://ieeexplore.ieee.org/document/8099810)
* [Recipe1M+: A Dataset for Learning Cross-Modal Embeddings for Cooking Recipes and Food Images](https://arxiv.org/abs/1810.06553)
* [Cross-Modal Retrieval and Synthesis (X-MRS): Closing the Modality Gap in Shared Representation Learning](https://arxiv.org/abs/2012.01345)
* [MCEN: Bridging Cross-Modal Gap between Cooking Recipes and Dish Images with Latent Variable Model](https://arxiv.org/abs/2004.01095)
* [Transformer Decoders with MultiModal Regularization for Cross-Modal Food Retrieval](https://arxiv.org/abs/2204.09730)


### Structure and Acknowledgements 

* "Step1.ipynb": Contains code and retrieval results using the improved representation learning pipeline and CCA. 
* "Step2a.ipynb": Contains code pertaining to the neural network training and evaluation when trained with MSE Loss. 
* "Step2b.ipynb": Contains similar code but for networks trained using Triplet Loss with random negative sampling.
* "Viz.ipynb": contains code and visualizations seen in the report.

Note: "Step-3.ipynb" is extra part of the project that aimed to enhance the explanibility of the retrieval system by leveraging attention mechanisms in ViT and BERT

Made as a team with [@Neil-98](https://github.com/Neil-98), Aishwarya Harpale and Linqi Xiao
