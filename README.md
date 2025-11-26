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

## Setup
 **Clone the repository**
   ```bash
   git clone https://github.com/Rawbeenprajapati/Early-Detection-of-Mental-Health-Symptoms-via-Social-Media-Text-Analysis.git
```

## Model Performance
The sentiment analysis pipeline achieves:
- Overall Accuracy: 86%
- Negative Sentiment F1-Score: 0.90
- Precision (Crisis Detection): 0.87
- Recall (Crisis Detection): 0.89

## Key Results
- 5:1 reduction in false positives compared to document-level analysis
- 1 AM is identified as the peak hour for mental health crises
- Clear separation between Low/Moderate/High/Critical risk levels

## Note:
- Due to file size, I could not upload the whole file, so here is the link to all file: https://drive.google.com/file/d/1Hpl2mTLASaKmwHrZ0H71bLrhbBgOtfDG/view?usp=sharing

