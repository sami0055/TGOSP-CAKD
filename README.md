🧠 Teacher-Guided One-Shot Pruning via Context-Aware Knowledge Distillation

This repository contains the official implementation of the research paper
“Teacher-Guided One-Shot Pruning via Context-Aware Knowledge Distillation.”

Our work introduces a teacher-guided one-shot pruning framework that integrates Knowledge Distillation (KD) directly into the pruning process, enabling high sparsity with minimal accuracy loss. By leveraging Context-Aware KL Divergence (CA-KLD) and gradient-based importance scoring, the method identifies and retains parameters critical for both task performance and knowledge transfer.

🚀 Key Features

Teacher-Guided Gradient Importance: Uses gradients from both task and KD losses to rank parameters by importance.

One-Shot Global Pruning: Achieves extreme compression without iterative prune–retrain cycles.

CA-KLD with Logit Normalization: Stabilizes gradients for robust distillation and pruning.

Sparsity-Aware Retraining: Maintains a fixed pruning mask to ensure consistent sparsity.
