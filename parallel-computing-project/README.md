# ⚙️ Parallel Computing Project

This repository contains implementations and comparisons between **parallel** and **sequential** versions of classic sorting algorithms and a deep neural network. The goal is to evaluate performance gains using multithreading/multiprocessing and GPU acceleration.

---

## 🔢 Part 1: Parallel Sorting Algorithms

Implemented using Python `multiprocessing` and/or `concurrent.futures`. Each algorithm is benchmarked and compared to its sequential version:

- Bubble Sort
- Selection Sort
- Heap Sort
- Merge Sort

Metrics:
- Execution time (seconds)

Notebook: [`notebooks/parallel_sorting.ipynb`](./notebooks/parallel_sorting.ipynb)

---

## 🧠 Part 2: Parallel Deep Neural Network (MNIST)

Implemented a DNN to classify handwritten digits using the MNIST dataset. The task is solved using:

- **Sequential Training** (CPU or single-thread)
- **Parallel Training** (e.g., GPU / data loaders with num_workers)

Comparison Metrics:
- Accuracy
- Training Time
- Loss

Notebook: [`notebooks/parallel_dnn_final.ipynb`](./notebooks/parallel_dnn_final.ipynb)

---

## 🧾 Report Summary

- Task: Handwritten digit recognition using deep neural networks
- Framework: TensorFlow / PyTorch
- Why DNN: MNIST is a standard benchmark for DNN classification tasks
- Network Architecture: [add from your model]
- Results: [insert summarized accuracy/time chart from your notebook]

---

## 🛠️ How to Run

Install dependencies:
```bash
pip install -r requirements.txt
```

Launch notebooks:
```bash
jupyter notebook
```

---

## 📁 Files
- `notebooks/parallel_sorting.ipynb` – Sorting algorithms (sequential vs parallel)
- `notebooks/parallel_dnn_final.ipynb` – Final deep learning model with parallelization
- `README.md` – This file

---

## 📦 Dataset – MNIST Digits

This project uses the MNIST handwritten digits dataset from Kaggle:

🔗 [MNIST Dataset on Kaggle](https://www.kaggle.com/datasets/hojjatk/mnist-dataset/data)

### 📁 Expected Files:
After downloading, place the following files inside a `data/` folder at the project root:
- `mnist_train.csv`
- `mnist_test.csv`

Your folder structure should look like:
```
parallel-computing-project/
├── notebooks/
├── data/
│   ├── mnist_train.csv
│   └── mnist_test.csv
```

If the notebook doesn't find the files, double-check that they're correctly named and located inside the `data/` directory.
