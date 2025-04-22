# Deepfake Detection Project

This project aims to detect deepfakes using the Xception model. It leverages deep learning techniques to distinguish between real and fake videos.

## Dataset

The project uses the DeepFake Detection Challenge (DFDC) dataset, specifically the 'dfdc-faces-of-the-train-sample' dataset from Kaggle.

## Model

The project utilizes the Xception model pre-trained on ImageNet as the base model. Custom layers are added for binary classification (real/fake).

## Training

The model is trained using data augmentation and includes callbacks for learning rate scheduling and early stopping.

## Evaluation

The model is evaluated on a validation set using metrics such as accuracy, precision, recall, and F1-score.

## Inference

The trained model can be used to predict on new images or videos by extracting faces and feeding them to the model.

## Usage

1. Clone the repository.
2. Install the required dependencies.
3. Download the dataset.
4. Train the model.
5. Evaluate the model.
6. Use the model for inference.

## Contributing

Contributions are welcome! Please feel free to submit pull requests.

## License

This project is licensed under the MIT License.
