# d3-prosper-loan-chloropleth

## Summary

My D3 visualization maps Prosper (a peer-to-peer lender) loans from 2006 to 2014. The Prosper dataset used includes 113,937 loans with 81 variables on each loan, including loan amount, borrower rate (or interest rate), current loan status, borrower income, and many others. I choose to investigate the progression of lendee state and loan amount to get a picture of where the highest loan density occurs. Once I plotted overall loan density, I included a time component to show the geographic fluctuations in loan density. What I discovered was that the loan density traces the story of Prosper and the US economy as a whole; loan density starts out strongest on the west coast (where Prosper was founded in 2005), then follows the movement of the US economy (with dips in 2008 - 2009).

## Design

TBD

## Feedback

*Jean* (initial sketches)
- Try plotting on some kind of map instead of separating each state into its own plot.
- Noted that bigger / more populous states were also states with more loans.

*Alex* (midway)
- Suggested that I use a continuous color scale to more clearly see loan increase over time.
- Change blacked out states to more washed out color.

*Chris* (midway)
- Add animation, so viewer immediately sees the progression over time.
- Include supplementary charts like bar plot, or something, that compliment the map.
- Create tool tip with additional information about each state


## Resources
- [geoJSON US States and Counties](https://bubinga.co/geojson-us-states-and-counties/)
- [National Population Totals Datasets: 2010-2016](https://www.census.gov/data/datasets/2016/demo/popest/nation-total.html)
- [Basic US State Map Tutorial](https://gist.github.com/michellechandra/0b2ce4923dc9b5809922)
- [D3 Scale Chromatic](https://github.com/d3/d3-scale-chromatic)
- [D3.js Slider Examples](http://thematicmapping.org/playground/d3/d3.slider/)
