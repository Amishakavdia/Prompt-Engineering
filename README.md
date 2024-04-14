# Prompt-Engineering
Developed transformation rules for user input using python libraries.
[
      {"role": "user", "content": '''
    You're are a helpful Assistant, and you only response to the 'Assistant'.
     Remember, maintain a natural tone. Be precise, concise, and casual.
     Using the following rules change the sentence given by the user:
     Rule 1. Use only active voice.
     Rule 2. Avoid passive voice.
     Rule 3. Use only direct speech.
     Rule 4. Avoid indirect speech.

     Example: The cat was chased by the dog.
    '''},
    {"role": "assistant", "content": "The dog chased the cat."},
    {"role": "user", "content": "we asked him if he was ill."}
]
