# Full-Stack Python & AI / ML Development
## Professional 3-Month Course Lecture Sheet

**Technologies Covered:** Python 3.12+ • NumPy • Pandas • Matplotlib • Seaborn • SciPy • SQL & PostgreSQL • SQLAlchemy • Scikit-Learn • PyTorch • OpenCV • HuggingFace Transformers • Ollama (Local LLMs) • ChromaDB / Vector DBs • LangChain • FastAPI • Docker • MLflow • GitHub Actions (CI/CD) • Cloud Deployment (Render/AWS/VPS)

---

### Course Metrics & Format
- **Duration**: 3 Months (12 Weeks)
- **Teaching Sessions**: 30 Classes (2.5 - 3 Hours per Class)
- **Assessment Classes**: 6 Milestone Phase Assessments
- **Learning Model**: Project-Driven & Industry-Oriented
- **Capstone Project**: Enterprise AI-Powered Predictive & RAG Platform

---

### Student Success Roadmap — How to Get the Best Result
1. **01 • Learn**: Master the fundamental concepts and theoretical foundations before copying or writing code.
2. **02 • Practice**: Complete all hands-on in-class exercises and solve the dedicated Home Task Problem after each lecture.
3. **03 • Build**: Progressively integrate every newly acquired skill into the course capstone project module by module.
4. **04 • Ship**: Test, document, containerize, deploy to a live production environment, and present the final capstone in viva.

> **Student Standard**: Keep your GitHub commit streak active, debug your own stack traces using logs, ask questions in group discussions, review weekly topics, and never leave a practical home task unfinished.

---

## Program Overview

This course takes students from core Python programming to building production-ready Artificial Intelligence, Machine Learning, Deep Learning, and Generative AI applications served via high-performance FastAPI backends and deployed with modern MLOps pipelines.

### 1. Learning Outcomes
- Write clean, modular, object-oriented, and production-grade Python code using Python 3.12+ standards.
- Perform high-performance numerical computing with NumPy and complex data wrangling, cleaning, and EDA with Pandas & Seaborn.
- Design relational database schemas, write advanced SQL queries, and connect Python to PostgreSQL using SQLAlchemy ORM.
- Build, tune, and evaluate classic Machine Learning models (Regression, Classification, Ensemble Trees like XGBoost, Clustering, PCA) using Scikit-Learn.
- Construct and train Deep Neural Networks, Convolutional Neural Networks (CNNs), and Sequence Models using PyTorch & OpenCV.
- Master Generative AI, Fine-Tuning principles, Local LLM deployment (Ollama), Vector Search (ChromaDB), RAG architectures, and AI Agents with LangChain.
- Expose machine learning and generative AI workflows via async FastAPI REST endpoints with Pydantic validation.
- Implement MLOps best practices: MLflow experiment tracking, Docker containerization, pytest suites, GitHub Actions CI/CD pipelines, and cloud server deployment.

### 2. Course Format Summary
| Parameter | Detail |
| :--- | :--- |
| **Duration** | 3 Months |
| **Teaching Sessions** | 30 Classes |
| **Assessment Classes** | 6 Classes (After every 5 classes) |
| **Delivery Style** | Project-Driven & Hands-On |
| **Recommended Class Duration** | 2.5 – 3 Hours |

### 3. Technology Baseline
`Python 3.12+` `NumPy` `Pandas` `Matplotlib & Seaborn` `SciPy` `PostgreSQL` `SQLAlchemy` `Scikit-Learn` `XGBoost` `PyTorch` `OpenCV` `HuggingFace` `Ollama` `ChromaDB` `LangChain` `FastAPI` `Docker` `MLflow` `pytest` `GitHub Actions` `Nginx / VPS Deployment`

### 4. Progressive Capstone Project
Students progressively construct an **Enterprise AI-Powered Intelligence Platform** featuring:
- Automated ETL data processing pipelines and relational PostgreSQL database storage.
- Predictive Analytics Module powered by tuned XGBoost models for business metrics prediction.
- Deep Learning Vision Module using PyTorch transfer learning for image processing.
- Generative AI Document Q&A (RAG) powered by local Ollama / HuggingFace models and ChromaDB vector search.
- Enterprise-grade FastAPI REST API with JWT security, rate limiting, and SSE streaming.
- Docker multi-container setup, GitHub Actions CI/CD pipeline, and live cloud deployment with complete technical documentation.

---

## Detailed 30-Class Curriculum Breakdown

### Phase 1 — Python Core Foundations & Algorithmic Thinking (Classes 01–05)
*Build a bulletproof programming foundation with clean Python syntax, data structures, functional patterns, object-oriented architecture, file operations, and virtual environments.*

---

#### Class 01: Python Fundamentals & Development Setup
- **Topic 1 — Python Ecosystem & Environment Setup**: Understand Python runtime architecture, Python 3.12 features, installing VS Code, configuring virtual environments (`venv`/`conda`), package management with `pip`, script execution, and workspace structure.
- **Topic 2 — Syntax, Variables & Primitive Types**: Master dynamic typing, integers, floats, booleans, string manipulation, type casting, input/output formatting, and clean variable naming conventions.
- **Home Task Problem**: Set up a clean VS Code development environment, create a virtual environment, and write a interactive CLI utility script that accepts user inputs, calculates financial/unit metrics, and prints a formatted report.

---

#### Class 02: Data Structures & Control Flow
- **Topic 1 — Control Flow & Logic Branching**: Master `if/elif/else` statements, truthy/falsy values, ternary operators, `while` loops, `for` loops, `range()`, and loop control primitives (`break`, `continue`, `pass`).
- **Topic 2 — Core Built-in Data Structures**: Work with Lists, Tuples, Sets, and Dictionaries. Understand mutability vs immutability, sequence slicing (`[start:stop:step]`), dictionary lookup speed, and common data structure methods.
- **Home Task Problem**: Build a interactive CLI Student Grade & Performance Management System that allows adding student records, calculating averages, finding highest/lowest scorers, and filtering top performers.

---

#### Class 03: Functions, Modules & Functional Programming
- **Topic 1 — Reusable Function Design**: Define functions with positional parameters, keyword arguments, default values, `*args`, `**kwargs`, return types, type hinting, variable scope (`global`/`local`), and Google-style docstrings.
- **Topic 2 — Functional Patterns & Comprehensions**: Practice Lambda functions, `map()`, `filter()`, List/Dict/Set comprehensions, generator expressions, and modularizing code into custom Python packages.
- **Home Task Problem**: Write a collection of reusable mathematical and string processing helper modules using comprehensions and lambda filters to clean and process a multi-nested dataset list.

---

#### Class 04: Object-Oriented Programming (OOP) in Python
- **Topic 1 — Classes, Objects & Encapsulation**: Understand class definitions, `__init__` constructors, instance vs class variables, magic/dunder methods (`__str__`, `__repr__`, `__len__`), private attributes (`_`, `__`), and getter/setter property decorators (`@property`).
- **Topic 2 — Inheritance, Polymorphism & Composition**: Implement single/multiple inheritance, `super()`, method overriding, Abstract Base Classes (`abc`), duck typing, and object composition patterns.
- **Home Task Problem**: Design an OOP Banking Domain Model with `Account`, `Customer`, `Transaction`, and `Bank` classes implementing deposit, withdrawal, interest calculation, balance validation, and transaction audit trails.

---

#### Class 05: File Handling, Exception Handling & Environment Isolation
- **Topic 1 — File I/O & Serialization**: Read and write plain text files, CSV files using `csv` module, JSON files using `json` module, context managers (`with` statement), and file system operations using `pathlib`.
- **Topic 2 — Exception Handling & Environment Management**: Handle runtime errors with `try/except/else/finally`, define custom exception classes, handle exception chaining, structure `requirements.txt`, and load environment variables with `python-dotenv`.
- **Home Task Problem**: Build a robust CSV Data Importer and JSON Summary Generator that parses raw data, validates data types, catches file/formatting exceptions, logs errors, and outputs clean summary analytics.

---

### Phase 2 — Data Science Foundations & Numerical Computing (Classes 06–10)
*Transition from base Python into high-performance array operations, data manipulation with Pandas, scientific visualization, statistics, and SQL database interactions.*

---

#### Class 06: High-Performance Computing with NumPy
- **Topic 1 — NumPy Ndarrays & Vectorization**: Master N-dimensional array creation, data types (`dtype`), shape manipulation (`reshape`, `transpose`), vectorization vs Python loops, slicing, and broadcasting rules.
- **Topic 2 — Matrix Operations & Statistical Aggregations**: Perform matrix multiplication (`@`), linear algebra operations (`np.linalg`), random number sampling (`np.random`), boolean masking, and axis aggregations (`sum`, `mean`, `std`).
- **Home Task Problem**: Build a financial portfolio risk simulator using vectorized NumPy array math to calculate daily returns, variance-covariance matrices, standard deviations, and Monte Carlo projections over 1,000 simulations.

---

#### Class 07: Data Manipulation & Wrangling with Pandas
- **Topic 1 — Pandas Series & DataFrames**: Create DataFrames, index data with `.loc` and `.iloc`, filter rows with logical conditions, handle missing data (`isna`, `fillna`, `dropna`), and transform column types.
- **Topic 2 — Advanced Wrangling & Merging**: Group data with `.groupby()`, compute multi-level aggregations, create pivot tables, merge tables (`merge`, `concat`, `join`), apply custom functions (`.apply()`), and handle time-series data.
- **Home Task Problem**: Clean and wrangle a multi-table E-Commerce sales dataset by handling missing values, parsing timestamps, aggregating revenue per product category, and joining customer/order tables into an analysis dataset.

---

#### Class 08: Data Visualization & Exploratory Data Analysis (EDA)
- **Topic 1 — Statistical Visualization Tools**: Master line charts, bar plots, histograms, KDE density plots, box plots, scatter plots, pair plots, and correlation heatmaps using Matplotlib and Seaborn.
- **Topic 2 — Exploratory Data Analysis (EDA) Methodology**: Detect data distribution skewness, identify multivariate relationships, spot extreme outliers, evaluate feature correlations, and summarize actionable data insights.
- **Home Task Problem**: Perform a complete EDA on a Telecommunication Customer Churn dataset, generate 6 publication-quality charts (correlation heatmap, churn rate by tenure boxplot, categorical bar plots), and write an executive summary report.

---

#### Class 09: Applied Statistics & Probability for ML
- **Topic 1 — Descriptive & Inferential Statistics**: Measures of central tendency (mean, median, mode), spread (variance, standard deviation, IQR), probability distributions (Normal, Binomial, Poisson), Z-scores, and Central Limit Theorem (CLT).
- **Topic 2 — Hypothesis Testing & Correlation**: Formulate null/alternative hypotheses, p-values, t-tests, Chi-Square independence tests, ANOVA, Pearson vs Spearman correlation, and confidence intervals using SciPy.
- **Home Task Problem**: Conduct A/B test analysis on e-commerce landing page conversion rates using SciPy, computing required sample sizes, p-values, t-test statistics, and confidence intervals to validate design recommendations.

---

#### Class 10: Relational Databases, SQL & Python Integration
- **Topic 1 — SQL Relational Database Queries**: Master table schemas, data types, primary/foreign key constraints, `SELECT`, `WHERE`, `JOIN` (`INNER`, `LEFT`, `RIGHT`), `GROUP BY`, `HAVING`, subqueries, aggregate functions, and window functions.
- **Topic 2 — Python Database Integration & SQLAlchemy**: Connect Python to PostgreSQL/SQLite via `psycopg2` / `sqlite3`, execute parameterized SQL queries to prevent injection, use SQLAlchemy ORM models, session management, and load query results into Pandas DataFrames.
- **Home Task Problem**: Build a Python script that connects to a PostgreSQL database, creates normalized user/sales tables, populates realistic sample data via transactions, executes 5 complex analytical queries, and exports reports into Pandas DataFrames.

---

### Phase 3 — Machine Learning Core & Predictive Modeling (Classes 11–15)
*Master the machine learning workflow using Scikit-Learn: feature engineering, supervised regression and classification, ensemble tree algorithms, unsupervised clustering, and hyperparameter tuning.*

---

#### Class 11: Machine Learning Workflow & Scikit-Learn Pipeline
- **Topic 1 — ML Problem Formulation & Preprocessing**: Supervised vs Unsupervised learning types, feature vectors vs target variables, train/test splitting (`train_test_split`), preventing data leakage, numerical scaling (`StandardScaler`, `RobustScaler`), and categorical encoding (`OneHotEncoder`, `TargetEncoder`).
- **Topic 2 — Scikit-Learn Estimator API & Custom Pipelines**: Understand `fit()`, `transform()`, `predict()` methods, `ColumnTransformer`, constructing multi-step `Pipeline` objects, and serializing pipelines with `joblib`.
- **Home Task Problem**: Build a production Scikit-Learn preprocessing and modeling pipeline for a raw dataset containing mixed numerical and categorical features, evaluate baseline accuracy, and serialize the pipeline artifact.

---

#### Class 12: Supervised Learning I — Regression Models & Metrics
- **Topic 1 — Linear, Ridge & Lasso Regression**: Ordinary Least Squares (OLS) mathematical intuition, gradient descent optimization, cost functions, L1 (Lasso) vs L2 (Ridge) regularization penalty terms, and feature selection.
- **Topic 2 — Regression Metrics & Residual Diagnostics**: Evaluate models using Mean Squared Error (MSE), Root Mean Squared Error (RMSE), Mean Absolute Error (MAE), R-Squared ($R^2$), Adjusted $R^2$, residual plots, and homoscedasticity checks.
- **Home Task Problem**: Build a Real Estate House Price Prediction model using Lasso and Ridge regression, analyze coefficient feature importances, plot residual errors, and document MSE/RMSE/$R^2$ performance metrics.

---

#### Class 13: Supervised Learning II — Classification & Ensemble Methods
- **Topic 1 — Classification Algorithms & Decision Boundaries**: Logistic Regression, Decision Trees, K-Nearest Neighbors (KNN), Naive Bayes, and Support Vector Machines (SVM).
- **Topic 2 — Ensemble Tree Methods & Class Imbalance**: Bagging vs Boosting principles, Random Forests, XGBoost / LightGBM gradient boosting, feature importance ranking, and handling imbalanced datasets using SMOTE and class weighting.
- **Home Task Problem**: Train a Credit Risk Default Classifier using Random Forest and XGBoost, apply SMOTE to balance target classes, tune decision thresholds, evaluate precision-recall trade-offs, and plot ROC-AUC curves.

---

#### Class 14: Unsupervised Learning — Clustering & Dimensionality Reduction
- **Topic 1 — Clustering Algorithms**: K-Means clustering, distance metrics, selecting optimal clusters via Elbow Method and Silhouette Analysis, Hierarchical Clustering (Dendrograms), and DBSCAN density-based clustering.
- **Topic 2 — Dimensionality Reduction**: Principal Component Analysis (PCA) variance maximization, eigenvalues/eigenvectors intuition, explained variance ratio, and high-dimensional visualization with t-SNE / UMAP.
- **Home Task Problem**: Segment an e-commerce customer database using K-Means and PCA, plot customer segments in 2D space using Matplotlib, calculate Silhouette scores, and define distinct customer buyer personas.

---

#### Class 15: Model Evaluation, Cross-Validation & Hyperparameter Tuning
- **Topic 1 — Validation Strategies & Diagnostic Metrics**: K-Fold Cross-Validation, Stratified K-Fold, TimeSeriesSplit, Confusion Matrix, Precision, Recall, F1-Score, Macro/Micro averages, and ROC-AUC curve evaluation.
- **Topic 2 — Hyperparameter Optimization**: Grid Search CV, Random Search CV, Bayesian Optimization using `Optuna`, hyperparameter search spaces, and preventing model overfitting vs underfitting.
- **Home Task Problem**: Optimize an XGBoost classification pipeline using Optuna and Stratified 5-Fold Cross-Validation, output full classification reports, plot confusion matrices, and document final tuned parameters.

---

### Phase 4 — Deep Learning, Neural Networks & Computer Vision (Classes 16–20)
*Dive into Deep Learning fundamentals using PyTorch: tensor math, autograd, custom neural network architectures, training loops, computer vision with OpenCV, CNNs, transfer learning, and NLP sequence models.*

---

#### Class 16: Deep Learning Fundamentals & PyTorch Core Tensors
- **Topic 1 — Neural Network Intuition & PyTorch Tensors**: Perceptron mechanics, activation functions (ReLU, Sigmoid, Softmax), PyTorch tensor creation, CPU vs GPU CUDA acceleration (`.to('cuda')`), tensor shapes, and automatic differentiation (`autograd` & `.backward()`).
- **Topic 2 — Custom Dataset & DataLoader API**: Subclassing `torch.utils.data.Dataset`, implementing `__len__` and `__getitem__`, using `DataLoader` for mini-batching, shuffling, multi-worker loading, and data transformations.
- **Home Task Problem**: Write a custom PyTorch `Dataset` and `DataLoader` for a tabular dataset, perform GPU tensor operations, execute forward/backward autograd passes, and verify gradient updates.

---

#### Class 17: Custom Neural Networks & PyTorch Training Loop
- **Topic 1 — Building Custom `nn.Module` Architectures**: Linear layers (`nn.Linear`), activation layers, dropout regularization (`nn.Dropout`), batch normalization (`nn.BatchNorm1d`), and forward pass execution.
- **Topic 2 — Complete PyTorch Training & Validation Loop**: Loss functions (`MSELoss`, `CrossEntropyLoss`), optimizers (`SGD`, `AdamW`), learning rate schedulers, epoch iteration, metric tracking, validation evaluation, and model checkpointing (`torch.save`).
- **Home Task Problem**: Build and train a Multi-Layer Perceptron (MLP) image classifier on Fashion-MNIST from scratch in PyTorch, implement validation logging, plot loss/accuracy curves, and save the best model weights.

---

#### Class 18: Computer Vision Essentials with OpenCV
- **Topic 1 — Digital Image Processing Foundations**: Color space conversions (RGB, BGR, HSV, Grayscale), image loading, resizing, cropping, rotation, affine transformations, thresholding, and morphological operations (erosion, dilation).
- **Topic 2 — Feature Extraction & Object Contours**: Edge detection using Sobel and Canny filters, finding contours (`cv2.findContours`), bounding box drawing, histogram equalization, and object tracking basics.
- **Home Task Problem**: Build an automated document scanner script using OpenCV that detects page corners, applies perspective warping, enhances text contrast, and crops page regions automatically.

---

#### Class 19: Convolutional Neural Networks (CNNs) & Transfer Learning
- **Topic 1 — CNN Architecture & Feature Extraction**: Convolutional layers (`nn.Conv2d`), max/average pooling (`nn.MaxPool2d`), stride, padding, receptive field concepts, and CNN feature map visualization.
- **Topic 2 — Transfer Learning with Pretrained Vision Backbones**: Fine-tuning ResNet50 / EfficientNet / MobileNet using `torchvision.models`, frozen vs trainable backbone layers, custom classification heads, and data augmentation (`transforms.v2`).
- **Home Task Problem**: Build a medical/botanical image classifier (e.g. leaf disease detector) using transfer learning with ResNet50 in PyTorch, implementing data augmentation, achieving >90% test accuracy, and evaluating confusion matrices.

---

#### Class 20: NLP Fundamentals, Embeddings & Sequence Models
- **Topic 1 — Text Processing, Tokenization & Word Embeddings**: Text normalization, lowercasing, stopword removal, stemming/lemmatization, Bag-of-Words, TF-IDF, Word2Vec embeddings, and PyTorch `nn.Embedding` layer.
- **Topic 2 — Sequence Models & Transformer Attention Intuition**: Recurrent Neural Networks (RNNs), LSTMs, GRUs, vanishing gradient solutions, self-attention mechanism intuition, and Transformer encoder-decoder structural basics.
- **Home Task Problem**: Train a sentiment analysis model using a PyTorch LSTM network on a movie review dataset, using custom tokenization, word embeddings, and evaluating accuracy on unseen test reviews.

---

### Phase 5 — Applied AI, Generative AI & LLMs (Classes 21–25)
*Step into cutting-edge AI: Hugging Face ecosystem, fine-tuning concepts, local LLM execution with Ollama, Vector Databases, Retrieval-Augmented Generation (RAG), AI Agents, and serving models via FastAPI.*

---

#### Class 21: Hugging Face Ecosystem & Pretrained Transformers
- **Topic 1 — Hugging Face Hub & Transformers Library**: Loading pretrained transformer models (`AutoModelForCausalLM`, `AutoTokenizer`), model generation parameters (`temperature`, `top_p`, `top_k`, `max_new_tokens`), and pipeline APIs.
- **Topic 2 — LLM Fine-Tuning & Quantization Concepts**: Full fine-tuning vs PEFT (Parameter-Efficient Fine-Tuning), LoRA / QLoRA adapters, 8-bit & 4-bit model quantization, Hugging Face `SFTTrainer`, and evaluation.
- **Home Task Problem**: Load an open-weights LLM (e.g., Llama-3-8B / Qwen-2.5) via Hugging Face Transformers, construct text generation pipelines with custom sampling parameters, and write an automated text summarization utility.

---

#### Class 22: Local LLM Execution (Ollama) & Advanced Prompt Engineering
- **Topic 1 — Local LLM Deployment with Ollama**: Installing Ollama, pulling local models (Llama 3.2, Mistral, DeepSeek), customizing Modelfiles, system prompts, running local REST servers, and integration via Python SDK (`ollama-python`).
- **Topic 2 — Prompt Engineering & Structured JSON Output**: Zero-shot, Few-shot, Chain-of-Thought (CoT) prompting strategies, ReAct framework, persona definition, and enforcing structured Pydantic JSON output schema.
- **Home Task Problem**: Build a local CLI AI Document Information Extractor powered by Ollama that reads unstructured resume text and enforces a Pydantic JSON schema to return structured candidate details.

---

#### Class 23: Retrieval-Augmented Generation (RAG) & Vector Databases
- **Topic 1 — Vector Embeddings & Vector Search Mechanics**: Text embedding generation using `sentence-transformers`, similarity metrics (Cosine Similarity, Euclidean Distance, Dot Product), HNSW indexing, and vector database architecture.
- **Topic 2 — Building RAG Pipelines with ChromaDB & FAISS**: Document loading (PDF, TXT, Markdown), text chunking strategies (`RecursiveCharacterTextSplitter`), indexing vectors into ChromaDB / FAISS, context retrieval, and augmented prompt generation.
- **Home Task Problem**: Build a complete Document Q&A RAG application that ingests a multi-page PDF document, indexes vector embeddings into ChromaDB, and answers user questions with exact document page citations.

---

#### Class 24: AI Agents, Tools & Workflows with LangChain / LlamaIndex
- **Topic 1 — LangChain Core Architecture & Memory**: Chains (`LLMChain`), Memory management (`BufferMemory`, `VectorStoreMemory`), Document Loaders, Indexing abstractions, and output parsers.
- **Topic 2 — AI Agent Systems & Function Calling**: Defining custom Python tool functions, agent reasoning execution loops (ReAct pattern), multi-tool decision selection, error handling, and guardrails.
- **Home Task Problem**: Build an autonomous AI Research Agent using LangChain that accepts a research topic, queries a web search API tool, queries an internal vector database tool, performs calculations, and outputs a synthesized markdown research report.

---

#### Class 25: Serving AI Models with FastAPI Backend
- **Topic 1 — Modern FastAPI Web Architecture**: Asynchronous request handling (`async/await`), Pydantic request/response validation schemas, Dependency Injection (`Depends`), CORS middleware, and API Routers.
- **Topic 2 — Building Production REST APIs for AI Workflows**: Real-time response streaming (`StreamingResponse` / Server-Sent Events for LLMs), custom exception handlers, background tasks, and interactive OpenAPI (Swagger) documentation.
- **Home Task Problem**: Build a production FastAPI backend service exposing REST endpoints for: (1) Predictive ML classification, (2) Vector similarity search, and (3) Real-time streaming LLM answer generation with Pydantic schema validation.

---

### Phase 6 — MLOps, Quality Assurance & Live Cloud Deployment (Classes 26–30)
*Bring your AI applications to production readiness: experiment tracking, Docker containerization, automated testing with pytest, security, GitHub Actions CI/CD pipelines, and cloud server deployment.*

---

#### Class 26: Model Tracking, Versioning & MLOps Pipelines
- **Topic 1 — Experiment Tracking with MLflow & W&B**: Logging hyperparameters, metrics, confusion matrix artifacts, model binaries, model lineage tracking, and using MLflow Model Registry (`mlflow.register_model`).
- **Topic 2 — Data & Model Version Control**: Versioning raw datasets and model weights with DVC (Data Version Control), configuring remote storage backends, and building reproducible ML pipelines.
- **Home Task Problem**: Integrate MLflow experiment tracking into an XGBoost model training script, logging parameters, metrics, artifact confusion matrices, and registering the top-performing model artifact into the registry.

---

#### Class 27: Containerization with Docker for AI/ML Apps
- **Topic 1 — Docker Foundations & Multi-Stage Builds**: Dockerfiles, selecting base images (`python:3.12-slim`), package installation, layer caching optimization, `.dockerignore`, and multi-stage build optimization for slim container sizes.
- **Topic 2 — Multi-Container Systems with Docker Compose**: Writing `docker-compose.yml` to orchestrate FastAPI backend service, PostgreSQL database container, ChromaDB vector database container, environment variable loading, and bridge networks.
- **Home Task Problem**: Write Dockerfiles and a `docker-compose.yml` configuration to orchestrate your FastAPI backend service, PostgreSQL database, and ChromaDB vector store into a single command setup (`docker compose up`).

---

#### Class 28: Production Security, Model Optimization & Monitoring
- **Topic 1 — AI API Security & Secrets Management**: API Key & JWT authentication middleware, rate limiting (`slowapi`), CORS protection, secure environment variable management (`python-dotenv`), and sanitizing inputs against prompt injection attacks.
- **Topic 2 — Model Inference Optimization & Health Monitoring**: Model quantization & export (ONNX Runtime, TensorRT), latency reduction, health check endpoints (`/healthz`), structured logging (`structlog`), and monitoring metrics.
- **Home Task Problem**: Secure your FastAPI AI microservice by adding JWT authentication, rate limiting (10 requests/min), ONNX runtime model inference acceleration, structured JSON logging, and a health check endpoint.

---

#### Class 29: GitHub Workflow, CI/CD & Automated Testing
- **Topic 1 — Automated Testing & Code Quality Tools**: Unit testing with `pytest`, API endpoint integration testing with `httpx` / `TestClient`, code formatting & linting (`ruff`, `black`, `mypy`), and assertion best practices.
- **Topic 2 — GitHub Actions CI/CD Pipeline**: Writing `.github/workflows/ci.yml`, running pytest test suites on pull requests, building Docker container images automatically, pushing to Docker Hub / GitHub Container Registry (GHCR), and automated deployment triggers.
- **Home Task Problem**: Create pytest test suites for your FastAPI endpoints and ML data preprocessors, and configure a GitHub Actions workflow that executes linting, runs unit tests, builds the Docker image, and verifies build pass status.

---

#### Class 30: Final Capstone Integration, Live Deployment & Handover
- **Topic 1 — Live Cloud Server Deployment (VPS / Cloud)**: Provisioning Linux VPS / Cloud servers (Render, AWS EC2, DigitalOcean), Nginx reverse proxy setup, SSL certificate installation (`certbot`), systemd service management, and production domain routing.
- **Topic 2 — Production Monitoring, Documentation & Viva Presentation**: Live verification of database connectivity, background tasks, automated rollback strategies, README & Swagger API documentation, demo data seeding, and professional viva presentation skills.
- **Home Task Problem**: Deploy your complete Capstone Enterprise AI Platform to a live server URL, submit the GitHub repository with comprehensive README, setup instructions, architecture diagram, video demo link, and complete production verification checklist.

---

## Assessment Plan & Final Evaluation

Six structured milestone assessments evaluate practical technical progress after each learning phase.

```
01 • Assessment 1 (After Class 05) — Python Core & OOP Foundations
     Build a CLI-based modular Python application using OOP principles, inheritance, custom exception handling, and file operations.

02 • Assessment 2 (After Class 10) — Data Wrangling, EDA & SQL Pipeline
     Clean a messy dataset using Pandas, generate publication-ready EDA charts, and execute analytical SQL queries in PostgreSQL via SQLAlchemy.

03 • Assessment 3 (After Class 15) — End-to-End Scikit-Learn ML Pipeline
     Train, tune, and evaluate an XGBoost predictive model pipeline with cross-validation, hyperparameter tuning (Optuna), and model serialization.

04 • Assessment 4 (After Class 20) — PyTorch Deep Learning & Vision Classifier
     Construct a custom PyTorch CNN / Transfer Learning pipeline for image classification, featuring custom DataLoader, training loss curves, and evaluation metrics.

05 • Assessment 5 (After Class 25) — Full-Stack RAG & FastAPI AI Microservice
     Build an async FastAPI service featuring Vector Search (ChromaDB), Ollama / HuggingFace LLM response generation, and SSE streaming endpoints.

06 • Assessment 6 (After Class 30) — Final Capstone Evaluation & Live Viva
     Present live deployed Capstone AI application, complete code review viva, and submit GitHub repo, Docker setup, README documentation, and live URL.
```

---

### Suggested Grading Scheme
- **Assignments & In-Class Home Tasks**: 20%
- **Phase Milestone Assessments (1 to 5)**: 30%
- **Final Capstone Project**: 30%
- **Viva & Code Review Presentation**: 10%
- **Attendance & Professional Participation**: 10%

---

### Final Student Deliverables Checklist
- [ ] GitHub Source Code Repository (clean commit history, clear structure).
- [ ] PostgreSQL Database Migration / Seed scripts.
- [ ] Exported ML Model & Preprocessing Pipeline Artifacts (`.joblib` / `.onnx` / PyTorch `.pt`).
- [ ] Vector Database index setup (ChromaDB / FAISS).
- [ ] `Dockerfile` and `docker-compose.yml` multi-container setup.
- [ ] Complete `README.md` with installation, setup, architecture diagram, and API docs.
- [ ] Live Deployed Capstone Web App / API URL (with HTTPS SSL).
- [ ] 5-minute video walkthrough demo link & live presentation slides.

---

### Production Technology Skills Included in This Course
- **GitHub Workflow**: Multi-branch git flow, pull request reviews, feature branching, release tagging.
- **MLOps & Experiment Tracking**: MLflow tracking server, parameter logging, artifact versioning with DVC.
- **CI/CD Pipeline**: GitHub Actions workflows, automated linting (`ruff`), unit testing (`pytest`), Docker image builds.
- **Server Configuration & Deployment**: Linux/VPS server configuration, Nginx reverse proxy, SSL HTTPS configuration, systemd services, environment variables, live model inference monitoring.

> **Final Production Standard**: Students must be capable of taking a raw data problem, engineering predictive & Generative AI models, wrapping them into high-performance FastAPI backends, containerizing with Docker, and deploying to live cloud servers via CI/CD automation.

---

**Developed by:** Robiul Suny Emon

