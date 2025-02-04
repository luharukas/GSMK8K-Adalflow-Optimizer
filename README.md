# GSMK8K-Adalflow-Optimizer

# GSM8K Math Problem Solver with AdalFlow

## Overview
This project implements a sophisticated math problem solver using the GSM8K (Grade School Math 8K) dataset with AdalFlow framework and Google's Gemini models. The system demonstrates remarkable accuracy in solving complex mathematical word problems through step-by-step reasoning.

## Features
- Utilizes Google's Gemini 1.5 models (Flash-002 and Pro)
- Implements both standard inference and text gradient optimization
- Supports batch processing and parallel execution
- Includes comprehensive evaluation metrics
- Built with AdalFlow framework for efficient model optimization

## Performance Metrics

### Base Model Performance (Without Optimization)
- Training Accuracy: 91%
- Testing Accuracy: 89%
- Validation Accuracy: 90%

### Optimized Performance (With Text Gradient)
- Training Accuracy: 96%
- Testing Accuracy: 93%
- Validation Accuracy: 95%

## Architecture
The system consists of several key components:
- **GSM8K Task Pipeline**: Handles the core problem-solving logic
- **Backward Training Engine**: Implements text gradient optimization
- **Custom Data Processing**: Specialized dataset handling for GSM8K format
- **Evaluation System**: Precise answer matching and accuracy computation
