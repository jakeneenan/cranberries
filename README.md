# How's the cranberry market in Massachusetts?

For our first project, we were supposed to focus on something we missed from home. I did not, so I decide to do so for my second one. Growing up in Massachusetts, I drove by cranberry bogs almost daily. I used USDA data and talked to to the Cape Cod Cranberry Grower's Association to get a sense of how the industry is doing and how it's preparing for climate change. You can see the final product [here](https://jakeneenan.github.io/cranberries/).
 
 ## Findings
 
Cranberry growers in the state are abandoning older bogs that are less productive and focusing their efforts on more recently planted ones, leading to an almost 8% drop in the state's bog acerage. This has allowed them to keep the fickle crop relatively stable during an historic drought. Climate change is already shortening the growing season, putting more pressure on them to invent new ways of getting the most berries possible from their bogs.

## Data collection

The USDA National Agriculture Statistics Service publishes the data I used [here](https://quickstats.nass.usda.gov). It contains the price of cranberries in Massachusetts going back to 1901, and more detailed statistics about land use and yield going back to 2007.

## Data analysis process

Technically, it was a relatively easy lift here. Just getting familiar with the USDA's data dictionary and using ggplot for some exploratory data viz. After doing that, I had a bunch of charts I couldn't interpret because I know very little about cranberries. Talking to someone from the CCCGA was super helpful and allowed me to properly frame the story and visuals.

## New skills

I took a couple steps back with the graphics and focused on making something simple and informative. I'm learning less is often more with reader-facing visualizations.

## Further work

Massachusetts actually publishes shapefiles that allegedly have cranberry bog parcels marked. I checked this with geopandas and it doesn't appear to actually be the case -- the use codes the correspond to a cranberry bog on the state's website are nowhere to be found. I'd like to talk to someone at the Massachusetts Bureau of Geographic Information about this; a map would have been nice to have.

It would also be interesting to complile statewide average temperature and precipitation data to see how it compares to cranberry production over time. This data is often localized in time and geographic area, and I'm not sure how to go about finding a state average from this.
