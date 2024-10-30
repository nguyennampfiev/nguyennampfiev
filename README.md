# Hi there, I'm Nam 👋

I'm a PostDoc with a passion for ML, DL and Computer Vision. I enjoy working on ANR Chamdoc project. Check out some of my work below!

- 🔭 I’m currently working on ANR CHAMdoc project.
- 🌱 I’m currently learning NLP as well as LLMs, RAG.
- 👯 I’m looking to collaborate on NLP as well as Computer Vision problem.
- 💬 Ask me about Document Processing, OCR, Denoising, Generative Modeling, ASR, Action Recognition. 
- 📫 How to reach me: nguyennampfiev1995@gmail.com

## 🚀 Projects

### [ANR CHAMdoc]()
## Overview

The goal of this project is to develop a comprehensive, automated workflow for analyzing Cham documents, an ancient script with cultural and historical significance. The workflow consists of three primary stages: Image Enhancement, Text Line Segmentation, and Text Line Transliteration (OCR). Each stage is designed to address the unique challenges presented by Cham manuscripts, including their age, script complexity, and the varying quality of preserved documents.

**Duration**: Sep 2023 - Now
#### 1. Image Retrieval
- **Objective**: Retrieval all the similar stamps given input stamp.
- **Solution**:
  
  - Grounding DINO for segmentation.
  - Triplet loss with customize miner based on SwinTransformer.
  - I created a simple interface so user can easily to interact with system based on Streamlib and Docker.

**Duration**: Feb 2020 - Jul 2023
##### 2. Image Enhancement

- **Objective**: Improve the quality of scanned Cham document images.
- **Solution**:
  - I proposed Pix2Pix model with Multi scale Attention for further improve both quantitative and qualitative of documents.

##### 3. Text Line Segmentation

- **Objective**: Accurately segment text lines from enhanced images.
- **Solution**:
  - I proposed finetuning [docExtractor](https://github.com/monniert/docExtractor) for base line extraction.
  - I modified the typical Seam Carving algorithm by adding the additional cost fucntion for correcly adjust bounding box.
    
##### 4. Text Line Transliteration (OCR)

- **Objective**: Convert segmented Cham text lines into machine-readable text.
- **Solution**: Seq2Seq model with Transformer
  - I proposed two step sequence transformer by first using Seq2Seq model to translate text from Cham alphabet to Latin alphabet then using Transformer to adjust the results
##### Final Deliverable
This workflow automates the analysis of Cham documents (inscription and manuscript), enhancing images, segmenting text, and converting it into digital text. This process aids in the preservation and further study of Cham cultural heritage.
### [Invoice Information Extraction]()
**Duration**: 2020 - 2021

## Overview
This project focused on developing an automated system for extracting key information from invoices. The project involved creating a robust pre-processing algorithm to handle rotated invoice images and integrating a micro AI service into a complete information extraction pipeline.

## Key Activities

### 1. Pre-Processing Algorithm Development
- **Objective**: Correctly rotate invoice images to standardize orientation for accurate data extraction.
- **Tasks**:
  - Developed a pre-processing algorithm to detect and correct the orientation of scanned or photographed invoices.
  - Utilized image processing techniques to identify text and layout patterns that indicate the correct orientation.
  - Integrated the algorithm into the pipeline, ensuring that all invoices are properly aligned before further processing.

### 2. Micro AI Service Development
- **Objective**: Create a micro AI service to handle the extraction of key information from invoices.
- **Tasks**:
  - Designed and implemented a microservice using AI models capable of identifying and extracting relevant fields (e.g., invoice number, date, total amount) from invoices.
  - Integrated the micro AI service into the broader pipeline, ensuring seamless data flow and processing.

## Tools & Technologies
- **Image Processing**: Used for developing the rotation correction algorithm, focusing on text detection and orientation analysis.
- **AI/ML Models**: Implemented to recognize and extract key invoice fields, adaptable to different invoice templates and layouts.
- **Microservices Architecture**: Designed the AI service as a microservice to enable modular and scalable integration with the extraction pipeline.


### [ASR]()
# Automatic Speech Recognition (ASR) Project

## Project: Voice Trigger System for Russian, Spanish, and French

**Duration**: August 2018 - October 2019

## Overview
This project focused on developing a Voice Trigger System tailored for Russian, Spanish, and French languages. The system utilizes Automatic Speech Recognition (ASR) technologies to detect specific voice commands or "triggers." The primary tools used were HTK (Hidden Markov Model Toolkit) and Kaldi, both widely recognized in the speech recognition community.

## Key Activities

### 1. Speech Recognition Investigation
- **Objective**: Explore and evaluate ASR methodologies based on HTK and Kaldi tools.
- **Tasks**:
  - Conducted a the use of mixing tool between HTK and Kaldi for voice trigger systems.
  - Investigated acoustic and language modeling techniques to optimize recognition accuracy for each target language.

### 2. Voice Trigger Model Fine-Tuning
- **Objective**: Adapt and fine-tune the Voice Trigger models for Russian, Spanish, and French.
- **Tasks**:
  - Customized and trained models using language-specific datasets to enhance trigger detection accuracy.
  - Addressed language-specific challenges such as phonetic variability and acoustic differences.

## Tools & Technologies
- **HTK (Hidden Markov Model Toolkit)**: Used for initial ASR model training and evaluation.
- **Kaldi**: Employed for advanced modeling, including deep learning-based approaches for speech recognition.
- **Datasets**: Language-specific datasets for Russian, Spanish, and French to train and validate the models.

## Outcomes
- Successfully developed and fine-tuned Voice Trigger models for Russian, Spanish, and French languages.
- Achieved high accuracy in detecting voice triggers across different languages by leveraging the strengths of both HTK and Kaldi.
- The project laid the groundwork for further advancements in multilingual ASR systems, particularly in voice-activated applications.

## 🛠️ Technologies & Tools
-Tools                                       Git, Flask, Gradio, Streamlit, Docker, Kubernetes, Postman
-Computer Vision              Document Image Analysis, Image translation, OCR, Object Detection
                                                   Fine-grained  Image Retrieval, Segmentation, Human Action Recognition, 
                                                   GANs, VAEs.
- GenAI                                     Hugging Face, Langchain, Unstructured Io, Knowledge Graphs
- NLP                                         LLMs, PEFT, LORA, Text classification, RAG
- Languages                            Python, Matlab, Java Script, Bash Script, C++
- Frameworks/Libraries   Numpy, Scikit-learn, Pytorch, Tensorflow, Transformers, Pandas, OpenCV
- Cloud/DevOps                   Docker,  Kubernetes,  RESTful APIs,  Microservices Architecture, GCP


