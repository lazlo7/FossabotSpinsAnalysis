# Spins Analysis in erobb221's Twitch Chat

- `./src/fetch.ipynb` - notebook to fetch `!spin` command logs from Fossabot using `logs.ivr.fi`.
- `./src/analysis.ipynb` - various statistics and graphics created with fetched logs.

Analysis of `!spin` Fossabot command in erobb221's twitch chat.  
Emoji rendering done with custom build of `mplcairo`, a `cairo` backend of matplotlib.  
Emojis are rendered using `NotoColorEmoji` font, which should be in `./data/` folder.  

This is just a simple pet-project, many things could be improved upon (i. e. emoji font not hardcoded, 
mplcairo build script not located and so on).  
Note that the notebooks are meant to be opened in `vscode` via the `Jupyter Notebook` extensions.
