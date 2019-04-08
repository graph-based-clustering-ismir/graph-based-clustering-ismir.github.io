# Graph-Based Audio Clustering for Browsing Online Sound Collections

This is a prototype application for showing the results of the graph-based audio clustering performed on search results from [Freesound](https://freesound.org/).

Each node in the graph correspond to a Freesound clip.
Edges between nodes reflect a notion of content-based similarity calculated with the [AudioSet](https://research.google.com/audioset/) embeddings or some acoustic features.

Clusters in the graph were identified using a Louvain community detection algorithm [implementation](https://github.com/taynaud/python-louvain/tree/networkx2) with the [NetworkX](https://networkx.github.io/) Python package.

Front Developement
-------------------
You can start a developement server by running this python script (python 3 required):
```
python3 start_dev_server.py
```
The application will be served at: `http://localhost:8100/`.


Graph Generation & Clustering
-------------------
TODO...
