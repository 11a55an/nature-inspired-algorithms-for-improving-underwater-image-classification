# Nature Inspired Algorithms for Improving Underwater Image Classification

This repository contains the implementation of nature-inspired algorithms to improve the results of underwater image classification. Specifically, we have utilized Genetic Algorithm (GA), Particle Swarm Optimization (PSO), and Ant Colony Optimization (ACO) to enhance the performance of image classification models.

## Table of Contents
- [Introduction](#introduction)
- [Methodology](#methodology)
  - [Feature Extraction](#feature-extraction)
  - [Nature Inspired Algorithms](#nature-inspired-algorithms)
  - [Classification](#classification)
- [Results](#results)

## Introduction
Underwater image classification is a challenging task due to the unique conditions such as light absorption, scattering, and color distortion. To address these challenges, we employ nature-inspired algorithms to optimize feature selection and improve classification performance. This repository demonstrates the use of GA, PSO, and ACO for feature selection on features extracted from three different models: ResNet, MobileNet, and Inception.

## Methodology

### Feature Extraction
We extract features from underwater images using the following pre-trained deep learning models:
- ResNet
- MobileNet
- Inception

### Nature Inspired Algorithms
We apply the following nature-inspired algorithms to optimize feature selection for each set of extracted features:
- **Genetic Algorithm (GA)**
- **Particle Swarm Optimization (PSO)**
- **Ant Colony Optimization (ACO)**

### Classification
The selected features from each algorithm are used to train a Support Vector Classifier (SVC) to evaluate the classification performance.

## Results
The table below summarizes the classification accuracy achieved using different feature extraction models and nature-inspired algorithms:

| Model      | Base   | ACO    | PSO    | GA     |
|------------|--------|--------|--------|--------|
| MobileNet  | 97.55% | 97.81% | 98.43% | 99.11% |
| ResNet     | 97.29% | 97.44% | 97.39% | 97.34% |
| Inception  | 96.40% | 96.77% | 96.77% | 96.87% |

