# Kazakh Traditional Food Classification Using CNNs

This project presents a deep learning-based system for classifying images of traditional Kazakh dishes using Convolutional Neural Networks (CNNs). A custom dataset of 9,577 images across 22 categories was used to train multiple CNN architectures including DenseNet121, EfficientNet-B0, and others. The best model achieved 95% accuracy and was deployed in a Telegram bot for real-time inference.

## Repository Structure

- `notebooks/`: Jupyter notebooks for model training and Telegram bot.
- `model/`: Fine-tuned model in ONNX format.
- `dataset_info/`: Class list and sample images.
- `requirements.txt`: List of required Python packages.

## How to Run

1. Clone the repository
2. Install dependencies:
   ```
   pip install -r requirements.txt
   ```
3. Open `notebooks/1Kazakh National Food.ipynb` to see model training.
4. Open `notebooks/Telegram Bot.ipynb` to run the Telegram bot.

## Model Performance

| Model           | Accuracy |
|----------------|----------|
| DenseNet121 FT | 95%      |
| EfficientNet-B0| 94%      |
| ResNet50       | 91%      |
| MobileNetV2    | 92%      |
| VGG16          | 89%      |

## Contact

Developed by Iliyas Makhatbek.For more information, contact: `il_makhatbek@kbtu.kz`
