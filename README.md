Deep Learning in Medical Imaging: An Integrated Approach to X-ray Diagnostics

Overview

This repository hosts the implementation of a deep learning project aimed at enhancing X-ray diagnostics for respiratory diseases such as COVID-19, Tuberculosis, and Pneumonia. By integrating advanced architectures such as Convolutional Neural Networks (CNNs), Multi-Layer Perceptrons (MLPs), and ResNet50, the project strives to provide rapid, accurate, and scalable diagnostic solutions.

Features
	•	Integrated Model Architecture: Combines CNN, MLP, and ResNet50 for a comprehensive and nuanced analysis.
	•	Data Quality Assurance: Implements rigorous preprocessing and segmentation for consistent and high-quality inputs.
	•	High Accuracy: Achieves up to 99% diagnostic accuracy on selected datasets.
	•	Scalability: Designed to adapt to new respiratory diseases and other medical imaging modalities.

Objectives
	1.	Improve diagnostic precision and speed for X-ray image analysis.
	2.	Establish a robust preprocessing pipeline to standardize inputs.
	3.	Benchmark performance against existing solutions, targeting at least 98% accuracy.
	4.	Expand disease detection capabilities to include diverse respiratory conditions.

Methodology
	•	Data Collection & Preprocessing:
	•	Utilized publicly available X-ray datasets.
	•	Preprocessed images using the VGG16 model for feature extraction.
	•	Applied K-means clustering for image segmentation and feature grouping.
	•	Model Architecture:
	•	CNNs: For spatial pattern recognition.
	•	MLPs: For decision-making and classification.
	•	ResNet50: For deep feature extraction and handling complex patterns.
	•	Training & Evaluation:
	•	Data split into training, validation, and test sets.
	•	Iterative refinement to prevent overfitting and maximize accuracy.

Results
	•	CNN achieved 99% accuracy, showcasing excellent spatial hierarchy recognition.
	•	MLP reached 98% accuracy, excelling in decision-making tasks.
	•	ResNet50 demonstrated deep feature extraction capabilities with a 75% accuracy rate.
	•	Integrated model improved robustness and diagnostic precision.

Usage
	1.	Install dependencies:
Ensure all required libraries are installed. If a requirements.txt file is provided, run:

pip install -r requirements.txt


	2.	Prepare the dataset:
Place the dataset in the designated directory (e.g., data/) or update the dataset path in the script as needed.
	3.	Run the script:
Execute the Python file to perform preprocessing, training, and evaluation:

python script_name.py

Replace script_name.py with the name of the script.

	4.	View Results:
Results will be saved in the output directory or displayed in the terminal/logs.

Limitations
	•	Limited scope to respiratory diseases included in the training dataset.
	•	Dependency on open-source datasets, which may introduce biases.
	•	Requires high computational resources for training deep learning models.

Future Work
	•	Incorporate additional datasets to expand disease detection capabilities.
	•	Optimize ResNet50 performance to address current limitations.
	•	Explore new architectures such as EfficientNet and DenseNet for improved scalability.

Contributors
	•	Ganesh Cherukuri
MSc Data Science and Analytics
Brunel University, Department of Computer Science
ganeshganu944@gmail.com


