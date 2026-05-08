# Emotion_Detection_CNN
Features
Face Detection: Uses Haar Cascade (haarcascade_frontalface_default.xml) for preprocessing and isolating facial regions.

CNN Model: Custom architecture designed for robust emotion classification.

Dataset Integration: Trained on a large, labeled dataset of facial expressions.

Applications: Useful in human-computer interaction, mental health monitoring, surveillance, and entertainment systems.

📂 Dataset
Source: Kaggle - Face Expression Recognition Dataset (kaggle.com in Bing)

Contains thousands of labeled facial images across multiple emotion categories.

⚙️ Installation
Clone the repository and install dependencies:
bash
git clone https://github.com/yourusername/Emotion_Detection_CNN.git
cd Emotion_Detection_CNN
pip install -r requirements.txt


🚀 Usage
Preprocess Data

Haar Cascade is used to detect faces in input images.

Train the Model

bash
python train.py
Test/Inference

bash
python predict.py --image sample.jpg
📊 Results
Achieves high accuracy on the validation set.

Confusion matrix and accuracy plots are available in the results/ folder.

🔮 Future Work
Improve accuracy with deeper CNN architectures (ResNet, VGG).

Real-time emotion detection via webcam integration.

Deployment as a web app or mobile application.

🤝 Contributing
Contributions are welcome! Please fork the repository and submit a pull request with improvements or bug fixes.

📜 License
This project is licensed under the MIT License.


Data Set Link - https://www.kaggle.com/jonathanoheix/face-expression-recognition-dataset
