# AI-Powered Healthcare Assistant

An end-to-end healthcare AI platform using transformer-based models for mental health detection, clinical diagnosis prediction, and intelligent patient query resolution.

---

## Project Overview

The AI-Powered Healthcare Assistant is a real-world, multi-module healthcare application designed to assist patients and clinicians through automated text understanding and predictive analytics. It integrates natural language processing and machine learning to:

- Detect mental health issues such as anxiety, stress, and depression.
- Predict potential clinical diagnoses from patient reports.
- Provide a chatbot-based interface for health-related query resolution and symptom triage.

This system is built with a focus on deploying intelligent, explainable AI for medical support.

---

## Features

1. **Mental Health Predictor**  
   - Detects signs of anxiety, depression, or stress from user input using a fine-tuned BERT classifier.
   - Input: Free-text sentences or patient feedback.
   - Output: Mental health category prediction.

2. **Clinical Diagnosis Prediction**  
   - Uses transformer models to predict diseases based on unstructured clinical notes or patient descriptions.
   - Trained on labeled medical text to identify likely conditions.

3. **Healthcare Customer Support Chatbot**  
   - Conversational assistant for answering health-related queries and guiding users based on symptoms.
   - Simulates real-time patient support with intelligent, domain-specific responses.

4. **Diagnostic Reasoning**  
   - Understands clinical and psychological patterns from textual data.
   - Learns from real-world healthcare language to deliver accurate insights.

---

## Tech Stack

| Component                  | Technology                                  |
|---------------------------|----------------------------------------------|
| Language Models           | BERT, DistilBERT, Hugging Face Transformers |
| ML & NLP Libraries        | scikit-learn, spaCy, NLTK, Transformers      |
| Application Framework     | Streamlit                                   |
| Programming Language      | Python                                       |
| Development Tools         | Jupyter Notebook, Git                        |

---

## Example Use Cases

- Input: "I'm feeling sad and don't want to talk to anyone."  
  Output: Depression

- Input: Medical report text mentioning "persistent cough and breathlessness."  
  Output: Asthma or COPD

- Query: "What should I do if I have a fever and body aches?"  
  Chatbot Response: "These could be flu-like symptoms. Please stay hydrated and consult a physician if it persists."

---



