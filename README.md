# ⚙️ Parallel Computing Project

This repository contains implementations and comparisons of both **parallel** and **sequential** versions of classic sorting algorithms and a deep neural network. The goal is to demonstrate performance improvements through multithreading, multiprocessing, and GPU acceleration.

---

## 🔢 Part 1: Parallel Sorting Algorithms

Implemented using Python's `multiprocessing` and `concurrent.futures`. Each algorithm is benchmarked against its sequential version:

- Bubble Sort  
- Selection Sort  
- Heap Sort  
- Merge Sort  

### 📊 Metric:
- Execution Time (in seconds)

📓 **Notebook**: [Parallel Sorting](parallel-computing-project/notebooks/parallel_sorting.ipynb).

---

## 🧠 Part 2: Deep Neural Network (MNIST)

Built a deep neural network to classify handwritten digits using the **MNIST dataset**, and compared:

- Sequential CPU training  
- Parallelized training (using batch loading / GPU)

### 📈 Metrics:
- Accuracy  
- Loss  
- Training Time

📓 **Notebook**: [Parallel Deep Learning (MNIST)](notebooks/parallel_dnn_final.ipynb)

---

## 🧩 Design Patterns Used

| Pattern        | Purpose |
|----------------|---------|
| **Observer**   | Email & SMS notification after ticket booking |
| **Strategy**   | Switching payment methods dynamically |
| **Decorator**  | Applying discounts to payment logic |
| **Singleton**  | Ensuring one central TicketManager instance |

---

## 🛠️ How to Run the Project

Install all required libraries:

```bash
pip install -r requirements.txt
