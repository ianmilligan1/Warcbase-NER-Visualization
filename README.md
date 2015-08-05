#Warcbase-NER-Visualization

We've been generating arrays of location frequency data with [warcbase](https://github.com/lintool/warcbase) - see our section on [named entity recognition](https://github.com/lintool/warcbase/wiki/Pig:-Named-Entity-Recognition-(on-a-cluster)) - but a trick has been making this useful.

I decided to see if we could make the NER speak to Wolfram|Alpha, thanks to *Mathematica*'s new functionality. The results were interesting:

![Example output from this file](Conservative-Frequency-Map.jpg)

## Files You'll Find Here
**Conservative-200902-loc-freq.txt**: This is an example of an output file from the NER process. There are some for the Greens and NDP as well.  
**Frequency-to-Wolfram-Viz.nb**: The Mathematica notebook.  
