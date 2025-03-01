# TEXT_TO_IMAGE_FLOWERS

This repository contains code and models for **Text-to-Image Generation** based on various architectures. The project explores the use of different text encodings in GAN-based models and fine-tuning of the **Stable Diffusion** model.

## Results
The results show that Stable Diffusion achieved the best clarity with a score of 737.77 (Mean: 1.37, Std: 0.21), outperforming GAN and XLNet, which had an FID score of 1355.40 (Mean: 1.0, Std: 0.0). This superior performance in image quality and detail was also confirmed in human evaluations.

## File Structure

- **`DATASET_DETAILS.md`**  
  This file contains detailed information about the dataset used in the project, including the dataset link and the split details.

- **`GAN_GRU.ipynb`**  
  This Jupyter notebook contains the implementation of a **Generative Adversarial Network (GAN)** built from scratch using **GRU** (Gated Recurrent Units) for text encoding. It includes the code, training procedure, and output results.

- **`XLNET_GAN.ipynb`**  
  This Jupyter notebook contains the implementation of a GAN model using **XLNet** for text encoding. The notebook includes the code, model training, and output generation.

- **`Stable_Diffusion.ipynb`**  
  This notebook covers the fine-tuning of the **Stable Diffusion** model for text-to-image generation. It includes the setup, training, and output examples from the fine-tuned model.



