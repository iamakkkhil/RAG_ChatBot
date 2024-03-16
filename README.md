# RAG (Retrieval Augmented Generation) ChatBot - Langchain

Created a ChatBot of __Alice in Wonderland__ Book using Langchain RAG in Python. <br>

Below are few Prompts that I have passed and response I got from the bot
1. __Prompt__: <u>What does the blue caterpillar do ?</u> <br>
__Response__: Based on the context you provided, the blue caterpillar takes the hookah out of its mouth and addresses Alice in a sleepy voice, after some silence. It also calls out to Alice when she turns away from it, and asks her to come back as it has something important to say.

2. __Prompt__: <u>Which potion did Alice drink ?</u> <br>
__Response__: Alice drank the "Drink Me" potion from the little bottle she found. The label on the bottle intrigued her as it had the words "Drink Me" written on it, and since it wasn't marked as poison, she decided to take a taste. She found the undefined flavor delightful, which encouraged her to finish the entire bottle.

3. __Prompt__: <u>Who wrote alice in wonderland?</u> <br>
    __Response__: Based on the context provided, Lewis Carroll wrote Alice's Adventures in Wonderland. The eBook edition released on June 27, 2008, was likely a re-release or an anniversary edition as the book was originally published earlier.


### Install dependencies.

```python
pip install -r requirements.txt
```

### Create the Chroma DB.

```python
python create_database.py
```

### Query the Chroma DB.

```python
python query_data.py "How does Alice meet the Mad Hatter?"
```

You'll also need to set up an Cohere account (and set the Cohere key in your .env file) for this to work.