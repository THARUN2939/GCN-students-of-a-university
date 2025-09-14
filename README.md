GCN: Students of a University

This project implements a Graph Convolutional Network (GCN) to predict student dropout in a university setting.
The model uses student-related features and graph-based relationships to classify whether a student is likely to drop out or continue.

📂 Project Structure
GCN-students-of-a-university-main/
│── GCN_students_of_a_university.ipynb   # Jupyter Notebook with implementation

🚀 Features

Implements Graph Convolutional Networks (GCN) using PyTorch Geometric.
Applies GCN to student dropout prediction.
Demonstrates dataset loading, preprocessing, model training, and evaluation.
Visualizes dropout classification results.

🛠️ Requirements

Make sure you have the following installed:

python 3.8+
torch
torch-geometric
numpy
matplotlib
scikit-learn
networkx


To install dependencies:
pip install -r requirements.txt

📘 Usage

1.Clone the repository:
git clone https://github.com/<your-username>/GCN-students-of-a-university.git
cd GCN-students-of-a-university
2.Open the Jupyter Notebook:
jupyter notebook GCN_students_of_a_university.ipynb
3.Run all cells to train and evaluate the GCN model.

📊 Dataset

The notebook includes a student dataset representing:

Nodes → Students.

Edges → Relationships or interactions between students.

Labels → Dropout status (dropout / continue).

Note: You may replace the dataset with your own student data for custom predictions.

🧠 Model
Architecture: Graph Convolutional Network (GCN)
Loss Function: Cross-Entropy
Optimizer: Adam
Evaluation Metrics: Accuracy, Precision, Recall, F1-Score

📈 Results
The GCN model achieves effective performance in predicting student dropout.
Helps universities identify at-risk students early and take preventive actions.

🤝 Contributing
Contributions are welcome!
If you’d like to improve the model, add datasets, or enhance documentation, feel free to open a pull request.
