# PRODIGY_GA_01

## Task 01 - Generative AI Internship @ Prodigy InfoTech

## Medical Evidence Brief Generator using  Fine-Tuned GPT-2

## Overview

This project fine-tunes GPT-2 on a custom healthcare dataset to generate structured clinical evidence briefs from short medical prompts. The model was trained on curated examples covering diabetes, cardiovascular disease, heart failure, GLP-1 receptor agonists, SGLT2 inhibitors, and related therapeutic areas.

The generated output follows a standardized format containing:

- Overview
- Key Evidence
- Clinical Relevance
- Safety Notes
- Key Takeaway

This enables rapid generation of concise evidence summaries for healthcare professionals, medical writers, and health-tech applications.

## Project Objective

Develop a domain-specific text generation model capable of producing coherent and contextually relevant clinical evidence briefs from a single short prompt.

## Features

- GPT-2 fine-tuning on a custom healthcare dataset
- Structured clinical evidence brief generation
- Medical prompt-to-summary workflow
- Standardized output format
- Implemented in Google Colab
  
## Dataset

Custom healthcare training dataset containing:

- 74 structured prompt-output examples
- 61,916 characters
- 7,645 words

## Topics Included

- Semaglutide
- Empagliflozin
- SGLT2 Inhibitors
- Heart Failure
- Tirzepatide
- Cardiovascular Diseases
- Type 2 Diabetes
- GLP-1 Receptor Agonists

## Technologies Used

- Python
- Hugging Face Transformers
- PyTorch
- Datasets Library
- Google Colab

## Training Details

- Base Model: GPT-2
- Fine-tuning Framework: Hugging Face Transformers
- Training Steps: 640
- Final Training Loss: ~0.40

  ## Project Workflow

1. Collected and curated medical evidence examples.
2. Created structured prompt-output training pairs.
3. Loaded GPT-2 tokenizer and pre-trained model.
4. Tokenized and prepared the dataset.
5. Fine-tuned GPT-2 on healthcare-specific data.
6. Generated evidence briefs from custom prompts.
7. Evaluated generated outputs.

   ## Results

- Successfully fine-tuned GPT-2 on a custom healthcare dataset.
- Final training loss reached approximately 0.40.
- Generated structured clinical evidence briefs from short medical prompts.
  
## Sample Prompt

Semaglutide obesity outcomes

## Sample Generated Output

OVERVIEW:
Early recognition and management of obesity-related comorbidities remain critical components of modern obesity management.

KEY EVIDENCE:
Systematic review evidence suggests that obesity-related comorbidities contribute significantly to morbidity and mortality in semaglutide users.

CLINICAL RELEVANCE:
Understanding comorbid obesity symptoms may reduce patient initiation and progression to symptomatic obesity.

SAFETY NOTES:
Although evidence suggests improvements in glycemic control, clinicians should monitor comorbid comorbid conditions for potential interactions.

KEY TAKEAWAY:
Emerging evidence highlights the important role of obesity comorbidity in managing obesity-related comorbidities.

## Repository Structure

PRODIGY_GA_01
│
├── screenshots/
│   ├── task1_dataset_stats.png
│   ├── task1_training_progress.png
│   ├── task1_training_complete.png
│   └── task1_generated_output.png
│
├── .gitignore
├── LICENSE
├── medical_evidence_dataset.txt
├── PRODIGY_GA_01_GPT2_Text_Generation.ipynb
├── requirements.txt
└── README.md

## Screenshots

### Dataset Statistics
![Dataset Statistics](screenshots/task1_dataset_stats.png)

### Training Progress
![Training Progress](screenshots/task1_training_progress.png)

### Training Completion
![Training Completion](screenshots/task1_training_complete.png)

### Generated Output
![Generated Output](screenshots/task1_generated_output.png)
