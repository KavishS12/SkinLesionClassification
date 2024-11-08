# Skin Lesion Classification Using Computer Vision and Machine Learning

This project applies machine learning to classify skin lesions, utilizing color, texture, and shape features from dermoscopic images in the HAM10000 dataset. The primary goal is to support early detection and diagnosis of skin cancer through automated classification.

## Features and Methodology
- **Dataset**: HAM10000 – a collection of over 10,000 images across seven skin lesion categories.For detailed information on the dataset ,refer to [data_description.pdf](./data_description.pdf).

- **Feature Extraction**:
  - **Color**: Color histograms capture pixel intensity distributions.
  - **Texture**: Haralick texture features quantify surface patterns.
  - **Shape**: Hu moments capture invariant shape characteristics.
- **Models**: Decision Trees and Random Forests were employed for classification, with Random Forest achieving the highest accuracy (95.01%).
#
For more details, check out the [project report](./Skin%20Lesion%20Classification%20report.pdf).

