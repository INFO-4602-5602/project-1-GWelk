Project 1: Ancombe's quartet
Authored by: Gena Welk
Due: Feb 14, 2018
Submitted: Feb 14, 2018
INFO 5250: Information Visualization with Danielle Szafir

Collaboration:
I did not work with anyone.  Occasional questions and guidance was received from Supriya, Evan, and Danielle.

Research:
Lots of Googling led me to bl.ocks.org, stackoverflow.com, chartio.com, d3noob.org - but these were for guidance and their code was copied.
Additionally, I consulted Scott Murray's book, "Interactive Visualization for the Web".

Part 1: Interpreting Data
-imported D3 in head of html code
-used XAMPP as a local server
-uploaded 4 datasets via D3
-used skeleton code to verify upload via CheckDataset function

Part 2: Building Scatterplots
-created a scatterplot
-created x and y axes, with labels
-used d3.max function to create scale
-dataset was loaded for use in this section
??-(Isn't  there a way to load the dataset outside this section and refer back to it?)
??-I wanted to create the axes beginning at number 0. (unsuccessful).  I also screwed something up with the labels (because they did not print in increments of one)
-notable learning in this section: changing datatypes to int and float (instead of strings)

Part 3: Building Linegraphs
-similar to scatterplot in part 2
-brought in the data anscombe_I (again)
-created x and y axes, with labels
-used d3.max function to create scale
??-I wanted to create the axes beginning at number 0. (unsuccessful)
-notable learning in this section: data.sort function
-notable difference in part 3: var line = d3.line().x(function(d) {return x(d.x);}).y(function(d) {return y(d.y);});

Part 4: Interaction
-mouseover points changes it to red (successful)
-clicking on a point (unsuccessful).  I was successful in using "on mouseclick" to trigger an event (printing "SOMETHING" to the screen in the id of "ScatterLabel") I tried to use ".text(function(d){return x(d[xVal]);})" on line 274 but this was wrong.
-because of my unsuccessful on click code, the axes broke and did not print to the screen

Part 5: Building Multiple Charts
-created 4 scatterplots with individual labels using different div tags
-incomplete: side by side.  I tried to do this by creating a container class in the .css file, but did not know what to do next
??- I wanted to have the x-axis start at 0.  was not successful.
??- I wanted to scale down so the chart was smaller and could be compared next to the others.  I didn't get that far.

Bells:
None.
:(

Whistles:
None.
:(
