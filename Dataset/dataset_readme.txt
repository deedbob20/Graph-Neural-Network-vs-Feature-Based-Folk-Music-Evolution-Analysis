Dataset Explainer:

- 'file_features_clean'
	- Dataset containing all the rhythm and pitch vectors for each tune (cleaned to remove tunes without one or the other)

- 'normalised_pitch_vectors_clean.pkl'
	- Equal length pitch vectors, for each tune (shows percentage of each interval)

- 'normalised_rhythm_vectors_clean.pkl'
	- Equal length rhythm vectors, for each tune (shows percentage of each rhythmic duration)


- '5_class_tune_year_labels.pkl'
	- Classes:
		- 1650, 1700, 1750, 1800, 1850
	- 200 nodes per class
	- Each node has 100 Neighbours
	- Balanced across 25 year period
	- '5_class_edge_df_50yrN.pkl
		- Each node’s neighbour is within 50 years
		- 5_class_50yrN_split
			- Train, Val, Test split of the same dataset


'10_class_tune_year_labels.pkl'
	- Classes:
		- 1650, 1675, 1700, 1725, 1750, 1775, 1800, 1825, 1850, 1875
	- 100 nodes per class
	- Each node has 100 Neighbours
		- Balanced across 25 year period
	- 10_class_edge_df_50yrN.pkl'
		- Each node’s neighbour is within 50 years
		- 10_class_50yrN_split
			- Train, Val, Test split of the same dataset		


