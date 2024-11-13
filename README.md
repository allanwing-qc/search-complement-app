# Quantum Search Complement App

This repository provides an interactive Streamlit app to explore a modified version of the SKW algorithm, which performs the search complement of a marked node within a \(2^n\)-dimensional complete graph with self-loops. The algorithm's goal is to decrease the probability of a selected quantum state, achieving a search complement effect, i.e. the opposite effect of Grover's algorithm.

### Key References
- **SKW Algorithm**: For the original algorithm, see [arXiv:quant-ph/0210064](https://arxiv.org/abs/quant-ph/0210064).
- **Modified Approach**: The modified version used in this app [arXiv:2405.16322v1](https://arxiv.org/abs/2405.16322v1).

We use **Qiskit 0.45.3** for quantum operations in this project.

---

### Installation and Usage

To run the app in your terminal:

1. Install required Python packages from `requirements.txt`:
    ```bash
    pip install -r requirements.txt
    ```

2. Launch the Streamlit app:
    ```bash
    streamlit run search_complement_st.py
    ```

