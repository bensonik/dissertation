5. Predicting Seasonal Migration
================================

The presence of seasonal migration in a species’ life history can
obviously alter distribution greatly. As a species alternates between
foraging, breeding, calving or migratory behaviors response to the
environmental is likely to vary. Accounting for these spatial and
behavioral disparities is commonly done by building separate seasonal
models to represent the different of habitats (Redfern et al. 2006).
Migrations however can last up to 4 months over 20,000 km distances in
the case of the grey whale. Models describing them as present over the
entire range during that period would be insufficient for planning
purposes. The general timing and broad locales are often available in
natural history and scientific literature. Surprisingly I could not find
a single species distribution model for cetaceans that explicitly
includes migration.

Most papers which discuss migration and species distribution modeling
are modeling the long term shift in distribution, typically poleward,
imposed by climate change (Guisan and Thuiller 2005; Robinson et al.
2011), and not the seasonal migrations common to megafauna. Mechanistic
species distribution models have been suggested (Kearney and Porter
2009; Robinson et al. 2011) but are complicated with energy and mass
balance equations using parameters often difficult attain. Complex
Markov models have been used with bird data to model bird migrations and
trajectories (Sheldon et al. 2007). A simpler method is possible and
desirable for easily providing marine stakeholders and the general
public (e.g. through OBIS SEAMAP or GROMS ) with a best guess view of
what whales are where when. In its simplest form, separate models would
be fit from observations separated out seasonally and spatially to
distinguish the breeding, foraging and 2 migrating habitats. For the
migratory habitat, time would be included as an interaction term for all
environmental variables. Another variable could be introduced which
measures distance along the axis of the median path, or straight line
from the centroids of the breeding and foraging grounds. A significant
fit for the interaction with this linear predictor would provide a clear
description of where the whale is expected to be on its journey. Using
the distance from this median line should give an idea of how widely
dispersed the animals are along the way. If using a GAM then to model
this interaction term, then it would be a bivariate smoother which could
expand and contract along the axis. Compositing these models together
could then provide a simple time-varying habitat model incorporating
migratory movement.

I propose to do this with the North Atlantic right whale (Eubalaena
glacialis) since data is easily obtained through OBIS-SEAMAP over the
entire species range and existing datasets are available for habitat in
the Gulf of Maine foraging grounds (Best et al. In Revision; Department
of the Navy (DON) 2007) and calving grounds off Florida (Good 2008), as
well as comparison with migratory model based on telemetry data (Schick
et al. 2009). Kenney et al. (2001) conceptualized a hierarchical sensory
model for right whales to hone in on prey and navigate between summer
foraging grounds in the Gulf of Maine and winter calving grounds off
Florida, but fell short of postulating specific cues to initiate
migration. Past years of observations and environmental data could be
mined to explore a more specific environmental cue than date. This would
enable predictions of the onset of migration. Other unmeasurable
factors, such as satiation or hunger, are likely candidates, perhaps not
inferable by environmental proxy.

References
==========