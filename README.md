# Qtech_chat_parsing
The task is to build an AI Chat Log Summarizer is a Python-based tool that reads .txt chat logs between 
a user and an AI, parses the conversation, and produces a simple summary
including message counts and frequently used keywords.

The thought process is also mmentioned in the Qtech.ipynb file. 

"""Thought Process"""

I have a text file that contains conversation between a user and an AI chatbot.

"""Task 1.: My task is to separate the messages by speaker and AI."""

    Step 1: load the text file that contains the conversation
    
    Step 2: read the conversation and store them in a variable called lines
    
    Step 3: Separate the User: and AI: part from the conversation and store the ID 
    of the speaker in a variable and the message in other variable using strip() function.

"""Task 2: Count total messages"""

"""Task 3: Keyword Analysis"""

    Step 1: import nltk for keyword extraction
    
    Step 2: use punkt_tab from nltk which will give us the split words from the texts
    
    Step 3: use stopwords set to identify the common set of words in english and exclude them
    
    step 4: get all the words excluding the common english words, use isalpha() for excluding punctuation mark
    
    step 5: use counter to count the frequency of a word

"""Task 4: Generate the summary"""
