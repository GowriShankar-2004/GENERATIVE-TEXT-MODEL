# GENERATIVE-TEXT-MODEL

*COMPANY*: CODTECH IT SOLUTIONS

*NAME*: AKULA GOWRI SHANKAR

*INTERN ID*: CT04DH833

*DOMAIN*: AI(ARTIFICIAL INTELLIGENCE)

*DURATION*:4 WEEKS

*MENTOR*: NEELA SANTOSH

## DESCRIPTION

Step 1: Import Required Libraries
The script imports modules from the transformers library by Hugging Face and PyTorch. These tools make it easy to load and use powerful pre-trained models like GPT-2.

Step 2: Load GPT-2 Tokenizer and Model
We use:

GPT2Tokenizer: Converts human-readable text into tokens the model understands.

GPT2LMHeadModel: The GPT-2 model that generates new text by predicting the next token in the sequence.

These are pre-trained and downloaded directly from Hugging Face’s model hub.

Step 3: Define the generate_text() Function
This function takes two parameters:

prompt: The starting sentence or idea you want the model to build on.

max_length: The maximum number of tokens (words + punctuation) in the generated text.

Inside the function:

The prompt is tokenized into a format suitable for the model.

The model is called with:

max_length=200: Controls how long the output should be.

do_sample=True: Enables sampling instead of greedy decoding, which produces more creative outputs.

top_k=50 and top_p=0.95: These parameters control randomness by limiting the sampling pool to the top probable words.

temperature=0.8: Adds a bit of randomness to make text more varied and natural.

Finally, the tokens are decoded back into human-readable text.

Step 4: Provide a Prompt and Print the Output
In the __main__ block, we define a prompt like:

“The impact of artificial intelligence on future education systems”

The function is called and the output is printed.

## OUTPUT

The impact of artificial intelligence on future education systems is expected to be profound. As AI technologies become more sophisticated, schools and universities may shift toward personalized learning environments that cater to individual student needs. Adaptive learning platforms, powered by AI, could monitor student progress in real-time and adjust lessons accordingly. Additionally, educators might rely on AI assistants to help with administrative tasks, freeing up time for more student interaction. However, the integration of AI also raises concerns about data privacy and the potential for over-reliance on automated systems. Balancing technological advancement with ethical considerations will be crucial in shaping the education of tomorrow.
