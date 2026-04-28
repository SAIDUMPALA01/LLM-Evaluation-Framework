# LLM-Evaluation-Framework
Data and code for LLM evaluation framework paper
# LLM Evaluation Framework

This repository contains data and 
materials for the paper:

"A Multi-Dimensional Framework for 
Evaluating the Quality of LLM-Generated 
Outputs: A Literature Review and Taxonomy"

Author: Sai Rama Krishna Reddy Dumpala
Institution: Birmingham City University, UK
Date: April 2026

## Experiment Description

Five open-ended questions were asked to 
ChatGPT (free version, GPT-3.5) three 
times each in completely separate chat 
sessions with no shared history.

## Questions Asked

1. What are the main causes of climate change?
2. Explain what machine learning is in simple terms
3. What is the difference between AI and human intelligence?
4. How does ChatGPT generate responses?
5. What are the limitations of large language models?

## Key Finding

Only 1 out of 5 questions (20%) produced 
fully consistent answers across all 3 sessions.

## Files

- data/consistency_experiment_data.csv — Raw results
- data/raw_answers.txt — Full ChatGPT responses
- paper/paper.pdf — Full paper

## How to Reproduce

1. Open chat.openai.com
2. Start a new chat session
3. Ask each question
4. Close and start a new session
5. Repeat 3 times per question
6. Compare answers using the rubric in the paper
