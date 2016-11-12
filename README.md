# *Almost* recreating The Great Discontent layout with flexbox 

## Key Findings:
- Flexbox has its limitations like any other CSS layout technique.
- Making background images scale well requires some patience and math. 
- Controlling font size based on a container’s width takes a hint of JS.
- Pseudo-elements are a thing and they’re super useful.

[The Great Discontent site](http://thegreatdiscontent.com/) is designed and developed by [Ryan Essmaker](https://twitter.com/ryanessmaker) and [Andy Rossi](https://twitter.com/AndrewRocco). The homepage features a responsive grid of article “tiles” to show off the publication’s latest interviews. The tiles are a mix of beautiful imagery and quotes. 

I’m a big fan of TGD so I wanted to see if I could replicate the  homepage design myself (without peeking too much) and investigate the CSS techniques they used to make it look so good. Here are the highlights.

## The Navigation

The nav had one point of reassembly when the viewport reaches `min-width: 800px`.



