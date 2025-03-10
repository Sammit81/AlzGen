# AlzGen - Enhancing Alzheimer’s Disease Detection through GANs and Advanced Deep Learning Architectures


## Overview
Alzheimer’s disease is a progressive neurodegenerative disorder that affects millions worldwide, with early diagnosis being crucial for effective intervention. This project leverages Generative Adversarial Networks (GANs) to enhance the detection and analysis of Alzheimer’s through advanced deep learning techniques. By generating high-quality synthetic medical images and improving classification accuracy, this research aims to address challenges in medical data scarcity while enhancing diagnostic capabilities. AlzGen combines the power of artificial intelligence and medical imaging to contribute toward early and more precise Alzheimer’s detection.

## Dataset
[OASIS Alzheimer's Detection](https://www.kaggle.com/datasets/ninadaithal/imagesoasis)

## Features
- Synthetic Data Generation – Uses GANs to generate realistic brain MRI scans.
- Alzheimer’s Classification – Deep learning models to detect and classify Alzheimer’s stages.
- Data Augmentation – GAN-based data augmentation to improve model generalization.
- Explainability & Insights – SHAP and Grad-CAM visualizations to enhance model interpretability.

## Installation Setup
1. Clone the repository
```sh
git clone https://github.com/yourusername/NeuroGen.git
cd NeuroGen
```
2. Create a virtual environment
```sh
python -m venv alzgen_env
source alzgen_env/bin/activate   # On Windows: neurogen_env\Scripts\activate
```
3. Install dependencies
```sh
pip install -r requirements.txt
```
## Usage

### Generating Neural Images using GANs
1. Open `GAN.ipynb`
2. Run the notebook
3. Artificial Neural Images will be generated using this notebook
4. Save those images (I have used GDrive to save the generated images and to load the dataset)

### Model building and Alzheimer’s disease prediction
1. Open `Alzheimer's.ipynb`
2. Run `ResNet50`
3. Run `Inception ResNet-V2`
4. You will get SHAP values for Alzheimer's disease detection.

## Results and Evaluation
### Model Performance Metrics
- Accuracy, Precision, Recall, F1-score, and AUC-ROC scores for Alzheimer’s classification.
- Confusion Matrix to analyze misclassification rates.
### GAN-Generated Image Quality
- Visualization of real vs. GAN-generated MRI scans.
### Explainability & SHAP Analysis
- SHAP Visualization to highlight the most influential regions in brain scans.
- SHAP (SHapley Additive Explanations) Values to interpret feature importance in Alzheimer’s classification.
- SHAP Summary & Dependence Plots to analyze model decision-making.
### Comparative Study
- Performance comparison between advanced CNN models.
- Impact of data augmentation using GANs on Alzheimer’s detection accuracy.

## Future Work
- Expand dataset for better model generalization.
- Optimize GAN architecture for improved image quality.
- Deploy as a web-based tool for real-world usage.

## License
This project is licensed under the MIT License.

## Contributions
I am not accepting contributions for this project as it is my university thesis.