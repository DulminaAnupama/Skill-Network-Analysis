# Skill-Network-Analysis
This project models professional skills as a **network of dependencies** using large-scale co-occurrence data (20,000+ skills and millions of relationships).
# Skill Network Analysis

## Overview
This project models professional skills as a **network of dependencies** using large-scale co-occurrence data (20,000+ skills and millions of relationships).

The goal is to uncover:
- Gateway skills (high influence across domains)
- Monopoly skills (domain-dominant skills)
- Hidden structures in skill ecosystems

---

## Tech Stack
- Python
- Pandas
- NetworkX
- Matplotlib

---

## Methodology
1. Construct skill co-occurrence matrix
2. Compute **Jaccard similarity**
3. Build network graph using NetworkX
4. Apply centrality measures:
   - Degree Centrality
   - Betweenness Centrality
5. Identify:
   - Gateway Skills
   - Monopoly Skills

---

## Key Results

### Network Visualization
![Network](outputs/network_plot.png)

### Dependency Chain
![Dependency](outputs/dependency_chain.png)

### Gateway Skills
![Gateway](outputs/gateway_bar_chart.png)

### Monopoly Skills
![Monopoly](outputs/monopoly_bar_chart.png)

---

## Installation

```bash
git clone https://github.com/your-username/Skill-Network-Analysis.git
cd Skill-Network-Analysis
pip install -r requirements.txt
