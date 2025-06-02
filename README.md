# SEMANTIC BOOK RECOMMENDER

*Discover your next favorite book with AI-powered semantic recommendations.*

[![Python](https://img.shields.io/badge/python-3.12%2B-blue.svg)](https://python.org)
[![AI Powered](https://img.shields.io/badge/AI-powered-brightgreen.svg)](#)
[![Status](https://img.shields.io/badge/status-active-success.svg)](#)

## 🛠️ Built with

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Gradio](https://img.shields.io/badge/Gradio-FF6B35?style=for-the-badge&logo=gradio&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)
![Scikit Learn](https://img.shields.io/badge/Scikit_Learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)

---

## 📋 Table of Contents

- [Overview](#overview)
- [System Architecture](#system-architecture)
- [Key Features](#key-features)
- [Components](#components)
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
  - [Data Setup](#data-setup)
  - [Usage](#usage)

---

## Overview

This project is a semantic book recommender system that leverages large language models (LLMs) to provide intelligent book recommendations based on user queries. The system combines advanced NLP techniques including semantic search, text classification, and sentiment analysis to deliver personalized reading suggestions.

![System Architecture](https://github.com/user-attachments/assets/85a883ae-4a64-4e08-b04c-3febc9df4c75)

---

## System Architecture

The recommender system is built on a multi-component architecture that processes user queries through several AI-powered stages to deliver contextually relevant book recommendations.

---

## Key Features

### 🔍 **Semantic Search**
Advanced vector-based similarity matching to find books that align with user preferences and context.

### 🤖 **LLM Integration**
Utilizes large language models for natural language understanding and intelligent recommendation generation.

### 📚 **Text Classification**
Automatically categorizes books as "fiction" or "non-fiction" using zero-shot classification techniques.

### 💭 **Sentiment Analysis**
Analyzes emotional tone and sentiment to match books with user mood and preferences.

### 🌐 **Interactive Web Interface**
User-friendly Gradio dashboard for seamless book discovery and recommendations.

### 📊 **Data Processing Pipeline**
Comprehensive data cleaning and preparation workflow for optimal recommendation accuracy.

---

## Components

The system consists of five main components, each handling specific aspects of the recommendation process:

### 1. **📈 Data Exploration** 
Comprehensive data cleaning and text preprocessing pipeline.
- **File:** `data-exploration.ipynb`
- **Purpose:** Prepares and cleans book metadata for analysis

### 2. **🔎 Semantic Search Engine**
Vector database construction for similarity-based book matching.
- **File:** `vector-search.ipynb`
- **Purpose:** Builds and optimizes vector representations for semantic search

### 3. **🏷️ Text Classification Module**
Genre classification system using advanced NLP techniques.
- **File:** `text-classification.ipynb`
- **Purpose:** Automatically categorizes books by genre using zero-shot classification

### 4. **😊 Sentiment Analysis Engine**
Emotional tone extraction for mood-based recommendations.
- **File:** `sentiment-analysis.ipynb`
- **Purpose:** Analyzes and categorizes books by emotional tone and sentiment

### 5. **🖥️ Web Application Interface**
Interactive dashboard for user interaction and recommendation display.
- **File:** `gradio-dashboard.py`
- **Purpose:** Provides user-friendly interface for book recommendations

---

## Getting Started

### Prerequisites

- **Python Version:** 3.12 or higher
- **Package Manager:** pip
- **Data Source:** Kaggle dataset (instructions provided in project files)

### Installation

1. **Clone the repository:**
   ```bash
   git clone <repository-url>
   cd semantic-book-recommender
   ```

2. **Install dependencies:**
   ```bash
   pip install -r requirements.txt
   ```

### Data Setup

Download the necessary dataset from Kaggle as instructed in the project files. Ensure the data is placed in the appropriate directory structure for the notebooks to function correctly.

### Usage

**Launch the web application:**
```bash
python gradio-dashboard.py
```

The Gradio interface will start locally, providing an interactive dashboard where users can:
- Enter book preferences or queries
- Receive personalized recommendations
- Explore book details and metadata
- Filter results by genre, sentiment, or other criteria

---

## 🚀 Features Overview

- 🧠 **AI-Powered Recommendations** - Leverages LLMs for intelligent suggestions
- 📖 **Multi-Genre Support** - Handles both fiction and non-fiction categories  
- 🎯 **Contextual Understanding** - Processes natural language queries effectively
- 📊 **Sentiment-Based Filtering** - Matches books to user emotional preferences
- ⚡ **Real-Time Processing** - Instant recommendations through optimized algorithms
- 🎨 **Interactive Interface** - Clean, intuitive Gradio-based web application

---

**[↑ Return to top](#semantic-book-recommender)**
