# metis_project2_luther

## Notebooks
Notebooks should be run in this order:

### Web scraping: 
* DataScraper.ipynb

### Data massaging:
* Prepare_GamesData.ipynb
* Prepare_InjuryData.ipynb
* Prepare_MergeData.ipynb

### Regression:
* 3_process_data.ipynb

### Visualization:
* 4_graph.ipynb

### Other:
* correlations/*

## Data
Each stage outputs to their own folder, such as:

* data/1/fftoday_{years}_pos{position}.csv
* data/2/{position}.csv

Position numbering:
* 20 = RB
* 30 = WR
* 40 = TE
