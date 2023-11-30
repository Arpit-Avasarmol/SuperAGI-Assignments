# SuperAGI-Assignments
Name: Arpit Sanjay Avasarmol
Branch: MTech, Data Science
Enrollment ID: 22566003
Gsuite Id: arpit_savasarmol@mfs.iitr.ac.in

### Task 1 | GPT-2 Model & Checkpoints (20 Points)

---

Start by implementing the `GPT2-small` model (with 125 million parameters) using Python and PyTorch. Make sure you touch upon the key aspects of the model like multi-head self-attention mechanism, feed-forward networks and positional encoding.

Key points:

- Follow the original GPT-2 design of using both token and positional embeddings.
- Implement the transformer layers with multi-head self-attention and point-wise feed-forward network.
- You're required to abstain from using pre-built transformer libraries.

Refer to the GPT-2 paper's architecture descriptions in Sections 1 and 2 for further help. ([GPT-2 paper](https://cdn.openai.com/better-language-models/language_models_are_unsupervised_multitask_learners.pdf)). Additionally, a great resource could be Andrej Karpathy’s [nanogpt](https://github.com/karpathy/nanoGPT) repository and the [makemore](https://youtube.com/playlist?list=PLAqhIrjkxbuWI23v9cThsA9GvCAUhRvKZ&feature=shared) series.

To validate your implementation, load the original GPT-2 125M model checkpoints and run a sample prediction.

**Deliverable:** Complete Python code featuring the GPT-2 model along with demonstration of appropriate testing to verify its functioning.


### Task 2 | Transformer Architectural Changes (40 Points)

---

In the second task, you are required to add alterations to your original GPT-2 model architecture to experiment and assess the potential of improvements. Here's what you need to do:

- **Rotary Positional Embedding:** Replace the original positional embeddings in the GPT-2 model with Rotary embeddings. You may refer to [Su et. al. RoFormer](https://arxiv.org/pdf/2104.09864.pdf).
- **Group Query Attention:** Equip your model with the Group Query Attention mechanism following the insights from the [Ainslie et. al. GQA: Training Generalized Multi-Query Transformer](https://arxiv.org/pdf/2305.13245v2.pdf). Analyze how this mechanism can modify the model's operation compared to the standard attention mechanism.
- **Sliding Window Attention:** Imbibe the Sliding Window Attention mechanism in your model and observe its effects on model performance. Refer to the work by [Beltagy et. al. Longformer](https://arxiv.org/pdf/2004.05150v2.pdf) for better comprehension of its implementation and advantages.

**Deliverable:** Python code with any one, two or all three changes. Comment on the model size and capabilities, potential pitfalls and/or any improvement after each change. Points will be awarded for any combination of successful implementations.

**Evaluation Scheme:** Each feature implementation will account for:

- Rotary Positional Embedding: 15 points
- Group Query Attention: 10 points
- Sliding Window Attention: 15 points
