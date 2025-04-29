# [Medical chat bot](https://github.com/hainguyen1511/Google-Colab/blob/main/Medical%20Bot.ipynb)
Inspired by [Computer Science (compsci112358) on youtube](https://www.youtube.com/watch?v=9KZwRBg4-P0)
> [!NOTE]
> 1. Define the Scope & Goals
Target users: Patients, doctors, healthcare providers?
Core functions: Symptom checking, appointment scheduling, basic medical advice?
Limitations: Legal compliance (HIPAA, GDPR), no direct diagnosis?

> [!NOTE]
> 2. Choose the Tech Stack
Programming Language: Python
Libraries & Tools: numpy, pandas, sklearn
NLP: NLTK, or 
Machine Learning: newspaper3k, 

> [!NOTE]
> 3. Design the Conversation Flow
Greeting & user identification
Collect symptoms & health concerns
Provide responses (triage advice, health information)

> [!NOTE]
> 4. Implement Natural Language Processing (NLP)
Preprocess text (tokenization, stemming, stopword removal)
Train an intent classifier (understand user queries)

> [!TIP]
> How do I train this bot, were does it get health information from?
I will provide this bot a medical article from sources like mayoclinic.org

> [!IMPORTANT]
> using the newspaper3k library to fetch and process an article from the Mayo Clinic website.
Download the webpage content.
Parse it to extract text.
Apply NLTK techniques for keyword extraction.
Store the full article text in corpus1.
A couple of things to consider:
Respecting Copyright: Be cautious when storing and using extracted text, as websites like Mayo Clinic may have restrictions on content usage.
Error Handling: If the website changes its structure or blocks requests, you might need exception handling to prevent failures.
Alternative APIs: Some medical sites offer official APIs for accessing article summaries legally.

> [!CAUTION]
> nltk will tokenize article to keywords
