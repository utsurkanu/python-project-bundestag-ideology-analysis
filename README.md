# python-project-bundestag-ideology-analysis
Analyzing political ideology in German Parliamentary speeches using LLMs



**Prepared by:** Ulyana Tsurkanu, Jan Dzemiashkevich, Fandi Chen


---

## Overview
This project examines how political ideology is expressed in speeches from the German Bundestag. Using computational text analysis and large language models, it explores whether party speeches reflect recognizable ideological positions and how similar or different parties are in ideological terms.

The project treats ideology as **multidimensional**, rather than placing parties on a single left–right scale.


---

## Data
- **Dataset:** Bundestag-v2 (Threite, 2023)  
- **Unit of analysis:** individual parliamentary speeches  
- **Language:** German  
- **Size:** approximately 140,000 speeches  
- **Labels:** each speech is labeled with the speaker’s political party  

> All data used in this analysis is included or generated in the notebook — no external downloads are required.

---


## Repository Contents
- `PROJECT_V5.ipynb` – main analysis notebook  
- `report.pdf` – written report with detailed methodology, results, figures, and references  
- `README.md` – this file  

---

## How to Use
1. Open `PROJECT_V5.ipynb` in [Google Colab](https://colab.research.google.com/) or locally with Jupyter.  
2. All data and code are included in the notebook; no external downloads are required.  
3. Run all cells to reproduce the analysis and figures.

The `report.pdf` contains a detailed interpretation of the results.

---

## References
- Benoit, K., & Laver, M. (2006). *Party policy in modern democracies*.  
- Threite, J. (2023). *Bundestag-v2 dataset*.  
- Halterman, L., & Keith, D. (2025). *Codebook LLMs: Evaluating LLMs as Measurement Tools for Political Science Concepts*.  
- OpenAI ChatGPT (2023). Used as part of methodology for ideological classification and text analysis.  

