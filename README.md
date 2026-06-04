# global-development-explorer-d3

# Global Wealth, Education and Population — D3 Interactive Visualisation

## Overview
[1-2 sentences about what the project does]

## Live Demo
[If you deploy it — see Step 5 below]

## Research Questions
- Q1: Analyse the relation between wealth and education. Are there detectable trends?
- Q2: Does government investment in education drive future wealth growth?
- Q3: Are low-income countries catching up with wealthier nations over time?

## How to Run
1. Clone the repository
2. Navigate to the project folder
3. Run: `python -m http.server 8000`
4. Open Chrome and go to: `http://localhost:8000/index.html`

## Features
- Animated bubble chart across 126 countries (2000–2021)
- Year slider with smooth transitions
- Hover tooltips showing country details
- Continent filter with animated exit

## Data Sources
- [International Wealth Index — Global Data Lab](https://globaldatalab.org/wealth/table/iwi/)
- [World Education Data — World Bank via Kaggle](https://www.kaggle.com/datasets/bushraqurban/world-education-dataset/data)
- [Population Data — World Bank](https://data.worldbank.org/indicator/SP.POP.TOTL)

## Technologies
- D3.js v7
- HTML, CSS, JavaScript
- Python (data preprocessing)

## Acknowledgements
D3 bubble chart adapted from [D3 Graph Gallery](https://d3-graph-gallery.com/bubble.html) by Yan Holtz.
Data exploration assisted by AI tools.
