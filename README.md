
# Multi-Class Image Classifier (CIFAR-10)
Purpose
The purpose of this project is to classify images of three distinct types of food using high tech deep learning and computer vision techniques. The project utilizes transfer learning with PyTorch to achieve an impressive very high accuracy of 96+% on the test set. The implementation is executed on Google Colab for efficient computation and easy accessibility.

## Project Structure

- **data/**: Contains the CIFAR-10 dataset (or instructions for downloading).
- **scripts/**: Python scripts for training, evaluation, and preprocessing.
- **notebooks/**: Jupyter notebooks for training and experimentation.
- 
## Requirements
 tensorflow==2.11.0
 
numpy==1.23.0

matplotlib==3.6.0

scikit-learn==1.1.2

Data Link: https://github.com/IsraelAzoulay/multi-class-image-classifier-computer-vision

  ## steps
To install dependencies:
```bash
pip install -r requirements.txt
Running the Code
Training the Model
Run the following script to train the model:
bash
Copy code
python scripts/train_model_cifar10.py
Evaluating the Model
After training, evaluate the model performance:
bash
Copy code
python scripts/evaluate_model.py
Results
The model achieves [insert accuracy] on the test set.






