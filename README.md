# Food AI: Cross-modal Representation Learning and Food Recipe Retrieval
Code for the CS 536: Machine Learning project at Rutgers University. Inspired by the CVPR paper [Learning Cross-Modal Embeddings for Cooking Recipes and Food Images](https://ieeexplore.ieee.org/document/8099810)

-----------------------------------------
### Work Done

* Performed retrieval of food recipes given food images and vice versa using crossmodal techniques.
* Improved the representation learning pipeline for both recipe text and recipe images and beat the baseline top-10 recall for image-to-recipe retrieval in the original paper by 20 percentage points
* Measured retrieval metrics employing three techniques: CCA and neural networks trained for retrieval on learnt representations using 1) MSE Loss, and 2) Triplet Loss. Attained median retrieval rank of 1 and top-10 recall of 82.49% for 1,000 random food images using Triplet Loss trained neural networks.

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
The file "Step1" contains code and retrieval results using the improved representation learning pipeline and CCA. The file "Step2a.ipynb"  contains code pertaining to the neural network training and evaluation when trained with MSE Loss. The file "Step2b.ipynb" contains similar code but for networks trained using Triplet Loss with random negative sampling.

The file "Viz.ipynb" contains code and visualizations seen in the report.

Made as a team with [@Neil-98](https://github.com/Neil-98), Aishwarya Harpale and Linqi Xiao
