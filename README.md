# Constructional Complexity Analyzer

---

## Project Description

The Constructional Complexity Analyzer (CCA) is a tool designed to measure the constructional diversity, constructional elaboration, and verbal diversity of English texts.

---

## Features

CCA outputs various scores for the following indices:

### 1. Constructional Diversity

Calculates the following diversity measures based on constructions:

- Root TTR (RTTR; Guiraud, 1960)  
- Herdan’s C (or log TTR; Chotlos, 1944; Herdan, 1960)  
- Maas’ score (Maas, 1972)  
- Moving-average type-token ratio (MATTR; Covington & McFall, 2010)  
- Hypergeometric distribution diversity index (HD-D; McCarthy & Jarvis, 2007)  
- Measure of textual lexical diversity (MTLD-Original; McCarthy, 2005; McCarthy & Jarvis, 2010) 
- Moving-average bidirectional measure of textual lexical diversity (MTLD-MA-BI; McCarthy & Jarvis, 2010)  
- Moving-average wrapped measure of textual lexical diversity (MT


### 2. Constructional Elaboration

Calculates the mean number of dependents (except punctuation marks) for individual constructions


### 3. Verb Inventory Size

Calculates log 10 [type frequency of verbs + 1 ] for individual constructions


---

## Installation

### 1. Install spaCy

```bash
pip install spacy
```

```bash
python -m spacy download en_core_web_sm
```

### 2. Install Constructional Complexity Analyzer

```bash
pip install constructional_complexity_analyzer
```

### 3. Run the Analyzer

```bash
constructional-analysis /path/to/text_files
```

---

## License

This project is licensed under the  
**Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License (CC BY-NC-SA 4.0)**.
