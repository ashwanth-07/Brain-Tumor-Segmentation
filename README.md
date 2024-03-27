# Brain Tumor Segmentation using U-Net Architectures

This project aims to compare the performance of various U-Net based semantic image segmentation architectures for brain tumor segmentation in medical imaging. The architectures include Attention ResUNet, UNet (for 2D), 3D ResUNet, 3D UNet, and 3D Attention ResUNet. The models are evaluated on the BraTS dataset, which comprises volumetric brain MRI scans with masked labels representing different tumor components.

## Project Overview

The project is organized into separate Jupyter notebooks for each architecture:

* **Attention_ResUNet.ipynb**: This notebook provides a detailed explanation and implementation of the Attention ResUNet architecture. It includes preprocessing, architecture details, training, and results.
* **UNet_2D.ipynb**: This notebook provides a detailed explanation and implementation of the 2D UNet architecture. It includes preprocessing, architecture details, training, and results.
* * **Ensemble-Attention_ResUNet.ipynb**: This notebook provides a detailed explanation and implementation of Mixture of experts with Attention ResUNet architecture. It includes preprocessing, architecture details, training, and results.
* **ResUNet_3D.ipynb**: This notebook provides a detailed explanation and implementation of the 3D ResUNet architecture. It includes preprocessing, architecture details, training, and results.
* **UNet_3D.ipynb**: This notebook provides a detailed explanation and implementation of the 3D UNet architecture. It includes preprocessing, architecture details, training, and results.
* **Attention_ResUNet_3D.ipynb**: This notebook provides a detailed explanation and implementation of the 3D Attention ResUNet architecture. It includes preprocessing, architecture details, training, and results.

The results demonstrate the effectiveness of 3D models in capturing spatial information compared to their 2D counterparts. This highlights the importance of considering the three-dimensional nature of medical images in semantic segmentation tasks. The Ensemble of Attention ResUnet was able to reach 
