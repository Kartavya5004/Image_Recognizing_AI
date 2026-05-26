# Image_Recognizing_AI
A deep learning image classification project using MobileNetV2 with transfer learning. The model is fine-tuned for better accuracy, optimized for performance, and evaluated using standard metrics. Includes code for training, testing, and easy deployment.

Day 1: Introduction to AI and Image Recognition
* Overview of AI systems that can "see".
* Understanding computer vision basics.
* Environment setup and dependencies.
* Loading and preprocessing image datasets.
  
Day 2: Building a CNN from Scratch
* Introduction to Convolutional Neural Networks (CNNs).
* Layers explained: Convolution, Pooling, Flattening, Dense.
* Model compilation using optimizers and loss functions.
* Training the CNN on a small dataset.
* Evaluating performance with accuracy and loss metrics.
  
Day 3: Model Improvement
* Increasing dataset diversity using Data Augmentation.
* Fine-tuning hyperparameters:
  * Learning rate
  * Batch size
  * Epoch count
* Identifying overfitting and applying regularization (Dropout, L2).
* Testing with validation data.
  
Day 4: Transfer Learning & Fine-Tuning
* Pre-trained Models explained:
  * Examples: MobileNetV2, ResNet, VGG, ImageNet.
  * Benefits of using large, pre-trained datasets.
* Transfer Learning:
  * Using pre-trained weights for new, similar tasks.
  * Freezing and unfreezing layers.
* Fine-Tuning Process:
  * Unfreeze selective layers.
  * Retrain with small learning rate to preserve knowledge.
* Model Optimization for better accuracy.
* Preparing for deployment.

Day 5: Model Deployment
* Exporting trained models (.h5 format).
* Deployment methods:
  * Web: Flask, Django, Streamlit (recommended for beginners).
  * Mobile: TensorFlow Lite, CoreML.
  * Cloud: AWS, Google Cloud, Azure.
  * API Hosting: Serving predictions via REST API.
* Evaluation Metrics:
  * ROC Curve & AUC Score for binary classification (Cat vs Dog).
  * Interpreting False Positive Rate (FPR) & True Positive Rate (TPR).

# Workflow:
1. Load and preprocess the Kaggle Cats vs Dogs dataset.
2. Use MobileNetV2 as a frozen feature extractor.
3. Add custom classification layers for binary output.
4. Fine-tune with low learning rate.
5. Evaluate using ROC & AUC.
