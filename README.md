# Challenge US 2023 - SpazioDati
Offical project page: [Challenge US](http://www.sobigdata.eu/challenge-us-2023)

## Description
The Challenge US with SpazioDati involved the exploration of large language models to automatically extract names and job positions from "contacts" web pages, usually found in company websites. 

The process started with several different approaches, comprising of brute force approaches (eg. creating a dictionary of roles), model pipelines (eg. NER + QA) and the most prominent LLMs available (eg. GPT3.5 and GPT4).
After the first iterations, it was clear that the latter approaches were significantly superior in quality and quantity of results, both with respect to SpazioDati's approach and the other proposed ones. 
For this reason, the Python notebook and the presentation at hand solely cover the usage and the analysis of the results extracted using GPT models.

The final results show that GPT4 manages to extract twice the amount of people and three times the amount of roles with respect to SpazioDati, with a minimum amount of errors or hallucination involved.