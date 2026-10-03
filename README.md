# AI Techniques

**기호주의**
- Search
  - BFS·DFS (Iterative Deepening)
  - Uniform Cost Search
  - A* Search (Greedy Best-First)
  - Local Search (Hill Climbing, Simulated Annealing, Genetic Algorithm)
  - CSP (Backtracking, Arc Consistency)
  - Minimax (Alpha-Beta Pruning, Expectimax)
  - MCTS (UCT)
- Rule-based Inference (Forward Chaining, Backward Chaining)
- Logic
  - Propositional Logic (Model Checking, Resolution)
  - SAT Solving (DPLL, WalkSAT)
  - First-order Logic (Unification, Resolution)
  - Logic Programming (Prolog, Datalog)
  - Answer Set Programming (Non-monotonic Reasoning)
  - LLM + Logic Solver (Logic-LM, Z3)
- Planning
  - Classical Planning (STRIPS, PDDL)
  - HTN Planning
  - LLM + Planner (LLM+P, PDDL Generation)
- Knowledge Representation (Semantic Network, Frame, Description Logic)

**고전 머신러닝**
- Linear Regression (Ridge, Lasso)
- Logistic Regression
- KNN
- Naive Bayes
- Decision Tree
- SVM (Kernel)
- Ensemble (Bagging, Boosting, Stacking)
- Random Forest
- Gradient Boosting
- K-means
- Hierarchical Clustering
- DBSCAN
- GMM (EM)
- PCA
- Matrix Factorization (Collaborative Filtering)
- t-SNE (UMAP)

**확률 그래프 모델**
- Bayesian Network
- Exact Inference (Variable Elimination)
- HMM (Forward-Backward, Viterbi)
- MCMC (Metropolis-Hastings, Gibbs)

**머신러닝 평가**
- Regression Metrics (MSE, RMSE, MAE, R²)
- Classification Metrics (Precision, Recall, F1)
- ROC-AUC
- Cross-Validation
- Learning Curve (Bias-Variance)

**신경망 학습**
- Perceptron
- Loss Function (MSE, Cross-Entropy)
- Gradient Descent (Batch, SGD, Mini-batch)
- Backpropagation
- Automatic Differentiation
- Activation Function (ReLU, GELU, Softmax)
- Weight Initialization (Xavier, He)
- Optimizer (Momentum, Adam, AdamW)
- Learning Rate Scheduling (Warmup, Cosine)
- Regularization (Dropout, Weight Decay, Early Stopping)
- Data Augmentation
- Normalization (Batch Norm, Layer Norm, RMSNorm)
- Residual Connection
- Gradient Clipping
- Transfer Learning
- Contrastive Learning (CLIP)
- Hyperparameter Tuning (Grid, Random, Bayesian)

**신경망 아키텍처**
- MLP
- CNN
- RNN (LSTM, GRU)
- Seq2Seq (Attention)
- Transformer
  - Attention (Self, Cross, Causal, MHA, GQA)
  - Positional Encoding (Absolute, Relative, RoPE, ALiBi)
  - Transformer Variants (Encoder-only, Decoder-only, Encoder-Decoder)
  - SwiGLU
  - MoE
- GNN
- VLM (Projector, Cross-attention)
- Autoencoder
- VAE
- GAN
- Diffusion (DDPM, Flow Matching)

**자연어 처리**
- Tokenization (BPE, WordPiece)
- TF-IDF
- N-gram Language Model
- Word2Vec
- Language Modeling Objective (MLM, CLM)
- Sentence Embedding

**강화학습**
- Multi-armed Bandit (ε-greedy, UCB)
- Value Iteration
- Policy Iteration
- Monte Carlo Method
- TD Learning (SARSA)
- Q-Learning
- DQN
- Policy Gradient (REINFORCE)
- Actor-Critic
- PPO

**LLM 학습·파인튜닝**
- Pretraining
- SFT
- Synthetic Data (Self-Instruct)
- LoRA (QLoRA)
- Distillation
- RLHF (Reward Model, PPO)
- DPO
- GRPO (RLVR)

**LLM 생성·서빙**
- Decoding (Greedy, Beam Search, Top-k, Top-p)
- Constrained Decoding (JSON Schema, Grammar)
- KV-Cache
- Prefix Caching
- Quantization (PTQ, GPTQ, AWQ)

**프롬프트·컨텍스트**
- Prompt Engineering (Few-shot)
- Context Engineering
- Context Compression

**LLM 추론 강화**
- Chain-of-Thought
- Self-Consistency
- Test-time Compute Scaling (Best-of-N)
- Tree Search (Tree of Thoughts, MCTS)
- MoA

**LLM 에이전트**
- Tool Calling
- Agentic Workflow (Chaining, Routing, Parallelization)
- ReAct
- Human-in-the-Loop (Approval)
- Memory (Short-term, Long-term)
- Plan-and-Execute
- Reflection
- Computer Use
- Multi-Agent (Orchestrator-Worker, Debate)

**LLM 평가**
- Benchmark Scoring (Log-likelihood, Exact Match)
- Regression Test
- LLM-as-a-Judge
- Pairwise Comparison (Elo)
- Hallucination Detection
- Agent Evaluation (pass@k, Trajectory)

**LLM 안전·보안**
- Prompt Injection (Direct, Indirect)
- Jailbreak
- Data Poisoning
- Content Filtering (Input, Output, PII)
- Automated Red Teaming

**AI 서비스 운영**
- Streaming Response (SSE)
- Output Validation (Schema, Retry)
- Retry·Fallback (Exponential Backoff)
- Rate Limiting
- Response Caching (Exact, Semantic)
- Token·Latency·Cost Tracking
- Model Routing (Cascade)
- A/B Testing
- User Feedback Loop
- Drift Detection (Data Drift, Concept Drift)
