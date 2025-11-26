# Mental Health Crisis Detection from Social Media Text

A sentence-level analysis pipeline for detecting and quantifying emotional distress in social media posts using transformer-based sentiment analysis and psychological principles.

## Project Overview

This project develops a fine-grained, sentence-level approach to mental health crisis detection by:
- Analyzing emotional severity at the sentence level rather than document level
- Combining sentiment polarity (valence) and emotional intensity (arousal)
- Generating a continuous severity score (0-1) for psychological distress
- Implementing risk classification (Low, Moderate, High, Critical)
- Deploying a functional chatbot prototype for real-time intervention

## Key Features

- **Sentence-Level Analysis**: Captures emotional fluctuations within individual posts
- **Psychological Grounding**: Based on the Circumplex Model of Affect using ANEW norms
- **Transformer-Based Sentiment**: Utilizes RoBERTa for accurate emotion detection
- **Risk Classification**: Automated triage into four risk categories
- **Temporal Analysis**: Identifies peak crisis hours (1 AM)
- **Chatbot Integration**: Proof-of-concept for real-world deployment

## Installation

### Prerequisites
- pip install praw==7.8.1
- pip install pandas==2.2.3
- pip install numpy==2.1.3
- pip install matplotlib==3.10.0
- pip install seaborn==0.13.2
- pip install torch==2.8.0+cpu
- pip install transformers==4.49.0
- pip install scikit-learn==1.6.1
- pip install emoji==2.14.1
- pip install nltk==3.9.1
- pip install tqdm==4.66.5
- pip install wordcloud==1.9.3
- pip install translatepy==2.3
- pip install contractions==0.1.73

### Setup
 **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/mental-health-crisis-detection.git
   cd mental-health-crisis-detection
