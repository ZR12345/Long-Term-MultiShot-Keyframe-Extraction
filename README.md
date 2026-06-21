LMSKE: Long-Term Multi-shot Keyframe Extraction
Overview

This project implements an automated video summarization pipeline that extracts representative keyframes from videos using scene detection and semantic feature analysis.

The framework combines:

Scene segmentation using PySceneDetect
CLIP-based visual feature extraction
K-Means clustering
Silhouette-score-based cluster selection
Similarity filtering for redundancy removal
Pipeline
Video Input
Scene Detection
Frame Sampling
CLIP Feature Extraction
Clustering
Keyframe Selection
Redundancy Filtering
Summary Generation
Technologies
Python
OpenCV
CLIP
PyTorch
Scikit-learn
PySceneDetect
Outputs
Extracted keyframes
Timestamp CSV
Keyframe visualization grid
Performance metrics
Future Work
Real-time video summarization
Multi-modal summarization
Video caption generation
Transformer-based shot understanding
