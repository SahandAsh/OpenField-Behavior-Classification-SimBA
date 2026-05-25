# OpenField-Behavior-Classification-SimBA
Behavioral classification pipeline for rodent open-field assays using pose-estimation outputs and supervised machine learning in SimBA.

## Overview

This project demonstrates a behavioral analysis workflow for rodent open-field experiments using SimBA (Simple Behavioral Analysis).

Starting from pose-estimation outputs, the pipeline classifies multiple behaviors and visualizes behavioral dynamics over time.

Classified behaviors include:

- Locomotion
- Freezing / Immobility
- Wall-following (Thigmotaxis)

The project was developed as a self-training exercise in computational behavioral neuroscience and machine-learning-assisted behavioral quantification.

## Behavioral Classification Workflow

Real-time behavioral classification.
x

## Why Behavioral Classification Matters

Behavioral neuroscience traditionally relies on manual scoring of behaviors by experimenters, which can be labor-intensive, subjective, and difficult to scale.
Pose-estimation and behavioral classification frameworks enable reproducible, frame-level quantification of behavior.

Examples include:

- locomotor activity analysis
- freezing behavior in fear/anxiety paradigms
- thigmotaxis as an index of exploratory strategy and anxiety-like behavior
- automated behavioral phenotyping

These approaches are increasingly used in systems, social, and translational neuroscience.



## Repository Structure

OpenField-Behavior-Classification-SimBA/
│
├── README.md
├── requirements.txt
│
├── figures/
│   ├── Classifier.gif
│   ├── Heatmap.png
│   ├── behavior_distribution.png
│   ├── locomotion_prediction.png
│   ├── freezing_prediction.png
│   └── thigmotaxis_prediction.png
│
├── sample_data/
│   └── Validation_cvs.csv
