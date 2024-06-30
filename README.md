# Interactive ChatBot
Interactive chatbot for, to answer the most tacky question, "What's cooking?". Developed as a personal project to understand about knowledge embedded LLM model.

Problem statement - to develop an interactive chatbot, 
database - The Food Processor https://huggingface.co/datasets/Thefoodprocessor/recipe_new_with_features_full
This database is a compilation of recipes that can be explored in multiple ways. It includes information on allergies, specifying whether each dish is gluten-free, vegan, vegetarian, LowFODMAP, and more. Additionally, it indicates the appropriate time of day for each dish and suggests alternative ingredients in case some are unavailable.

Next was to explore the possibilities with LLM model, the very cool video gives a precise information about the difference with fine tunning and knowledge base model - https://www.youtube.com/watch?v=Q9zv369Ggfk

To develop a custom knowledge-based model, the concept of embedding is introduced. This involves vectorizing the information to create a vector space of related data. Detail information of embedding and vector space is discussed in article - https://medium.com/@vladris/embeddings-and-vector-databases-732f9927b377

Of the available vector database Chroma db was selected for implementation, its step up guide is provided - https://www.datacamp.com/tutorial/chromadb-tutorial-step-by-step-guide

With the database and vector space in place, the next step is to explore a Large Language Model (LLM). There are numerous LLMs available, pretrained on text, audio, and image data. The best-suited model can be selected based on the application requirements. Here, we will experiment with GPT4ALL models, which are lightweight and do not require an external GPU or internet server for processing. Detailed information about the various available models is presented on the official page - https://gpt4all.io/index.html




