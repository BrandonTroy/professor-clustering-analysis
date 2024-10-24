## TODO
- Finish preprocessing into df
  - Only 2649 professors were found when mapping gradient data to ratemyprofessor data; search through missed_names.txt and not_found.json to try and minimize wrongly missed profs

## Possible Clustering Methods
- cluster by manually drawing lines where it looks nice
- 

## Progress Report
10/22:
- Created filtered_distributions.json (filtered out all class sections from distributions.json where the professor wasn't found via 0.75 fuzzy search; dropped 28333 sections and 3998 instructors)
- Created further_filtered_distributions.json (heavier filter on previous file, removed middle names and make cutoff 0.9)

10/23:
- Combined data into combined_data.csv
- Created missed_names.txt and not_found.json for names/sections that weren't mapped to a professor in the ratemyprofessor dataset
