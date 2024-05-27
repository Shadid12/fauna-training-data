This guide shows how to generate synthetic data using GPT-4o for training the llama-3 model


## Meta Prompt
Give GPT-4 the following meta prompt

---
I am going to teach you a new programming language. It is called Fauna Query Language or FQL. Following are some syntax and examples of  this language. Answer questions based on the following context:

## Context
Copy a section of the documentation from docs.fauna.com. This is the context you are training the LLAMA-3 for. Make it clear and precise. You can try various prompt engineering and teach the GPT-4o model the concept in the documentation.

## Generate Synthetic Training Data
After you teach the concept. Feed couple lines of data as example data from `mytrain.json` file. Based the sample training data ask GPT to create synthetic training data for LLAMA-3. Make sure to evaluate some of the results. Although GPT-4o is more capable it still produces inacuracies.
