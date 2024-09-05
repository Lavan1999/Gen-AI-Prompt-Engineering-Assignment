# Prompt Engineering
## Objective: 
Improve the performance of a model on a summarization task by designing and evaluating different prompts.

## Steps Taken:

## Setup and Installation:

Installed necessary libraries: transformers, datasets, and rouge-score.
Loaded the BART model for summarization.
## Model and Tokenizer:

Used facebook/bart-large-cnn for the summarization task.
Initialized the summarization pipeline.
## Prompt Definition:

Created prompts to guide the summarization:
"Summarize the following text into a brief overview:"
"Extract and present the key points from the text:"
## Sample Text:

Provided a sample text on AI for summarization.
## Generating Summaries:

Implemented a function to generate summaries based on different prompts.
Generated summaries for each defined prompt.
## Evaluation:

Defined a reference summary for comparison.
Used ROUGE metrics to evaluate the quality of generated summaries.
## Results:

# Generated Summaries:

* Prompt 1: "Artificial Intelligence (AI) refers to the simulation of human intelligence in machines designed to think and learn like humans. Leading AI textbooks define the field as the study of 'intelligent agents'"
* Prompt 2: "Artificial Intelligence (AI) refers to the simulation of human intelligence in machines designed to think and learn like humans. Leading AI textbooks define the field as the study of 'intelligent agents'"
ROUGE Evaluation:

- Prompt 1:
ROUGE-1: 0.638
ROUGE-L: 0.638
- Prompt 2:
ROUGE-1: 0.638
ROUGE-L: 0.638
Summary and Insights:

Both prompts yielded identical summaries in this instance, which indicates that the model's output may not be heavily influenced by the slight variations in prompt wording.
The ROUGE scores show a good match with the reference summary, indicating effective summarization by the model.

