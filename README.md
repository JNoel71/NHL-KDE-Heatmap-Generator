# NHL-KDE-Heatmap-Generator

This is KDE heatmap generator for NHL shooting data. The program is written in a python jupyter notebook and 
makes use of the matplotlib, seaborn, pandas, numpy, scipy, and ipywidgets modules.

The database used contains all NHL fenwick-based shot attempts from 2011-2021, this database was created using the
event data from NHL games which was scraped with the help of Harry Shomer's python module hockey_scraper.

This notebook takes two names of players and compares where either their goals, shots, misses, or shot attempts are
taken. You can choose between these types with the help of the interactive dropdown. The notebook also has the
ability to filter the events for just even strength situations, powerplay situations, or all situations.

There is more information available within the actual notebook named shot.ipynb.
