# HH Demo Dependency Scoring Impact On Staffing Need Analysis

## About
- This analysis is a pilot use of python using **synthetic data** to demonstrate how a care home business can implement resident dependancy scoring.
- The purpose being to identify sites that are overstaffed or understaffed and suggest actions to reallocate appropriately ensuring resident care needs are sufficent whilst idenfying cost saving areas.
- Whilst the main objective centers on the theme of the project, the side objective is to show how analysis using python can give us a competitive edge in the market.
## Key Features
### This project contains:
- A breakdown of what synthetic data was created and why.
- A walkthrough of the analysis done.
- Conclusions and suggested action of what HH should do based of the analysis done.
## Getting Started
To Explore the analysis, clone the rpo and run the notebooks in order.

## Prerequisistes
- Python 3.10+
- Juypter Notebook / VS Code with Juypter extension
- libraries used: pandas, numpy, matplotlib, seaborn, sci-kit-leearn, faker

## Installation

git clone https://github.com/your-username/hh-dependency-analysis.git
cd hh-dependency-analysis
pip install -r requirements.txt

### Configuration
- Random seed: np.random.seed(42)
- All data is synthetic — no real resident or staffing data is used
- Scope: 50 homes, ~2,800 residents

## Usage
- Start with generate_data.ipynb to generate the 4 CSVs of synthetic data.
- Then run analysis.ipynb to execute the full analysis pipeline.
