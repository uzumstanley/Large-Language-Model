# Large-Language-Model

xLLM: New Generation of Large Language Models

# Mixture of experts
One specialized, small sub-LLM per top category
LLM router (multi-agent system) to manage the sub-LLMs
User selects top category and hyperparameters
Each sub-LLM built with its own taxonomy and knowledge graph

# No neural network, no training
Thus, low cost, easy to fine-tune (in milliseconds per sub-LLM)
Self-tuned based on favorite hyperparameters, and customizable
No GPU, no latency, better results, local implementation

# Concise results
Multiple sections displayed to user: links, related content, x-embeddings
Output with relevancy score attached to each item in each section
Supports bulk queries, output saved to file
Great for search, targeted to busy professional users and experts

# Case studies
Corporate corpus with augmented sources (content + taxonomies)
Wolfram corpus: 15 sub-LLMs, 500 sub-categories per sub-LLM
Publisher, 4000 titles: clustering, predicting article performance
