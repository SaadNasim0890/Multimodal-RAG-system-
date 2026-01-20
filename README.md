# Multimodal-RAG-system-

## 📌 Project Overview
This repository contains the solution for Assignment 3, focusing on Generative AI techniques. The project is divided into two distinct tasks:
1.  **Prompt Engineering Analysis (Q1):** Evaluating different prompting strategies to elicit specific responses from Large Language Models (LLMs).
2.  **Model Fine-Tuning/Training (Q2):** Training and evaluating a Transformer-based model (likely utilizing Sentence-BERT or similar architectures given the config files) on a specific dataset.

## 📂 Repository Structure

```
22i-1190-A3/
├── Q1/                         # Task 1: Prompt Engineering
│   ├── Q1.ipynb                # Main notebook for running prompt experiments
│   ├── prompts.txt             # Text file defining strategies (Zero-Shot, Few-Shot, CoT)
│   ├── Prompt_Analysis_Results.csv # Comparative analysis of model outputs
│   └── [Screenshots & Images]  # Visualizations of embeddings and outputs
│
├── Q2/                         # Task 2: Model Fine-Tuning / Training
│   ├── Q2 (1).ipynb            # Main notebook for training the model
│   ├── task2_loss_curve.png    # Visualization of the training loss over time
│   └── [Screenshots]           # Training progress and results
│
└── genAI_3.pdf                 # Assignment Problem Statement
```

## 🚀 Key Features

### Task 1: Prompt Engineering (Q1)
Analysis of three distinct prompting strategies:
*   **Zero-Shot Learning:** Direct querying without examples.
*   **Few-Shot Learning:** Providing context/examples to guide the model.
*   **Chain-of-Thought (CoT):** Encouraging step-by-step reasoning.

**Results:**
The effectiveness of these strategies is documented in `Q1/Prompt_Analysis_Results.csv`, comparing answers related to "FYP Grading Criteria" and "Financial Data Analysis".

### Task 2: Model Training (Q2)
*   Implementation of a training pipeline using `transformers` and `sentence-transformers`.
*   Monitoring of training progress via widgets.
*   Visualization of loss convergence (`task2_loss_curve.png`) to ensure model stability.

## 🛠️ Prerequisites
To run the notebooks, ensure you have the following installed:

*   **Python 3.8+**
*   **Jupyter Notebook / Google Colab**
*   **Libraries:**
    *   `torch`
    *   `transformers`
    *   `sentence-transformers`
    *   `pandas`
    *   `matplotlib` (for visualizations)

## 📖 How to Run

1.  **Clone the repository** (if applicable) or download the project folder.
2.  **Navigate to the folder:**
    ```bash
    cd 22i-1190-A3
    ```
3.  **Run Task 1:**
    *   Open `Q1/Q1.ipynb` in Jupyter Notebook.
    *   Execute the cells to observe the prompt responses.
4.  **Run Task 2:**
    *   Open `Q2/Q2 (1).ipynb`.
    *   Run the training cells. Note that training may require a GPU (T4 is referenced in the notebook metadata).

## 📊 Results Summary
*   **Q1:** Few-shot and CoT strategies generally provided more structured and accurate answers for complex queries like financial analysis.
*   **Q2:** The model successfully trained, with the loss curve demonstrating convergence over the training batches.

---
*Created for the GenAI Course, Assignment 3.*
