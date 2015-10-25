# Responsive Typography Demo

This is a a simple demo showing scalable responsive typography using rem and em units.

See it live here: http://dylanized.github.io/responsive-typography-demo/

Open the page in your browser and adjust the window size to see text, margins and padding adjust proportionally. Then view the source and check out the embedded style block to see how it's done.

Here's the important details:

- For small phones (xs-sized devices), let html be set to font-size:100%. (conveniently, this is the natural default)
- For each tier of larger devices, set the html font-size to a slightly higher percentage. See the lists below for some ideas.
- Style margins and paddings with "rem" units. The size of 1 rem is determined by the percentage you set.
- Style text elements with "em" units. These can be nested to scale up or down as needed.
- To scale ALL text and margins on ALL devices, adjust the master body font-size in "em" units.

In this demo we're showing exaggerated sizes:

- xs = 100%
- sm = 125%
- md = 150%
- lg = 175% (1rem = 28px)
- xl = 200%

A more practical schema would be:

- xs = 100%
- sm = 107.5%
- md = 115%
- lg = 125% (1rem = 20px)
- xl = 135%

FYI when size is set to 125%, a "rem" unit breaks down nicely:

- .25rem = 5px
- .5rem = 	10px
- .75rem = 15px
- 1rem = 20px

Questions? Feedback? find me @ http://twitter.com/dylanized