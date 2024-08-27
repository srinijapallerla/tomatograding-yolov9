# tomatograding-yolov9
# Tomato Grading with YOLOv9

This project aims to develop a deep learning model using YOLOv9 for detecting and grading tomatoes based on their ripeness and quality.

## Project Structure

- `data/`: Contains the training and validation datasets.
- `scripts/`: Python scripts for data preprocessing, training, and evaluation.
- `models/`: YOLOv9 configuration files and trained models.

## Getting Started

### Prerequisites

- Python 3.8+
- PyTorch
- OpenCV

### Installation

Clone the repository and install dependencies:

```bash
git clone https://github.com/your-username/tomato-grading-yolov9.git
cd tomato-grading-yolov9
pip install -r requirements.txt
Training the Model
```bash
python train.py --img 640 --batch 16 --epochs 50 --data data.yaml --cfg yolov9.yaml --weights yolov9.pt --name tomato_grading
Contributing
Feel free to submit issues or pull requests if you find any bugs or want to contribute to the project.
