# Pokemon-Games-Clustering-proposal
Machine learning project - proposal of a clustering solution for Pokémons in regard to their combat statistics and features.

tier_list.csv -> raw scraped data from the site “pokemon.neoseeker.com”.

tier_list_fixed.csv -> pre-existent clustering dataset, based on the tournaments fights,
                       scraped from the site “pokemon.neoseeker.com”. The data has been cleaned and
                       modified so that each cluster is equivalent to an integer value.

workflow_normalized.csv -> normalized dataset with the cluster attribute.

Scraping_tier_Pokèmon.ipynb -> Python notebook used for scraping, cleaning and preprocessing the data.

Radar_graph_Cluster.ipynb -> Python notebook used to create visual representations, 
                             in radar graph form, highlighting the differences
                             in mean values and standard deviation of the clusters.  
                             
Pokemon.knwf -> KNIME workflow for processing data and clustering                             
