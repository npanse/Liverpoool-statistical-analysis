# Liverpoool-statistical-analysis

Premier League data preprocessing and visualisation in Tableau.

The data was obtained from http://www.football-data.co.uk/ and is stored in data master according to the seasons.
Liverpool 2012-2020 notebook has all the preprocessing details alng with scatter plots generation.

# Voronoi Diagram

The main sample file is ``liverpool_2019.csv``, which contains 19 goals scored by Livepool FC in 2019. The tracking data was provided by LastRow -

https://github.com/Friends-of-Tracking-Data-FoTD/Last-Row

You can get a feel for the dataset by checking the Jupyter Notebook included in this repository. Basic ploting is built on top of ``matplotlib``, and animations are built with ``moviepy``. The python file footyviz.py is used to draw Voronoi tessellations.

# Pitch Control
 
This repository is for plotting pitch control videos for 19 Liverpool goals throughout 2019.  The pitch control model was taken from Friends of Tracking -

https://github.com/Friends-of-Tracking-Data-FoTD/LaurieOnTracking

Both the data files have 3459 entries, and the following list tells the indices for each goal.

- 0-154: Liverpool 3-0 Bournemouth, PL
- 155-319: Bayern 0-1 Liverpool, UCL
- 320-502: Fulham 0-1 Liverpool, PL
- 503-759: Southampton 1-2 Liverpool, PL
- 760-954: Liverpool 2-0 Porto, UCL
- 955-1211: Porto 0-2 Liverpool, UCL
- 1212-1350: Liverpool 4-0 Barcelona, UCL
- 1351-1507: Liverpool 1-0 Wolves, PL
- 1508-1656: Liverpool 3-0 Norwich, PL
- 1657-1851: Liverpool 2-1 Chelsea, Super Cup
- 1852-2000: Liverpool 2-1 Newcastle, PL
- 2001-2191: Liverpool 2-0 Salzburg, UCL
- 2192-2374: Genk 0-3 Liverpool, UCL
- 2375-2541: Liverpool 2-0 Manchester City, PL
- 2542-2740: Liverpool 1-0 Everton, PL
- 2740-3027: Liverpool 2-0 Everton, PL
- 3028-3198: Bournemouth 0-3 Liverpool, PL
- 3199-3423: Liverpool 1-0 Watford, PL
- 3424-3458: Leicester City 0-3 Liverpool, PL
