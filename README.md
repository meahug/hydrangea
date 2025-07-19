# What the flowers around us say about the earth beneath our feet
## Hydrangeas as a litmus test of the earth's soil

I started this project as a small Datawrapper map exploring hand-collected data in my neighborhood: hydrangea colors and their corresponding pH. (Aaron assigned his hand-collected data map in mid-June and I was waiting outside my polling place for 90min to vote in the mayoral primary. In my boredom, I noticed hydrangeas around me and thought about the soil beneath them that determined their petal color.) This ended up as a broader rabbithole exploration on regional soil pH across the country, and the specific soil sediments that exist in Brooklyn. I was also interested in historical geological events that may have caused these soil qualities to exist in the first place. 

Ultimately, I wanted to build a narrative about the plants around us carrying visual information. This information has a lot to tell us about the local ecosystem of our neighborhoods, and what geological events in the past helped shape this local ecosystem.

## Project findings

Upon collecting hydrangea colors and plotting them to soil pH, I noticed a few patterns. Potted plants had a higher pH, most likely due to being hand-watered, where potted soil increases more quickly to match the pH of the tap water being used. Overall, my hydrangeas skewed blue-purple, which is somewhat of an East Coast phenomenon where the soil is more acidic (overall, hydrangea color has a lot of local differences but follow regional soil pH patterns). 

Then, I dug into why certain regions of the US have different soil acidity. It was pretty difficult to find a working file for USA soil pH patterns but I eventually found a .tiff file of a soil pH dataset that I could import into QGIS and use a color ramp scale to depict pH at the national level. I matched the color ramp to the supposed hydrangea color that corresponds to the pH. This dataset was determined by spatial pattern recognition at a 100m scale using satellite data. I was hesitant to use a dataset using AI/pattern recognition, but upon reading into the methodology of the dataset, I discovered the soil pH data had an accuracy of 87%, which I learned (from Jeremy's class) is a fairly good accuracy rating for AI classification datasets overall. I couched this dataset with the word "approximate" to account for this margin of error.

## Data collection

## Data analysis


## New skills and approaches I learned through this project
Datawrapper(for the initial map and basemap styling), scrollytelling using the provided template, flexbox css, geojson.io (for plotting hydrangeas, pH and whether they're potted or not), QGIS (for creating the USA regional soil pH map using a color ramp and .tiff files, and for projecting the NYC boroughs using the correct projection), jupyter notebook (for checking my data and taking mean pHs of potted vs unpotted hydrangeas), Illustrator (not really a new skill for me, but customizing QGIS/SVG maps in Illustrator is somewhat of a new skill and Larry's tutorial was very helpful for this), assessing found dataset spatial recognition AI accuracy rates, and attempting to shape a concise narrative in a contained project + figuring out my journalistic tone (very new to me!).

## Things I'd like to try to do if I had more skills and time
- Veronica taught us about georeferencing the other day. I could've used georeferencing in QGIS for the terminal moraine & Laurentide ice sheet map - I did this by hand using illustrator to trace SVGs and comparing the New York State Museum pdf side by side with my NYC boroughs shapefile map. It was annoying to do!
- Crowdsourcing - Aaron had a very neat idea to allow other folks to survey the hydrangeas around them and submit their colors/pH through a collaborative MapBox survey and add them to the map. This would've been really cool - love some citizen science - but not quite sure how to do this yet.

Short description of your findings
Summary of the data collection process, with links
Overview of the data analysis process
A section about what new skills, approaches, etc you used, or where you grew the most
during the project
Data used for analysis – note that if your data is 100MB+, you can't host it on GitHub. That's fine,
just add the file to your .gitignore
Notebooks used for data collection and analysis
Your notebooks should include some Markdown cells at the top that explain what you're doing
in the notebook. Ideally you also sprinkle commentary/questions throughout the notebook.
A .gitignore (https://jonathansoma.com/fancy-github/organization/gitignore.html) file to keep out
any files you don't actually want in the project
A link to the project page (you can add a link in your README, or by clicking the gear icon next to
"About" on the right-hand side of your repo)