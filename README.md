<div align="center">

<img src="https://avatars.githubusercontent.com/u/156014441?v=4" width="120" style="border-radius: 50%;" />

# Deepika Nuthalapati

**Machine Learning Engineer** — Computer Vision · Applied AI · MLOps

Graduate Researcher, [2AI Applied AI Lab](https://github.com/2ai-lab) · University of South Dakota  
NSF Consultant · Research Associate, Dept. of Computer Science

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://linkedin.com/in/deepika-nuthalapati)
[![USD Profile](https://img.shields.io/badge/USD%20Profile-003087?style=flat-square&logo=academia&logoColor=white)](https://www.usd.edu/research-and-faculty/faculty-and-staff/deepika-nuthalapati)
[![Email](https://img.shields.io/badge/Email-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:deepika.nuthalapati@usd.edu)

</div>

---

## About

I am a graduate researcher in Computer Science at the University of South Dakota, working in the **2AI Applied AI Research Lab** on NSF-funded projects. My research centers on **multimodal deep learning and computer vision** — most recently, building a spatiotemporal Vision Transformer that fuses satellite and meteorological data to analyze climate change impact in South Dakota, work that was presented at both the **USGS EROS Fall Poster Session** and the **OAK Supercomputing Conference** in 2024.

Outside of research, I have spent the past year building a full-stack ML engineering portfolio — 20 end-to-end projects covering the complete lifecycle: data pipelines, model training, deployment, and monitoring. I care as much about how a model gets shipped and maintained as how it gets trained.

I am actively looking for my first full-time ML engineering role.

**Research focus:** Multimodal deep learning · Computer vision · Remote sensing · Medical imaging  
**Engineering focus:** Model deployment · MLOps · NLP · Production ML systems

---

## Research

### Published Poster Work

**Multi-Level Spatiotemporal Vision Transformer for Analyzing Climate Impact in South Dakota**  
*with Krishna Phanindra Marupaka — University of South Dakota*

Presented at two venues in 2024:
- [USGS EROS Fall Poster Session](https://www.usgs.gov/centers/eros/news/usgs-eros-poster-session-links-students-scientists) — November 2024, Sioux Falls, SD
- [3rd OAK Supercomputing Conference](https://www.wichita.edu/services/hpc/oaksupercompute2024/index.php) — May 2024, Wichita, KS

The work builds a multi-level spatiotemporal ViT that processes both satellite imagery and meteorological time-series data together, using cross-modal attention to capture how climate signals evolve across space and time. The model was evaluated on South Dakota land cover and climate datasets from USGS EROS.

**Lab affiliation:** [USD 2AI Applied AI Research Lab](https://github.com/2ai-lab) — founded by Dr. KC Santosh, researching AI applications in healthcare informatics, medical imaging, remote sensing, and computer vision.

---

## Technical Skills

### Machine Learning
| Area | Details |
|---|---|
| Supervised Learning | Classification, regression, feature engineering, hyperparameter tuning |
| Unsupervised Learning | K-Means, DBSCAN, Gaussian Mixture Models, PCA, autoencoders |
| Ensemble Methods | XGBoost, LightGBM, Random Forest, stacking, blending |
| Imbalanced Learning | SMOTE, class weighting, threshold tuning, PR-AUC optimization |
| Model Evaluation | Accuracy, F1, ROC-AUC, PR-AUC, MAE, RMSE, IoU, Dice, mAP |
| Explainability | SHAP (global and local), Grad-CAM, attention weight visualization |

### Deep Learning
| Area | Details |
|---|---|
| CNNs | ResNet-50 via transfer learning, U-Net for segmentation, YOLOv5 for detection |
| RNNs | LSTM, Bidirectional LSTM, Seq2Seq encoder-decoder |
| Transformers | Vision Transformer (ViT), spatiotemporal ViT, BERT/DistilBERT via HuggingFace |
| Multimodal Learning | Cross-modal attention, satellite + meteorological data fusion |
| Generative Models | GANs — adversarial training, batch normalization, LeakyReLU |
| Anomaly Detection | Autoencoder reconstruction error thresholding |
| Reinforcement Learning | DQN with experience replay and target network updates |
| Training Techniques | Mixed-precision (AMP), Dice + BCE loss, CutMix, MixUp, augmentation |

### NLP
| Area | Details |
|---|---|
| Preprocessing | Tokenization, padding, GloVe and transformer embeddings |
| Architectures | Bi-LSTM + Attention, BERT/DistilBERT fine-tuning |
| Tasks | Sentiment analysis, text classification, attention visualization |

### Computer Vision
| Area | Details |
|---|---|
| Classification | Transfer learning (ResNet-50), augmentation pipelines |
| Detection | YOLOv5, bounding box annotation, mAP evaluation |
| Segmentation | U-Net, pixel-level masks, Dice/IoU scoring |
| Recognition | FaceNet embeddings, cosine similarity, identity verification |
| Remote Sensing | Satellite imagery processing, spatiotemporal modeling |

### Data Engineering
| Area | Details |
|---|---|
| ETL Pipelines | Extraction, schema validation, transformation, loading |
| Feature Store | Feast — offline/online store, feature versioning, train/serving consistency |
| Preprocessing | Scaling, encoding, cleaning, imputation |

### MLOps and Deployment
| Area | Details |
|---|---|
| Model Serving | FastAPI REST endpoints, input validation, structured logging |
| Containerization | Docker — reproducible builds, model + API packaged together |
| Experiment Tracking | MLflow — parameter/metric logging, artifact storage, Model Registry |
| CI/CD | GitHub Actions — automated training, testing, and deployment pipelines |
| Optimization | ONNX export, dynamic and static quantization, latency benchmarking |
| Monitoring | Performance drift detection, production metric tracking |

### Tools
| Category | Tools |
|---|---|
| Frameworks | PyTorch, TensorFlow/Keras, Scikit-learn |
| NLP | HuggingFace Transformers |
| MLOps | MLflow, Feast, ONNX Runtime |
| Deployment | FastAPI, Docker, GitHub Actions |
| Vision | OpenCV, Albumentations |
| Data | NumPy, Pandas |
| Cloud | AWS, GCP (working knowledge) |
| Dev | Git, VS Code |

---

## Projects

These projects were built independently to production engineering standards — each one starts from a defined problem, makes deliberate architectural decisions, and is evaluated with appropriate metrics. Not just model training scripts.

---

### Computer Vision

**[Advanced CNN Image Classifier](https://github.com/nuthalapatideepika/cnn-image-classifier)**  
ResNet-50 fine-tuned on a custom dataset with CutMix, MixUp, and color jitter augmentation. Mixed-precision training (AMP) cuts compute time without accuracy loss. Evaluated with Grad-CAM so there is actual visual evidence of what the model learned, not just a number.  
`PyTorch` `ResNet-50` `Albumentations` `AMP` `Grad-CAM`

---

**[YOLO Object Detection Pipeline](https://github.com/nuthalapatideepika/yolo-object-detection)**  
Full detection pipeline from annotation to evaluation using YOLOv5. Covers bounding box labeling, augmented training, and confidence/IoU threshold tuning. Evaluated at multiple IoU thresholds using mAP — the metric that actually matters for detection.  
`YOLOv5` `PyTorch` `OpenCV`

---

**[U-Net Medical Image Segmentation](https://github.com/nuthalapatideepika/unet-medical-segmentation)**  
Pixel-level segmentation of MRI and CT images using a U-Net encoder-decoder. Combined Dice + BCE loss handles the severe foreground/background imbalance in medical images. Evaluated using IoU and Dice score. Connects directly to the lab's medical imaging research.  
`PyTorch` `U-Net` `Dice Loss` `NumPy`

---

**[Face Recognition with Embeddings](https://github.com/nuthalapatideepika/face-recognition-embeddings)**  
Identity verification pipeline using FaceNet for 512-dimensional face embeddings and cosine similarity for matching. Scales to new identities without retraining — a hard requirement for any real deployment.  
`PyTorch` `FaceNet` `OpenCV` `Cosine Similarity`

---

### Natural Language Processing

**[Transformer-Based Text Classifier](https://github.com/nuthalapatideepika/transformer-text-classifier)**  
BERT and DistilBERT fine-tuned on labeled text data using HuggingFace Transformers. Both models evaluated on accuracy, F1, and confusion matrix. DistilBERT achieves comparable accuracy at meaningfully lower inference cost — a useful tradeoff to know for production.  
`HuggingFace` `BERT` `DistilBERT` `PyTorch`

---

**[LSTM + Attention Sentiment Analyzer](https://github.com/nuthalapatideepika/lstm-sentiment-analyzer)**  
Bidirectional LSTM with a custom Attention layer trained on GloVe embeddings. Attention weights are extracted per prediction so you can see which words drove the decision — not just a black-box score.  
`TensorFlow/Keras` `Bi-LSTM` `GloVe` `Attention`

---

### Classical ML and Explainability

**[Fraud Detection with Ensemble Learning](https://github.com/nuthalapatideepika/fraud-detection-ensemble)**  
Stacked XGBoost, LightGBM, and Random Forest with a logistic regression meta-learner on a severely imbalanced fraud dataset. SMOTE and class weighting both applied. Primary metric is PR-AUC, not accuracy — because accuracy is misleading when fraud is 0.1% of records.  
`XGBoost` `LightGBM` `Scikit-learn` `SMOTE`

---

**[Churn Prediction with Explainable AI](https://github.com/nuthalapatideepika/churn-prediction-xai)**  
Gradient boosting churn model with SHAP for both global feature importance and per-customer local explanations. The point was not just a prediction but an answer to "why is this customer flagged" — the kind of output a business team can actually act on.  
`Scikit-learn` `XGBoost` `SHAP`

---

**[Advanced Clustering for Segmentation](https://github.com/nuthalapatideepika/clustering-segmentation)**  
K-Means, DBSCAN, and Gaussian Mixture Models compared on the same dataset after PCA dimensionality reduction. Evaluated on silhouette score with qualitative analysis of what each segment represents. Three algorithms on one dataset reveals what each one is actually good at.  
`Scikit-learn` `PCA` `K-Means` `DBSCAN` `GMM`

---

**[Hybrid Recommendation System](https://github.com/nuthalapatideepika/hybrid-recommender)**  
Collaborative filtering combined with TF-IDF content-based filtering in a weighted hybrid. Built specifically to address cold-start problems that pure collaborative filtering cannot handle. Evaluated on RMSE and precision@k.  
`Scikit-learn` `Surprise` `TF-IDF`

---

### Sequence Modeling and Generative Models

**[LSTM Time Series Forecasting](https://github.com/nuthalapatideepika/lstm-time-series)**  
Seq2Seq LSTM encoder-decoder for multi-step forecasting using sliding window sequences. Trained on MSE, evaluated on MAE and RMSE. The encoder-decoder structure handles variable forecast horizons cleanly.  
`TensorFlow/Keras` `LSTM` `NumPy` `Pandas`

---

**[GAN for Image Generation](https://github.com/nuthalapatideepika/gan-image-generation)**  
Generator and discriminator trained adversarially with batch normalization and LeakyReLU for stability. Image quality is tracked by saving generated grids at every epoch — so training collapse is visible immediately.  
`PyTorch` `GAN` `Batch Normalization`

---

**[Autoencoder Anomaly Detection](https://github.com/nuthalapatideepika/autoencoder-anomaly-detection)**  
Autoencoder trained only on normal samples. Anomalies are flagged when reconstruction error exceeds a threshold calibrated on a held-out validation set. No labels needed at inference — works on genuinely unseen anomaly types.  
`TensorFlow/Keras` `Autoencoder` `NumPy`

---

**[Reinforcement Learning Agent (DQN)](https://github.com/nuthalapatideepika/rl-dqn-agent)**  
Deep Q-Network in OpenAI Gym with experience replay and a separate target network. Both are necessary for stable training — without them, Q-value estimates diverge. Agent reward is tracked across episodes to measure convergence.  
`PyTorch` `OpenAI Gym` `DQN`

---

### MLOps, Deployment, and Data Engineering

**[End-to-End MLOps Pipeline](https://github.com/nuthalapatideepika/mlops-pipeline)**  
Complete ML lifecycle in one system: MLflow for tracking, Docker for reproducible builds, GitHub Actions for CI/CD, and monitoring for drift. Any team member can reproduce any run. Designed the way a real ML platform team would build it.  
`MLflow` `Docker` `GitHub Actions`

---

**[FastAPI Model Deployment](https://github.com/nuthalapatideepika/fastapi-model-deployment)**  
Trained model served via FastAPI with input validation, structured logging, and a health check endpoint. The entire service — model, dependencies, API — is inside a Docker image so deployment is one command.  
`FastAPI` `Docker` `Python`

---

**[MLflow Experiment Tracking System](https://github.com/nuthalapatideepika/mlflow-experiment-tracking)**  
MLflow tracking server with parameter/metric/artifact logging across runs. Best models registered in the Model Registry with version tags. Run comparison through the MLflow UI — the difference between scientific ML work and ad-hoc notebooks.  
`MLflow` `Scikit-learn`

---

**[Feature Store Regression Pipeline](https://github.com/nuthalapatideepika/feature-store-pipeline)**  
Feast-backed regression pipeline with features defined, versioned, and registered centrally. Offline store for training, online store for inference. Eliminates train-serve skew — the silent failure mode that breaks production ML more than any model bug.  
`Feast` `Scikit-learn` `Pandas`

---

**[Automated ETL Data Pipeline](https://github.com/nuthalapatideepika/etl-data-pipeline)**  
Modular ETL with schema validation at ingestion, a cleaning stage, a transformation stage, and structured output. Each stage is independently testable. Built because ML systems fail on data problems far more often than model problems.  
`Python` `Pandas` `NumPy`

---

**[Real-Time Inference Optimization](https://github.com/nuthalapatideepika/inference-optimization)**  
PyTorch model exported to ONNX, then quantized with both dynamic and static quantization. Latency benchmarked before and after. Built because model accuracy is only half the deployment story — the other half is whether it can serve requests fast enough.  
`ONNX Runtime` `PyTorch`

---

## GitHub Activity

<div align="center">

![GitHub Stats](https://github-readme-stats.vercel.app/api?username=nuthalapatideepika&show_icons=true&hide_border=true&count_private=true&theme=default)
&nbsp;&nbsp;
![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=nuthalapatideepika&layout=compact&hide_border=true&theme=default)

</div>

---

## Contact

**Email:** deepika.nuthalapati@usd.edu  
**LinkedIn:** [linkedin.com/in/deepika-nuthalapati](https://linkedin.com/in/deepika-nuthalapati)  
**University:** [usd.edu — Deepika Nuthalapati](https://www.usd.edu/research-and-faculty/faculty-and-staff/deepika-nuthalapati)  
**Location:** Vermillion, SD — open to remote and relocation

Actively seeking full-time ML engineering roles.
