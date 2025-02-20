# Cifar-10

Files in This Repository

Download demo.py from code folder

demo.py:
Python script to: Load the CIFAR-10 dataset (test set only). Load the pre-trained ResNet-34 model. Evaluate the model using the test dataset. Generate and display the confusion matrix and classification report.

simple_model.pth: Pre-trained model file. Ensure this file is present in the same directory as the demo.py script or update the path(line 28) in the script accordingly. Download from this Link: https://drive.google.com/file/d/1Oj8vO-GnoIwwYuB4pmzE7mcBjClrodLZ/view?usp=drive_link
Requirements Python 3.7 or later Libraries: torch torchvision numpy matplotlib seaborn scikit-learn

You can install the required libraries using: pip install torch torchvision numpy matplotlib seaborn scikit-learn

How to Run the Script: Clone or download this repository. Ensure the simple_model file is available in the project directory.

Run the script: [copy the code] python demo.py

Output Confusion Matrix: A heatmap showing the confusion matrix for predictions made on the CIFAR-10 test dataset.

Classification Report: A detailed report showing precision, recall, F1-score, and support for each class.
