\## Dataset Imbalance Analysis



The APTOS 2019 dataset exhibits a significant class imbalance problem. 

As illustrated in Figure 1, the majority class (No DR) contains a disproportionately large number of samples compared to minority classes such as Severe and Proliferative DR.



!\[Class Distribution](../../results/figures/fig\_1\_class\_distribution\_bar\_before\_balancing.png)



This imbalance can bias the model towards majority class predictions, leading to poor generalization on clinically critical minority classes.



The imbalance ratio between the largest and smallest classes is approximately 9.35:1, indicating a severe skew in data distribution.



To address this issue, appropriate balancing strategies such as data augmentation, weighted loss functions, or resampling techniques will be considered.

