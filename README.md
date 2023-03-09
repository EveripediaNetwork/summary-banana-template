# This repo holds the files for Flan-T5 base model fine-tuned for summarisation.

## INPUT
{
  "prompt": "A long text to summarize.",
  "min_length" : 25, 
  "max_length" : 30
}
## OUTPUT
{
  "output": "A short summary of the text."
}

## CODE SNIPPETS
### PYTHON

import banana_dev as banana

model_inputs = {
  "prompt": "A long text to summarize."
}

api_key = "YOUR_API_KEY"
model_key = "YOUR_MODEL_KEY"

### Run the model
out = banana.run(api_key, model_key, model_inputs)

<br>

## Helpful Links
Understand the 🍌 [Serverless framework](https://docs.banana.dev/banana-docs/core-concepts/inference-server/serverless-framework) and functionality of each file within it.

Generalize this framework to [deploy anything on Banana](https://docs.banana.dev/banana-docs/resources/how-to-serve-anything-on-banana).

<br>
