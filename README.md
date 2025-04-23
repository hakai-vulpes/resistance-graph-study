# Analysis of behavior in "The Resistance" game.

This project explores player behavior in The Resistance by focusing on non-verbal
clues, specifically eye movements and visual attention throughout the game. Everything
used has been extracted from "https://snap.stanford.edu/data/comm-f2f-Resistance.html"

We applied social computation techniques to extract meaningful metrics such as 
betweenness centrality, graph diameter, modularity, and clustering coefficient 
with a special focus on similarity, which plays a key role in generating embeddings 
to facilitate deeper analysis.

To begin, player embeddings were created in the notebook generation.ipynb, based on 
similarity of behavior. 
The visualization file displays a community-based representation of these embeddings. 
In the analysis file, various metrics are calculated to highlight differences between groups, 
helping to identify where the most likely deceivers may be hiding.

## Autores
- Daniel Moraleda Sánchez  
- Daniel Navarro Puche