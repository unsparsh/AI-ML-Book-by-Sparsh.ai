
# Day 15: Gated Recurrent Units (GRUs)

## Learning Objectives
1. Understand the structure and purpose of GRUs in neural networks.
2. Learn how GRUs differ from LSTMs and why they are used for similar tasks.

---

## Content

### 1. What are Gated Recurrent Units?
- **Concept**: GRUs are a type of RNN similar to LSTMs but with a simpler structure.
- **Advantages**: GRUs have fewer parameters than LSTMs, making them faster to train and sometimes more efficient.

### 2. How GRUs Work
- **Structure**: GRUs use two gates (update and reset) to control information flow, which simplifies the architecture compared to LSTMs.
- **Applications**: GRUs are often used in similar tasks to LSTMs, such as sequence modeling, but are preferred for faster training times.

### 3. Applications of GRUs
- **Examples**: Speech recognition, language modeling, and time-series prediction.

---

### Exercise
1. **Implement a GRU Model**: Build a GRU model for a sequence prediction task and compare its performance with an LSTM model.
2. **Experiment**: Try changing the number of units in the GRU and observe how it impacts performance.
