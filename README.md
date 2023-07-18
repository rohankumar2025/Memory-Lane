# Memory Lane
Memory Lane is a simple Jupyter Notebook that summarizes your long iMessage conversations from years ago. You don't need to scroll and manually read through all of your long conversations to be able to reminisce and get the jist of what you and your friend(s) used to talk about.

# Content
The notebook goes through the process of:
1. Extracting and formatting your own personal iMessage data from the database stored on your own local machine using Python SQL3
2. Splitting your long conversation into smaller documents using Langchain
3. Embedding each document as a vector of numbers to feed into Large Language Models like ChatGPT
4. Using signal processing clustering techniques to decide which group of documents best represents the larger conversation as a whole
5. Feeding each chosen document into GPT3.5-turbo and receiving its summary of your conversation
6. Piecing together the various summaries as one large summary

# Additional Resources
For more information on how the code works step-by-step see my Medium post:
https://medium.com/@rohankumar_75589/using-langchain-to-summarize-long-imessage-text-conversations-c97137851f4c
