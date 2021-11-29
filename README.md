# covid-us-networks
Analysing COVID-19 in the US using networks.

Data:

* [NYT Data](https://github.com/nytimes/covid-19-data)

* [Kaggle version](https://www.kaggle.com/fireballbyedimyrnmom/us-counties-covid-19-dataset)

* [States adjacency list](https://gist.github.com/neilb/ee60cd179d5eb17d1cb616cdeeda760f) - Edited to add DC and regions

* Counties adjacency list: [Cenus Bureau](https://www.census.gov/programs-surveys/geography/library/reference/county-adjacency-file.html), [NBER](https://www.nber.org/research/data/county-adjacency)

Links to specific COVID-19 data files used:

* [States](https://github.com/nytimes/covid-19-data/blob/master/us-states.csv)

* [Counties](https://github.com/nytimes/covid-19-data/blob/master/us-counties.csv)

Graphs directory:

* Basic networks: *_graph.gml (these are created from network_builder.ipynb)

* Graph metric networks: *_graph_nw_metrics.gml (these are created from network_metrics.ipynb using _graph.gml as a base, and contain network metrics as node properties e.g. betweenness)

* Correlation networks: *_corr.gml (these are created from correlation_networks.ipynb)