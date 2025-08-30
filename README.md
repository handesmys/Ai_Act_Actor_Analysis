# Ai_Act_Actor_Analysis

AI Act Actor Analysis

This repository contains a Jupyter Notebook for analyzing actors, networks, and narratives surrounding the EU Artificial Intelligence Act (AI Act). The project applies actor-network analysis and semantic analysis techniques to explore how different stakeholders engage in debates around AI regulation.

📌 Project Overview

Goal: Understand the structure and dynamics of actors discussing the EU AI Act.

Methods:

Named Entity Recognition (NER) to extract actors from text.

Network construction of actors and their co-occurrences.

Centrality and community detection to identify influential stakeholders.

Semantic analysis of stance and relationships.

Dataset: Euractiv articles mentioning the AI Act (preprocessed and cleaned).

🛠️ Tech Stack

Language: Python 3

Libraries:

pandas, numpy – data manipulation

networkx – network analysis

matplotlib / seaborn – visualization

spaCy – NLP and NER

scikit-learn – clustering and analysis

📂 Repository Structure
AI_Act_Actor_Analysis.ipynb   # Main notebook with analysis
data/                         # (Optional) Preprocessed dataset(s)
README.md                     # Project documentation

🚀 How to Run

Clone the repository:

git clone https://github.com/your-username/ai-act-actor-analysis.git
cd ai-act-actor-analysis



📊 Outputs

Actor co-occurrence networks

Centrality rankings of actors (top influencers)

Visualization of semantic clusters

🔍 Research Objectives

This project contributes to understanding:

Key actors shaping the AI Act debate.

Intensity and distribution of their connections.

Directionality of interactions and narratives.

Stance categorization of actors (supportive, critical, neutral).

Network homophily/heterophily (alliances vs. disagreements).
