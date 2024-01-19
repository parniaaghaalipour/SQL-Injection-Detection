# SQL Injection Detection Using BERT

This repository contains the code for a machine learning-based SQL injection detection system that leverages the power of BERT (Bidirectional Encoder Representations from Transformers) and text classification techniques to identify and classify SQL injection attacks.

## Overview

SQL injection is a prevalent security vulnerability that can affect data-driven applications. This project aims to use advanced natural language processing techniques to detect malicious SQL queries that may pose a threat to database security.

## Features

- **Dataset Processing**: Includes functionality for preprocessing and preparing SQL query data for model training.
- **BERT Integration**: Utilizes the BERT-base-uncased model for feature extraction from textual data.
- **Model Architecture**: Features a Convolutional Neural Network (CNN) based classifier built on top of BERT embeddings to identify potential SQL injections.
- **Training and Evaluation**: Comprehensive training and evaluation pipeline with performance metrics like accuracy, precision, recall, and F1-score.
