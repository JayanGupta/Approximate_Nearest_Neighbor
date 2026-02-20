# 🔍 Approximate Nearest Neighbor (ANN) Search Challenge

![Python](https://img.shields.io/badge/Python-3.8%2B-blue)
![Faiss](https://img.shields.io/badge/Faiss-Vector%20Search-green)
![NumPy](https://img.shields.io/badge/NumPy-Data%20Processing-013243)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-F37626)

> An efficient implementation of high-dimensional vector search using the **FAISS** (Facebook AI Similarity Search) library. This project demonstrates how to perform rapid similarity searches across large datasets using L2 distance indexing.

## 📊 About the Project
Traditional nearest neighbor searches become computationally expensive as data dimensions grow. This notebook implements **Approximate Nearest Neighbor (ANN)** techniques to provide a scalable solution for finding similar vectors in a 128-dimensional space.

## 🛠️ Key Features
* **Efficient Indexing**: Utilizes `faiss.IndexFlatL2` for robust similarity measurements.
* **High-Dimensional Data**: Demonstrates search capabilities using random 128-dimensional vector sets.
* **Rapid Retrieval**: Returns the $k$ nearest neighbors and their respective distances almost instantaneously.
* **Scalability**: Designed to handle datasets of 1,000+ vectors with ease, providing a foundation for larger-scale production environments.

## 🚀 Getting Started

### Prerequisites
You will need Python installed along with the FAISS and NumPy libraries:
```bash
pip install faiss-cpu numpy
```
### 🚀 Usage

1.  **Clone the Repository** Copy and run the following command to get the files locally:
    ```bash
    git clone [https://github.com/your-username/ann-search-challenge.git](https://github.com/your-username/ann-search-challenge.git)
    cd ann-search-challenge
    ```
2.  **Generate Synthetic High-Dimensional Data** Open `Approximate_Nearest_Neighbor.ipynb` and run the first few cells to create a dataset of 128-dimensional vectors using NumPy.
3.  **Build the FAISS Index** Execute the index creation cell. This step initializes the `IndexFlatL2` which prepares the system for high-speed Euclidean distance calculations.
4.  **Perform Your First Similarity Search** Run the final search cell to input a query vector and retrieve the $k$ nearest neighbors along with their distances almost instantaneously.
