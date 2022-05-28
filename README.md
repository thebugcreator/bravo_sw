# bravo_sw
The repository for BravoTeam Semantic Web Project

## Structure of the Repo:
- `ontology.owl` contains _____
- `players` contains all of the information about players.
  - `players_vocab.ttl` contains the vocabulary used to describe players.
  - `players_list.ttl` conains _____
- `video_games` contains all of the information and ontologies about video games.
  - `video_game_data_with_ontology.owl` is a file containing all of the data and ontologies in the `video_games` folder. If using protégé or blazegraph it is probably easiest to load this file alone so you don't have to load multiple files to vizualize or query the data.
  - `gave_voc.ttl` contains only the vocabulary used to describe video games.
  - `video_game_ontology.owl` contains only the video game ontology without any of the data individuals.
  - `wikidata_video_games.ttl` is the base of all of our video game information. It contains wikidata video games along with their genre, modes, platform, series, and publisher.
  - `wikidata_genres.ttl` contains all of the wikidata video game genres and their subgenres.
  - `wikidata_platforms.ttl` contains wikidata platforms of the following types: video game console (Q8076), home video game console (Q17589470), and home computer (Q473708), along with their release dates.

