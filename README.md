# Datavisual

Lin He

Bad Graph Critique 

I found this bubble chart in D3 example site. 

This bubble chart is very messy with different size and colors. It's a hierarchical analytical chart of the Flare library with different size of bubbles indicating the usages of different elements or functions in the library. 

Flare is an ActionScript library for creating visualizations that run in the Adobe Flash Player. From basic charts and graphs to complex interactive graphics, the toolkit supports data management, visual encoding, animation, and interaction techniques. 

Here is the bubble chart:
It reads json file and generates the bubble chart in javascript. 
Everything is in the index.html file. 

I used node.js to run the server to show the index.html file.

I changed the graph to histogram and tree graph.

The graph is bad for the below reasons:
1.less perceptually-accurate than bar charts <br/>
2.the color is useless in such a bubble graph

The histogram shows the distribution of the size of those classes. 
The tree graph shows the hierarchical structures of classes and elements of the packages. 

The tree graph and histograms are more clear and easy to classify the structures of the library. 



