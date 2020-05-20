# COVID-19 Geographical Animation Generators

These Mathematica files will read COVID-19 time series data from 
Johns Hopkins University Center for Systems Science and Engineering's GitHub page
and generate an mp4 movie file that animates how the numbers of positive cases developed over space and time.

Examples can be seen in the following:
* US nationwide animation: https://twitter.com/HirokiSayama/status/1261623727772631047/video/1
* Worldwide animation: https://twitter.com/HirokiSayama/status/1262109704328810496/video/1

In the visualization, the size of each disc represents the number of daily new positive cases (scaled). The 
color of the disc is determined by (# of daily new cases) / (max # of daily new cases observed up to that point),
which ranges from 0 (end of epidemic; blue) to 1 (growing or peak of epidemic; red).

Data was smoothed using seven-day moving averages.
