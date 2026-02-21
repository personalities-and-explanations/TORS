# README: Resource Repository
This repository contains the datasets, prompts, scripts, and interface screenshots used in the paper:

**Exploring Personality-Aware Explanations for Recommender Systems**

**Authors:**  
Gabrielle P. Alves, Dietmar Jannach, Marcelo G. Manzato, Luan F. Souza  

**Publication Venue:**  
To appear in []

## Citation
If you use this dataset, code, or prompts in your research, please cite the following paper:

```bibtex
@inproceedings{alves2026ocean,
  author    = {Alves, Gabrielle and Jannach, Dietmar and Manzato, Marcelo G. and Souza, Luan F.},
  title     = {Exploring Personality-Aware Explanations for Recommender Systems},
  booktitle = {},
  year      = {2026},
  publisher = {},
  address   = {}
}
```

## Content of the Folders

### 1. Datasets:
1. **lexical_frequencies_standardized_residuals.csv:** This file contains the original Portuguese tokens and the corresponding standardized residuals derived from the chi-square analysis.
2. **token_translation_mapping.ipynb:** This file contains the original Portuguese tokens, their English translations, and the matched Big Five trait category after stemming.
3. **users_data.csv:** This file contains the primary dataset gathered during our main study. It includes user interactions, responses, and behavioral logs.

### 2. Prompts:
1. **final_prompts_english.json:** Contains the finalized prompt templates in English used to generate personality-aligned explanations for music recommendations.
2. **final_prompts_portuguese.json:** Contains the finalized prompt templates in Portuguese used to generate personality-aligned explanations for music recommendations.

### 3. Screens:
Multiple images showcasing the various interfaces that are part of the study, organized sequentially to match the study flow.

### 4. Scripts
This folder contains the analysis notebooks used to generate results for the paper.

- **Demographics.ipynb**  
  Produces the participant demographics summary and trait distribution counts used in Section 4.1.

- **RQ1_LexicalEvaluation.ipynb**  
  Runs the lexical evaluation pipeline for RQ1 and outputs the classification metrics (precision, recall, F1-score) by trait and explanation condition.

- **RQ1_chisquare.ipynb**  
  Computes chi-square analyses and residual-based outputs used for explanation-type comparisons.

- **RQ2a_PreferredExplanationType*.ipynb**  
  Analyzes preferred explanation type outcomes for RQ2 and generates pairwise comparisons and summary outputs.

- **RQ2b_Trait(Non_)EffectsOnChoice*.ipynb**  
  Tests trait-related and non-trait-related effects on choice behavior for RQ2.

- **RQ3a_RelatingPersonalityTraits*.ipynb**  
  Examines relationships between personality traits and perceived outcomes for RQ3.

- **RQ3b_ModelingStyleandPerson*.ipynb**  
  Models the relationship between explanation style and personality-related factors for RQ3.

- **RQ4_system_perception.ipynb**  
  Runs the system-level perception analyses for RQ4 (for example, trust, satisfaction, and intention to use).


### 5. Tables
This folder contains the paper-ready tables exported from the notebooks, organized by paper section.

- **Section 4.1 Participant Demographics and Trait Distribution**  
  Tables reporting sample demographics and trait distributions.

- **Section 4.2 RQ1: Generating Personality-Aware Explanations at Scale**  
  Tables reporting RQ1 evaluation results (for example, classification metrics and summary comparisons).

- **Section 4.3 RQ2 Personality Trait Effects on Choice Behavior**  
  Tables reporting RQ2 choice behavior analyses, including tests and post-hoc comparisons.

- **Section 4.4 RQ3 Perceived Perception Outcomes**  
  Tables reporting RQ3 perception outcomes across explanation types and trait groups.

If you are looking for the exact output used in the manuscript, start with the file in the Tables folder that matches the manuscript section number, then follow the corresponding notebook in the Scripts folder.
