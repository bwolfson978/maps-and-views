Assignment 4 - Visualizations and Multiple Views  
===

One of the most powerful techniques for mitigating the shortcomings of a given visualization is to link it with other views.
Linking a map to a bar or scatterplot, for instance, may allow you to overcome the shortcomings of a map.
In general, linking visualizations allows you to explore different parts of the data between views, and mitigates the shortcomings of a given view by pairing it with other views.
This technique, called coordinated multiple views, is the focus of this assignment.

Your task is to choose an interesting dataset and visualize it in *at least three* **linked** views.
Each view should use a different visualization type, and interaction in one of the views should impact what's shown in the other views.

You should choose data and visualizations that are sufficiently complex so a user can discover interesting patterns and trends on their own.

For this assignment you should write everything from scratch.
You may *reference and adapt* code from books or the web, and if you do please provide a References section with links at the end of your Readme.

Resources
---

Stanford recently released a set of [interesting datasets](http://cjlab.stanford.edu/2015/09/30/lab-launch-and-data-sets/).

Chris Viau maintains a [huge list of d3 examples](http://christopheviau.com/d3list/gallery.html), some will have multiple views.

See the course Tips page for more dataset possibilities.

These three examples are intended to show you what multiple views visualizations might look like. 
I wouldn't recommend using them as a your starting point, but you may find some inspiration:

1. This [scatterplot matrix](http://bl.ocks.org/mbostock/4063663) has code that explains brushing and linking. But remember you'll be doing this with different types of views.

2. The example visualization for [Crossfilter](http://square.github.io/crossfilter/) uses coordinated multiple views. The interaction and brushing technique is well-executed.

3. The [dispatching events](http://bl.ocks.org/mbostock/5872848) page is a good example of using events, rather than explicit functions, for controlling behavior. Views can listen for events in other views and respond accordingly.

This GIF from a similar course shows how views can work together:

![cmv gif](https://raw.githubusercontent.com/dataviscourse/2015-dataviscourse-homework/master/hw3/preview.gif)

The main [d3 api](https://github.com/mbostock/d3/wiki/API-Reference) and especially the [d3 dispatch page](https://github.com/mbostock/d3/wiki/Internals#events) will be useful.

*If you aren't familiar with event-based programming you should experiment with d3.dispatch and other approaches to coordinating views well before the deadline (it's tricky.)*

Don't forget to run a local webserver when you're coding and debugging.
See this [ebook](http://chimera.labs.oreilly.com/books/1230000000345/ch04.html#_setting_up_a_web_server) if you're stuck.

Requirements
---

0. Your code should be forked from the GitHub repo and linked using GitHub pages.
1. Your project should load a dataset you found on the web. Put this file in your repo.
2. Your project should use d3 to build a visualization of the dataset. 
3. Your writeup (readme.md in the repo) should contain the following:

- Working link to the visualization hosted on gh-pages.
- Concise description and screenshot of your visualization.
- Description of the technical achievements you attempted with this visualization.
- Description of the design achievements you attempted with this visualization.

GitHub Details
---

- Fork the GitHub Repository. You now have a copy associated with your username.
- Make changes to index.html to fulfill the project requirements. 
- Make sure your "master" branch matches your "gh-pages" branch. See the GitHub Guides referenced above if you need help.
- Edit the README.md with a link to your gh-pages site, for example http://YourUsernameGoesHere.github.io/04-MapsAndViews/index.html
- To submit, make a [Pull Request](https://help.github.com/articles/using-pull-requests/) on the original repository.

Technical Achivements
---
- reading in csv file from california - mapping names of counties to FIPS, storing data
- getting a single state from topojson - filtering by state id
- using querySelectors to get to the specific county regions in the topojson map proved very difficult
Design Achievements
---


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