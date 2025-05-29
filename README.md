# CCLAMP_Topic-modelling
These scripts can be used to perform topic modelling on the texts in C-CLAMP.

For the individual texts:
* use `C-CLAMP_topic modelling.ipynb`
* add the results to the texts' metadata file (`C-CLAMP_metadata.txt`)

The output can be found in the `Output for texts` folder.


For the authors' complete oeuvres:
* first group the texts per author into a single .txt file using `C-CLAMP_group_by_author.ipynb`
* perform topic modelling with `C-CLAMP_topic modelling_authors.ipynb`
* add the results to the author metadata file (`author_metadata_hisclass_final.txt`)

The output can be found in the `Output for authors`folder.
