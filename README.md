---

# ISIC 2024 Skin Cancer Detection Challenge

This repository provides a solution for the **ISIC 2024 Skin Cancer Segmentation Challenge**, focusing on detecting and segmenting skin cancer lesions using deep learning models. The implementation leverages pre-trained models from Hugging Face and PyTorch for efficient and accurate segmentation.

## Features
- **Pre-trained Models**: Utilizes pre-trained models for enhanced performance.
- **Comprehensive Framework**: Includes loading, preprocessing, and training pipelines.
- **Scalable Implementation**: Designed for Google Colab but adaptable to other environments.
- **Metrics and Analysis**: Incorporates detailed evaluation and visualization for segmentation results.

## Getting Started

### Prerequisites
Ensure the following dependencies are installed:
- Python 3.x
- PyTorch
- Transformers (Hugging Face)
- Pandas
- H5py
- Scikit-learn
- Numpy
- TQDM

### Installation
Install required dependencies using:
```bash
pip install torch torchvision torchaudio transformers pandas h5py scikit-learn numpy tqdm
```

### Dataset
The dataset should comply with the ISIC 2024 challenge requirements. Place it in the designated directory as specified in the notebook.

### Usage
1. Clone this repository.
2. Open the notebook in Google Colab or a local environment.
3. Run the cells sequentially:
   - Mount your Google Drive for dataset access.
   - Install dependencies.
   - Load and preprocess the dataset.
   - Train and evaluate the model.

## Contributions
Contributions to this project are welcome. Please submit a pull request with your enhancements or fixes.

## Acknowledgements
- **Hugging Face**: For providing pre-trained models.
- **PyTorch**: For offering a flexible deep learning framework.
- **ISIC Challenge**: For organizing the segmentation challenge and providing the dataset.

#The model needs to be trained further for better accuracy. Considering we use different level of augmentation, and different learning rate, optimizer , and other parameters.
