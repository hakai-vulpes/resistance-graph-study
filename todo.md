# To-do List

Keep this at the end of the notebook, for documenting and keeping track.

- [x] Extract the players graph
- [x] Extract the games graphs
- [x] Calculate metrics
- [x] Create visualizations
- [ ] Design the poster

## Metrics

Some are interesting towards the players graph ("for players"), others are 
interesting in games graphs ("for games").
It's also important to take account that some of these are not designed for weighted 
graphs, so we can use them by rounding the weights, indicated as "to round".

- [x] Nodes degrees for most social or other metrics (for both)
- [x] Diamater (for both)
- [x] Social players tend to interact with other social players? (for games)
- [x] Cliques (for games + to round)
- [x] Betweenness (for both)
- [x] Clustering (for both)
- [x] Transitivity (for games + to round)
- [x] Reciprocity (for games + to round/adapt)
- [x] Eccentricity (for both)
- [x] Average shortest path (for players)
- [x] Comparison with random graphs (bad, but could be investigated)
- [x] Community detection (for players)

## Visualizations

We need at least one cool graph visualization of the players graph. After that, 
everything is optional. For instance we could retrieve time progression of 
interesting metrics like transitivity trend along games.

## Poster

Some requirements:

- Color scheme with good contrast
- Dislexic-friendly font
- Meaningful data exposed (not random metrics)