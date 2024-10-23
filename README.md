## TODO
- Finish preprocessing into df
  - Get average professor GPA by cross-referencing professor dataset with gradient distributions per class
  - Remove professors who didn't teach any classes

## Possible Clustering Methods
- cluster by manually drawing lines where it looks nice
- 

10/22/2024:
- Created filtered_distributions.json (filtered out all class sections from distributions.json where the professor wasn't found via 0.75 fuzzy search; dropped 28333 sections and 3998 instructors)
- Created further_filtered_distributions.json (heavier filter on previous file, removed middle names and make cutoff 0.9)