# Lung Infection Detection Model

## Overview

Welcome to the Lung Infection Detection Model repository. This project houses an advanced machine learning model tailored for identifying pulmonary ailments through medical imaging, specifically chest X-rays. The model is proficient in pinpointing prevalent lung issues such as pneumonia, tuberculosis, and other irregularities.

## Characteristics

- **Advanced Learning Framework:** The model leverages a state-of-the-art convolutional neural network (CNN) for precise image categorization.
- **Pre-established Model:** Benefit from a model that has undergone training on an extensive array of chest X-ray images, ensuring robust and reliable functionality.
- **Web Application:** Experience the convenience of a user-friendly web-based platform, allowing users to submit X-ray images and obtain prompt prognoses. (*Please note: The web application is currently under maintenance and not operational.*)

## Getting Started

1. **Clone the repository:**

   ```bash
   git clone https://github.com/s-tuti/LUNG-INFECTION-MODEL.git
   cd LUNG-INFECTION-MODEL
   ```

2. **Install Dependencies:**

   ```bash
   pip install -r requirements.txt
   ```

3. **Run the Web Application:**

   ```bash
   python app.py
   ```

## Model Training

If you wish to train the model on your dataset:

1. **Organize Your Dataset:**

   ```
   dataset/
   ├── normal/
   │   ├── normal_1.jpg
   │   ├── normal_2.jpg
   │   └── ...
   ├── pneumonia/
   │   ├── pneumonia_1.jpg
   │   ├── pneumonia_2.jpg
   │   └── ...
   └── other_diseases/
       ├── disease_1.jpg
       ├── disease_2.jpg
       └── ...
   ```

2. **Run the Training Script:**

   ```bash
   python train_model.py --dataset_path /path/to/your/dataset
   ```

   The trained model will be saved in the `models` directory.

## Contribution

Contributions are encouraged! If you encounter any issues or have suggestions for improving the model, feel free to open a pull request or create an issue.

## License

This project is licensed under the MIT License - see the (LICENSE.txt) file for details.
