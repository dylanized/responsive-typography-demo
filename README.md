# responsive-typography-demo
Simple demo showing scalable responsive typography using rem and em units

Adjust your browser window size to see the text and the margins adjust proportionally. Check out the style block in the head to see what's going on.

Here's how it works:

- For extra small devices, let html be set to font-size:100% (conveniently, this is the natural default)
- For each tier of larger devices, set the html font-size to a slightly higher percentage
- Style margins and paddings with "rem" units. 1 rem = the percentage you set
- Style element with "em" units. These can cascade up or down as needed
- To scale ALL text and margins on ALL devices, adjust the master body font-size in "em" units

In this demo we're showing exaggerated proportions:

- xs = 100%
- sm = 125%
- md = 150%
- lg = 175% (1rem = 28px)
- xl = 200%

More likely, you'd want to do proportions that are modest: 

- xs = 100%
- sm = 107.5%
- md = 115%
- lg = 125% (1rem = 20px)
- xl = 135%
