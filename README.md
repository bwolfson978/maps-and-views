Assignment 4 - Visualizations and Multiple Views  
===

https://bwolfson978.github.io/04-MapsAndViews/index.html

Technical Achivements
---
- dealing with relatively large data set - one of Stanford's interesting data sets
- reading in csv file from california - mapping names of counties to FIPS, storing data
- getting a single state from topojson - filtering by state id
- using querySelectors to get to the specific county regions in the topojson map proved very difficult
- using 4 views (minimum 3)
- using d3 dispatch between all views
- using brush on histogram, searching for all counties in range, showing on map
- interactivity on all views aside from bar chart

Design Achievements
---
- axes on charts
- titles on charts
- changing title on bar to give context to user (which county)
- highlighting of map counties
- tooltips on bubble hover
- bubble color scheme and size scheme
- organization of page
- brush view transparent on histogram

Sources
---
https://bl.ocks.org/mbostock/4060606
https://www.weather.gov/hnx/cafips
https://gist.githubusercontent.com/gregdevs/a73f8a16f129757c037e72ecdebdd8f2/raw/e36e06b88128a86534624a65a00375c5cea0a036/us.json
https://www.cde.ca.gov/ds/sp/ai/
https://bl.ocks.org/gregdevs/a73f8a16f129757c037e72ecdebdd8f2
https://jrue.github.io/coding/2014/exercises/basicbubblepackchart/
https://github.com/d3/d3-scale-chromatic/blob/master/README.md
https://bl.ocks.org/danielatkin/57ea2f55b79ae686dfc7
https://developer.mozilla.org/en-US/docs/Web/API/Document/querySelector
https://bl.ocks.org/mbostock/5872848
http://bl.ocks.org/nnattawat/8916402
https://hackernoon.com/htmlcollection-nodelist-and-array-of-objects-da42737181f9
http://softeng.oicr.on.ca/jeffrey_burt/2017/01/16/d3-brush/