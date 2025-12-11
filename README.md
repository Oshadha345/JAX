# JAX and Flax Learning Roadmap 🚀

![JAX](https://img.shields.io/badge/JAX-Library-blue) ![Flax](https://img.shields.io/badge/Flax-Framework-green) ![Contributions Welcome](https://img.shields.io/badge/Contributions-Welcome-brightgreen) ![License](https://img.shields.io/badge/License-MIT-yellow)

> **Learn JAX and Flax step-by-step, from basics to implementing cutting-edge research papers!**  
> 🧠 **Master the tools to build high-performance machine learning models.**

---

## 📂 Directory Structure

```plaintext
.
├── 01_JAX_Basics/                  # Phase 1: Getting familiar with JAX syntax and capabilities
├── 02_JAX_vs_NumPy/                # Phase 2: Comparing JAX with NumPy (Performance & Features)
├── 03_JAX_Mini_Projects/           # Phase 3: Building mini-projects with pure JAX
├── 04_Flax_Basics/                 # Phase 4: Introduction to Flax and its functionalities
├── 05_Flax_Mini_Projects/          # Phase 5: Building mini-projects with Flax
├── 06_Research_Paper_Implementations/ # Phase 6: Implementing research papers (Laptop-friendly)
└── README.md
```

---

## 🗺️ Roadmap

### 🥇 Phase 1: JAX Basics
**Goal:** Understand the core concepts of JAX.  
📚 **Topics:**
- JAX Arrays (`jax.numpy`) vs NumPy Arrays.
- Immutable arrays and pure functions.
- JIT compilation (`jax.jit`).
- Automatic differentiation (`jax.grad`, `jax.value_and_grad`).
- Vectorization (`jax.vmap`).
- Random number generation (`jax.random`).
- Pytrees.

---

### ⚡ Phase 2: JAX vs NumPy
**Goal:** Appreciate the power of JAX by comparing it directly with NumPy.  
📚 **Topics:**
- Benchmarking matrix multiplication and other operations.
- Demonstrating automatic differentiation (which NumPy lacks).
- Broadcasting and vectorization examples.

---

### 🛠️ Phase 3: JAX Mini-Projects
**Goal:** Apply JAX concepts to build simple machine learning models.  
📂 **Projects:**
- **Linear Regression:** Implement gradient descent manually using `jax.grad`.
- **MLP from Scratch:** Build a multi-layer perceptron, defining forward pass and loss function manually.

---

### 🌱 Phase 4: Flax Basics
**Goal:** Transition to Flax, a high-level neural network library built on top of JAX.  
📚 **Topics:**
- `flax.linen` Module API.
- Managing parameters and state (variables collections).
- `setup` vs `__call__` (compact) methods.
- Integration with `optax` for optimization.

---

### 🧩 Phase 5: Flax Mini-Projects
**Goal:** Build and train standard models using Flax.  
📂 **Projects:**
- **MNIST Classifier:** A classic "Hello World" for deep learning.
- **Autoencoder:** Learn to handle unsupervised learning tasks.

---

### 🧪 Phase 6: Research Paper Implementations
**Goal:** Implement cutting-edge research papers that are computationally efficient enough to train on a laptop.  
📂 **Projects:**
- **MLP-Mixer:** "MLP-Mixer: An all-MLP Architecture for Vision".
- **Vision Transformer (Tiny):** Implementing a scaled-down version of ViT.

---

## 🚀 Getting Started

1. **Environment Setup:**  
    Install the required libraries:
    ```bash
    pip install jax jaxlib flax optax
    # Note: For GPU support, follow the official JAX installation guide.
    ```

2. **Navigate:**  
    Start with the first notebook in `01_JAX_Basics`.

---

💡 **Pro Tip:** Contributions are welcome! Feel free to open issues or submit pull requests.  
📜 **License:** MIT  
👾 **Made with ❤️ by JAX enthusiasts.**

---
