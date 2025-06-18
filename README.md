# Project Name
Building Effective Search Systems for Insurance policy documents


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

## General Information
### Project Background:
I will be building an effective search systems project related to the insurance industry. An AI-powered project to extract information from insurance policy documents can revolutionize how policies are analyzed and understood. Using natural language processing (NLP), this system can efficiently scan, interpret, and extract key details such as coverage limits, exclusions, claim procedures, and premium details from the policy document
### Project Goal:
To address this, I will develop search systems for insurance policy documents, a question-answering system that combines the power of Embedding models, RAG & Large language models to ensure accurate and reliable information delivery
### Problem Statement:
Given Principal-Sample-Life-Insurance-Policy document containing information about the Group Member Life Insurance (Eligibility, Terminations, Reinstatement, BENEFITS, Member Accidental Death and Dismemberment Insurance, Dependent Life Insurance, Claim Procedures, cuisine type, area etc.), I will build a chatbot that parses the document and provides accurate answers based on the user queries
### Approach:
1. Embedding Layer: The embedding layer generates embeddings for our text corpus and allows the RAG model to understand the meaning of the query and to generate a relevant and informative response. This is essential for a variety of tasks, such as question answering system like what we are developing
2. Search and Rank Layer: It ensures that the retrieved text is accurate, relevant and contextually appropriate. The search component will use a technique called semantic similarity. It is a measure of how similar two pieces of text are in terms of their meaning. The search component uses semantic similarity to retrieve documents from a knowledge base that are relevant to the user's query. The re-rank component of the search typically uses a variety of techniques to re-rank the retrieved documents
3. Generation Layer: The generation layer will allow the model to generate new text in response to a user's query. The generative model takes the retrieved information, synthesises all the data and shapes it into a coherent and contextually appropriate response
### Challenges faced: Segmentation of the document and creation of a coherent response

## Conclusions
Appropriate results are achieved by executing queries such as,
- What is the eligibility criteria of member life insurance?
- What are the procedures and time limits for filing a claim and receiving benefits under this life insurance policy?

## Technologies Used
- Python - version 3.10
- pandas - version 2.2.2
- OpenAI - version GPT 4.1
- text-embedding-ada-002 
- Chroma Vector DB

## Acknowledgements
- TensorFlow, Pandas, Medium, Stackoverflow, OpenAI, Cohere

## Contact
Created by [@sahilavasthi] - feel free to contact me!
