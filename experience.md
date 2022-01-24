---
layout: page
title: Experience
permalink: experience
---

                                                             
## Product Management

- Developed an ML based product from idea stage to production deployment across 2 cloud platforms. This included internal pitches for funding at KPMG with the seed investment from the firm £250k with further investment in progress.

- Problem Statement: It is time consuming and difficult to properly classify a company's trading activity. The trading activity exposes the bank to a level of risk and drives the majority of the due dilligence requirements. Additionally, this activity could change at any point in time without informing the bank.

- The product is a Machine Learning based alternative to understanding customer trading activities using online digital traces and extrapolating the risk they provide to a Bank. Uses Natural Language Processing to emulate analyst lead investigations.

- The product is made available as a subscription based API that banks can integrate into different product where understanding a customers industry and risks are essential (client onboarding, due dilligence, periodic customer review etc.)

- ‍💻  Tech Stack: 
  - ☁️  AWS Services: API Gateway, Lambda, Step Functions, ECS
  - 📦  Packages: Transformers, SpaCy, Sentence Transformers, Magnitude

- 🖌️  Design Tools
  - Figma


## ML Project Management & Delivery

- Delivered the project end-to-end from PoC to Production delivery with 90+ BAU analysts using the system
- The Intelligent Document Processing system sources documents from 3 legacy document stores through API integrations and runs all the documents through the document understanding pipeline. 
- The pipeline consists of a page-stream segmentation model (page splitter) and a document classification model. Both use text based features using gradient boosted trees for latency purposes. Further work is being done using dual context (image+text) deep learning models (e.g. LayoutLM) for the next release.
- Lead a team of 10 on a large scale Financial Crime project at a Tier 1 Bank – overseeing 4 Data Scientists, 4 Data Engineers and 2 BAs. 
- The delivery was required to be on-premise on the client's infrastructure (custom Kubernetes cluster, standalone non-gpu enabled server for model training, Oracle DB back-end, S3-like blob storage)
- The team deployed 2 ML models and 16 Heuristic Models to production, passing the models and ecosystem through the internal Model Risk Process. 

- 💻   Tech Stack: 
  - 🏗️  Infrastructure: Pivotal Container Services, Linux RHEL
  - 📦   Packages: Instabase, XGBoost, OpenCV, Microsoft OCR

## Machine Learning

#### Client Deliveries

- Developed an NLP Model (BERT-Based) fine-tuned on Customer Due Dilligence (CDD) domain language to extract key information from unstructured text via both NER and Question Answering tasks.

- Built Machine learning models for a large UK bank, focusing on streamlining the complaints process. Developed an NLP classifier to judge which complaints could be accelerated through the process. Built an anomaly detection algorithm to warn of sudden spikes in volumes and link back the spike to a root cause.

#### Personal Projects

**Text Based ML**
- Predicting Brexit using Twitter as a high frequency polling mechanism. Built a fine-tuned DistilBert model to predict whether a spefic tweet was for brexit (anti-EU), against brexit (pro-EU) or neutral. [🔗 Presentation](https://www.bigsurv20.org/conf20/uploads/16/69/Twitter_BigSurv_4_.pdf)

**Image Based ML**
- Using YOLO for CCTV monitoring of accessibility assets (i.e. lifts and escalators) in train stations. The pipeline counts the number of passengers using each asset over the course of the day to optimise the maintenance cycles used by Network Rail. 🔗 Write-up in Progress

**Generative ML**
- Generative Radio is a submission for Kontinuum 2022, which combines the changing seasons throughout the year with a well known composition by Vivaldi (Four Seasons) to generate a unique and ever evolving composition which will play for 365 days in a row if selected by the panel. The musical generation is supplemented with artificially generated narration, which is programmatically triggered to play every hour, similar to a radio presenter. 🔗 Write-up in Progress

- Persigan is a fine-tune Image based GAN model to generate new Persian Carpet designs 🔗 Write-up in Progress

**Reinforcement Learning**
- Cryptocurrency trading using the TensorTrade RL framework to trade cryptocurrencies. 🔗 Write-up in Progress

## Data Engineering

- Designed then lead a team of 8 to build a customer data monitoring system for a Tier 1 Bank's high risk customers. Built in Python with 3rd party API integrations, reporting built in Pug.js

- Designed then lead a team of 7 to build a configuration based migration tool to transform data from legacy systems (relational) into a single customer view as a JSON. Developed a full customer decision tree which identified any missing data that is required as per policy tailored to every customer's circumstance.

## MI & Visualisations

- Lead the development and deployment of an MI solution for a Tier 1 bank. Managing 3 developers, 2 BAs and delivering tailored dashboards to different stakeholder groups (600+ End users).

## Academia

- BigSurv 2020 (Presenter) - Converting the Twitter API into a high quality panel via machine learning


## Hackathons

- InfraHack 2019 (1st Place)- Lift & Escalator Optimisation and Real-time Data Feeds using CCTV

- HackTrain VI (Finalist, Winner SilverRail Challenge) –Production grade chatbot in DialogueFlow
