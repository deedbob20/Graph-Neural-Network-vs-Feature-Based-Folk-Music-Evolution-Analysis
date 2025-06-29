# Supporting Documentation

This is all the supporting documentation produced for the 'Graph Neural Network vs Feature-based based Folk Music Evolution Analysis' paper, presented at EvoMUSART 2025, in Trieste, Italy. 
[Link to paper (PDF)](https://link.springer.com/chapter/10.1007/978-3-031-90167-6_21)

## Files:

- ABC_Guide.txt
    - *Simple explainer on ABC notation*
- abctunebooks_processing.ipynb
    - *Notebook to process the abc tunebooks, extractinf separate tunes*
- Clustering.ipynb
    - *Notebook to perform K-means clustering on musicological features*
- CreateBalancedGraph.ipynb
    - *Notebook to create a graph from the tune data*
- ExtractPitchRhythmVectors.ipynb
    - *Notebook to extract raw pitch and rhythm vectors from each tune*
- GCN_Testing.ipynb
    - *Notebook to test GCN model*
- GCN_Training.ipynb
    - *Notebook to train GCN model*
- GraphSAGE_Testing.ipynb
    - *Notebook to test GraphSAGE model*
- GraphSAGE_Training.ipynb
    - *Notebook to train GraphSAGE model*
- MelodicSimilarity.ipynb
    - *Notebook to create a Similarity-Based graph from the datasets*
- NormalisedFeatureVectors.ipynb
    - *Notebook to create length-normalised feature vectors, from the raw feature vectors*
    

## Folders:
- **/Dataset:**

    *This folder contains all the data collected and processed for this project.*

    - #### Files/Sub-Folders:

        - 5_class_edge_df_50yrN.pkl
            - *This file contains the edge dataframe for the 5 Class Dataset*
        - 5_class_tune_year_labels.pkl
            - *This file contains the labels for each tune in the 5 Class Dataset*
        - 10_class_edge_df_50yrN.pkl
            - *This file contains the edge dataframe for the 10 Class Dataset*
        - 10_class_tune_year_labels.pkl
            - *This file contains the labels for each tune in the 10 Class Dataset*
        - file_features_clean.pkl
            - *This file contains the raw pitch and rhythm vectors for every tune (>13,000)*
        - file_features_clean.tsv
            - *This file contains the raw pitch and rhythm vectors for every tune (>13,000), but as a readable tsv*
        - normalised_pitch_vectors_clean.pkl
            - *This file contains the length-normalused pitch vectors for every tune (>13,000)*
        - normalised_rhythm_vectors_clean.pkl
            - *This file contains the length-normalused rhythm vectors for every tune (>13,000)*

- **/saved_models:**

    *This folder contains the saved model state dictionaries for each of the trained GNN models. These can be loaded in the notebooks ending in '_Testing.ipynb'*

- **/split_data:**

    *This folder contains the partioned datasets (train, val, test), which load as PyTorch Geometric 'Tune' objects*




