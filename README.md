# Responsive Typography Demo

This is a a simple demo showing scalable responsive typography using rem and em units.

Open index.html in your browser and adjust the window size to see the text and the margins adjust proportionally. Then view the source and check out the embedded style block to see what's going on.

Here's how it works:

- For extra small devices, let html be set to font-size:100% (conveniently, this is the natural default)
- For each tier of larger devices, set the html font-size to a slightly higher percentage
- Style margins and paddings with "rem" units. 1 rem = the percentage you set
- Style element with "em" units. These can cascade up or down as needed
- To scale ALL text and margins on ALL devices, adjust the master body font-size in "em" units

In this demo we're showing exaggerated sizes:

- xs = 100%
- sm = 125%
- md = 150%
- lg = 175% (1rem = 28px)
- xl = 200%

This schema is more practical: 

- xs = 100%
- sm = 107.5%
- md = 115%
- lg = 125% (1rem = 20px)
- xl = 135%

Under this practical "125%" schema, on large devices (desktops) a "rem" unit breaks down nicely:

- .25rem = 5px
- .5rem = 	10px
- .75rem = 15px
- 1rem = 20px
