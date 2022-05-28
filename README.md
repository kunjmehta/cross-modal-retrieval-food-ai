# Food AI: Cross-modal Representation Learning and Retrieval
Code for the CS 536: Machine Learning project at Rutgers University. Inspired by the CVPR paper [Learning Cross-Modal Embeddings with Adversarial Networks 
for Cooking Recipes and Food Images](https://arxiv.org/abs/1905.01273)

-----------------------------------------
### Work Done

* Beat the baseline retrieval performance in the original im2recipe paper for the Recipe1M cross-modal food recipe retrieval task by 80% by improving on the feature extraction pipeline
* Improved retrieval performance by learning shared multi-modal representations using CCA and non-linear neural networks trained using Triplet Loss
* Enhanced the explainability of the system by incorporating Vision Transformers and cross-modal attention when learning shared representations

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

* [Learning Cross-Modal Embeddings with Adversarial Networks for Cooking Recipes and Food Images](https://arxiv.org/abs/1905.01273)
* [Recipe1M+: A Dataset for Learning Cross-Modal Embeddings for Cooking Recipes and Food Images](https://arxiv.org/abs/1810.06553)
* [Cross-Modal Retrieval and Synthesis (X-MRS): Closing the Modality Gap in Shared Representation Learning](https://arxiv.org/abs/2012.01345)
* [MCEN: Bridging Cross-Modal Gap between Cooking Recipes and Dish Images with Latent Variable Model](https://arxiv.org/abs/2004.01095)
* [Transformer Decoders with MultiModal Regularization for Cross-Modal Food Retrieval](https://arxiv.org/abs/2204.09730)


### Structure and Acknowledgements 
The file "Step1 + Step2.ipynb" contains code retrieval results using CCA and non-linear neural networks. The file "Step3.ipynb"  contains code for enhancing the explainability
of the model using Vision Transformers and cross-modal learning. The file "Viz.ipynb" contains code and visualizations seen in the report.

Made as a team with [@Neil-98](https://github.com/Neil-98), Aishwarya Harpale and Linqi Xiao
