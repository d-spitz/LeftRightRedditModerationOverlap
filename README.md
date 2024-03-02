# Project Summary
This project is part of an investigation into the moderation ecosystems of top English-speaking left-wing and right-wing political subreddits. In particular, we looked at the overlap of moderators and their rules between these communities, with graph and LLM analysis, respectively. Overall, we noticed that the right-wing group had more overlap in both ways, especially in regards to shared moderators.

# Authors
This research was done by Tess Eschebach and David Spitz for Nick Feamster's course on Internet Censorship.

# Code Structure
- `src` contains our code, both Reddit scraping and analysis
- `input` contains our lists of top left-wing and right-wing subreddits along with notes
- `subredditdata` contains our collected data on moderators (anonymized) and rules from each subreddit
- `graphs` contains visualizations of moderator overlap using gephi

# Acknowledgements
Thanks to the Github user [almayor](https://github.com/almayor) for allowing us to use their [effective moderation overlap code and approach](https://github.com/almayor/reddit-mod-overlap).