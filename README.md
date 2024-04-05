# Leveraging ChatGPT and Prompt Engineering to Support Contract Analysis - Project Datasets

Welcome to the repository containing the dataset created for the "Leveraging ChatGPT and Prompt Engineering to Support Contract Analysis" project. Our project focuses on utilizing advanced AI models to enhance the analysis of legal documents, providing insights into how these models can be leveraged in the field of law.

## Dataset Overview

The initial dataset features an XLS file containing the results of various prompting techniques tested on OpenAI's ChatGPT models (versions 3.5 and 4). These techniques include:

- Zero-shot learning
- Zero-shot with chain-of-thought learning
- Few-shot learning

The data originates from the Terms and Conditions of Italian websites, reflecting the nuances of Italian law. This dataset serves as a foundational resource for understanding how different prompting techniques influence model performance in legal contexts.

## Purpose of the Dataset

The primary goal of this dataset is to provide a preliminary understanding of how AI models, particularly ChatGPT 3.5 and 4, can be applied to improve workflows in legal environments. It explores how various prompting techniques can enhance the models' effectiveness, providing a stepping stone for developing best practices in AI-assisted legal document analysis.

More precisely, the dataset comprises a set of prompts provided as input to ChatGPT-3.5 and ChatGPT-4. It also includes tables with the results of both the annotation cycle and the final aggregated results. Finally, a sheet is dedicated to outlining the number of discrepancies between the first and second cycles of annotations.

## How to Use the Dataset

In the dataset, you will find the following sheets:

- `prompts_with_score_v1`
- `result_v1`
- `prompts_with_score_v2`
- `results_v2`
- `discrepancy (hallucinations)`
- `aggregated_results`

This dataset is intended for researchers, data scientists, and legal professionals interested in the automatic classification of contract clauses by leveraging large language models (LLMs). It can be used to:

- Compare the effectiveness of different prompting techniques for the automatic classification of contract clauses.
- Develop strategies for integrating AI into legal research and document analysis.
- Explore the potential of AI to provide insights into legal terminology and concepts based on Italian law.

We encourage you to delve into the dataset and explore the possibilities it unveils for the intersection of AI and contract analysis.