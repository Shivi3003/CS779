# CS779
# AutoPOT: Automatic Program of Thoughts Generation



## Abstract
AutoPOT is a groundbreaking project that harnesses the power of large language models (LLMs) to automatically generate Python code solutions for mathematical problems. By combining Automatic Chain of Thought (Auto-CoT) and Program of Thoughts (PoT) techniques, we achieve accurate and interpretable responses. Our approach clusters similar questions, extracts representative prototypes, and utilizes these prototypes to prompt LLMs for generating solutions.

## Introduction
AutoPOT leverages the advancements in large language models to address the challenge of improving LLMs' performance on mathematical problem-solving tasks. We integrate the Chain of Thought (CoT) model, which capitalizes on LLMs' ability to generate natural language rationales and perform few-shot learning, to enhance reasoning abilities. We introduce the Auto-CoT and PoT methods to achieve intelligent reasoning in arithmetic, commonsense, and other domains.

## Problem Definition
The project aims to enhance LLMs' accuracy in solving mathematical problems by improving the quality of prompts used. The challenge is to generate Python code rationales that lead to correct answers and are interpretable. Our goal is to achieve true intelligence in reasoning and efficient learning of new reasoning skills.

## Proposed Approach
1. Cluster similar questions using k-means clustering to identify representative prototypes.
2. Zero-shot prompt representative questions to generate responses.
3. Utilize the responses as prompts to enable LLMs to solve new unseen questions.

## Experiments and Results
We evaluated our approach on GSM8K and MultiArithmetic datasets. 
Our results showcase improved reasoning and accurate solutions. 
Comparison of Zero-Shot vs. PoT clusters on GSM8K dataset demonstrated the effectiveness of our approach (Figure 1).

## Error Analysis
Resource constraints, specifically limited access to TPU VMs, posed challenges during the coding phase. Adaptations were made to incorporate GPU-compatible models and datasets.

## Future Directions
Future work involves implementing PoT instead of Zero-Shot-CoT for better results on GSM8K clusters.
The plan is to explore ensemble models combining PoT and Auto-CoT. 
Additional experiments and comparison of these models will contribute to advancing CoT reasoning.


## Conclusion
AutoPOT presents a pioneering approach to automatic program of thoughts generation. Integrating Auto-CoT and PoT, we achieve accurate reasoning and Python code generation. While resource constraints affected initial implementations, we remain committed to improving and expanding this project.

## References
- Jason Wei et al., 2023. Chain-of-Thought Prompting Elicits Reasoning in Large Language Models.
- Wenhu Chen et al., 2022. Program of Thoughts Prompting: Disentangling Computation from Reasoning for Numerical Reasoning Tasks.
- Eric Zelikman et al., 2022. STaR: Self-Taught Reasoner.

For more details, refer to the complete project report and code implementation.
