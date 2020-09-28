# GrimmTextSimilarities
The purpose of this repository is to calculate and graph text similarities of the Grimm fairy tales.

Grimm Fairy Tales were imported into Python, and text similarities were computed using NLP, by calculating the TF-IDF vectors of each text document (term frequency–inverse document frequency), and computing the Cosine Similarity between these vectors.

Then, documents above a certain thershold (in this case 0.6) were chosen to be "similar". These relationships were then plotted using Neo4J.
