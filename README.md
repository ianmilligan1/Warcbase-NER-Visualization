#Warcbase-NER-Visualization

![Example output from both files put together](images/Finding-Aid-Example.png)

## Locations

For more information, see my full blog post ["Using Mathematica to Plot Locations Mentioned in Web Archives."](http://ianmilligan.ca/2015/08/05/using-mathematica-to-plot-locations-mentioned-in-web-archives/)

We've been generating arrays of location frequency data with [warcbase](https://github.com/lintool/warcbase) - see our section on [named entity recognition](https://github.com/lintool/warcbase/wiki/Pig:-Named-Entity-Recognition-(on-a-cluster)) - but a trick has been making this useful.

I decided to see if we could make the NER speak to Wolfram|Alpha, thanks to *Mathematica*'s new functionality. The results were interesting:

![Example output from location-frequency-to-visualizations.nb](images/Conservative-Frequency-Map.png)

## People

![Example output from frequency-person-to-visualizations.nb](images/person-ordered.png)

This program takes the top person entities, counts them, extracts images from the Wolfram|Alpha database, and then assembles them in a weighted montage. It's a useful way at a glance to see major figures in a collection.

## Relevant Files
**Conservative-200902-loc-freq.txt**: This is an example of an output file from the NER process. There are some for the Greens and NDP as well.  
**Location-Frequency-to-Visualizations.nb**: The Mathematica notebook for Location-Frequency.
**Frequency-Person-to-Visualizations.nb**: The Mathematica notebook for person frequency.