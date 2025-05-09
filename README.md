# RAG Prompt Engineering Experiment

## Project Overview
This project tests how small changes in prompt phrasing affect results from RAG (Retrieval-Augmented Generation) models like Perplexity.ai. We'll experiment with different versions of the same question across several topics to see how retrieved sources and answers change.

## Topics and Rationale
We've selected the following topics for specific reasons:

1. **Food Safety** - A universal social issue with abundant, factual data from authoritative sources (FDA, WHO, CDC). The wealth of established guidelines makes it ideal for testing how RAG models retrieve and prioritize standardized information.

2. **Mental Health** - A complex social topic with both scientific research and subjective perspectives. This allows us to test how RAG models balance clinical evidence with more nuanced, experience-based information.

3. **Wearable Health Tech** - A rapidly evolving field with a mix of technical specifications, scientific studies, and consumer reviews. This helps test how RAG models handle topics with both current and potentially outdated information.

These topics were chosen because they:
- Address important social issues with real-world implications
- Have abundant data from diverse, authoritative sources
- Represent different types of information (factual guidelines, scientific research, and evolving technology)
- Allow us to ensure the stability and reliability of our prompt engineering findings across different knowledge domains

## Methodology
For each topic, we'll create multiple prompt variations that:
- Vary in specificity
- Include different amounts of background information
- Use different phrasing styles
- Include or exclude context

## Results Tracking
For each prompt, we'll record:
- The prompt used
- Sources retrieved by the RAG model (with publication dates and authority level)
- Quality of the answer
- Relevance of information
- Any notable differences between prompt variations

## Goal
Determine which prompt engineering techniques most effectively help RAG models retrieve relevant information and generate useful answers.
