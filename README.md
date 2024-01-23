# An Evaluation of Machine Translation Models 

## Overview
This repo contains the evaluation and analysis of various machine translation models, specifically tailored for healthcare. The objective is to facilitate accurate and efficient translation of medical dialogue from languages (such as Telugu, Arabic, Swahili, etc.) to English and vice versa. The focus is on ensuring the highest possible accuracy and contextual relevance, given the critical nature of medical communications.

## Model Evaluation
A comprehensive evaluation framework was implemented to assess the performance of multiple machine translation models. The criteria includes accuracy, context preservation, medical terminology handling, and speed of translation. These factors are crucial in medical settings where precise and timely communication can significantly impact patient care.

### Languages Covered (so far)
- **Focus**: Special focus on regional medical terms, attention to dialectal variations and their impact on translation accuracy, Evaluation includes common phrases and terms used in medical dialogue, and contextual medical dialogue.
- **Languages**: Telugu, Hindi, Swahili, Arabic

### Key Metrics
- **Translation Accuracy**: Measured against a curated dataset of medical dialogue.
- **Context Preservation**: Maintaining the original message's context and nuances.
- **Terminology Handling**: Effectiveness in translating specialized medical terms.
- **Speed**: Translation turnaround time, crucial for real-time medical communication.
- **Cost of Deployment**: Make the cost of deployment cost-effective and  ease of the implementation. 

## Evaluation
The dataset used for the evaluation is the .csv file in the repo.

### Accuracy of translation using Bleu 
| Model Name             | Telugu -> English | Hindi -> English | Swahili -> English | Arabic -> English | Average        |
|------------------------|-------------------|------------------|--------------------|-------------------|----------------|
| GPT-3.5                | 16.7              | 16.9             | 15.6               | 19.3              | 17.125         |
| Helsinki-NLP/opus-mt-mul-en | 19.92             | 22.1             | 17.8               | 24.5              | 21.08          |
| Seamless M4T-v2 Model  | 98.11             | 99.4             | 45.81              | 78.56             | 80.47          |


## Contribution
Help enhance the effectiveness of medical translations in uhealAI! We welcome:
- Feedback on model performance.
- Suggestions for model improvement.
- Contributions to datasets, specifically in underrepresented languages.


## Contact
For more information or to contribute to this project, please contact august@uheal.ai.

---

Uheal project is part of an ongoing effort to leverage technology in bridging language barriers in healthcare. We aim to make healthcare more accessible and effective for diverse populations worldwide.
