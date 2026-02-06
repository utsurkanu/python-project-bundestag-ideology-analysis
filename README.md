# python-project-bundestag-ideology-analysis
Analyzing political ideology in German Parliamentary speeches using LLMs



**Prepared by:** Ulyana Tsurkanu, Jan Dzemiashkevich, Fandi Chen

---

## Overview
This project analyzes how political ideology is expressed in speeches from the German Bundestag. Using computational text analysis, it examines whether party speeches reflect recognizable ideological positions and how similar or different parties are in ideological terms.

The project treats ideology as multidimensional rather than a single left–right scale.

---

## Research Questions
- Do Bundestag speeches reflect party ideology?
- How similar are political parties based on the content of their speeches?
- Can modern AI-based text methods capture ideological structure in parliamentary discourse?

---

## Data
- **Dataset:** Bundestag-v2 (Threite, 2023)  
- **Unit of analysis:** individual parliamentary speeches  
- **Language:** German  
- **Size:** ~140,000 speeches  
- **Labels:** each speech labeled with the speaker’s political party  

> ⚠️ To reproduce the analysis, you will need access to the Bundestag-v2 dataset. Please see [data access instructions] or contact the dataset author.

---

## Methods
- Speeches are classified into six ideological categories using a large language model.
- Sentence-BERT embeddings and PCA are used to explore ideological similarity and clustering.
- Party-level similarities are visualized using cosine similarity networks.

---

## Findings
- Party speeches reflect well-known ideological positions.
- Ideologically closer parties show greater similarity in speech content.
- Ideological differences are gradual and overlapping rather than sharply divided.

---

## Repository Contents
- `PROJECT_V5.ipynb` – main analysis notebook  
- `report.pdf` – detailed methodology, results, figures, references  
- `README.md` – this file  

---

## Usage
### Requirements
- Python 3.9+
- Install dependencies:
```bash
pip install -r requirements.txt

