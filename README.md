# responsive-typography-demo
Simple demo showing scalable responsive typography using rem and em units

Adjust your browser window size to see the text and the margins adjust proportionally. Check out the style block in the head to see what's going on.

Here's how it works:

- Use a mobile-first responsive schema, where there's a global body tag and then an override for each device size
- For each device size, set html root as a proportional percentage value (or use the default values and breakpoints provided)
- Set margins and paddings in "rem" units - these are consistent everywhere on your page
- Set font sizes with "em" units - these can be cascaded down
- To scale ALL text and margins on ALL devices, adjust the master body font-size in "em" units
