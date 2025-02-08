# DEAD_1.0_microclimate

This repo contains shared documentation, results, and code for microclimate data compilation and analysis from the microclimate dataloggers in the Decomposition Experiment Across Drylands (DEAD) 1.0 experiment. Data loggers were deployed in concert with a litterbag experiment. Loggers were placed in otherwise empty litterbags (fiberglass mesh, 1 mm mesh size) and secured to the soil surface with sod staples.

Loggers were placed in five sites in the five North American deserts from Nov 2020-Nov 2022. Loggers were initially iButtons (temperature and RH), but a high failure rate occured early on with these loggers. _There are some iButton data but these have not yet been included in the data compilation._ We switched to Kestrel Drop loggers (temperature and RH) in ~March 2021, but there was some among-site variation in when these were deployed. There were some futher challenges with the Kestrels in that the company indicated >1 year battery life but in fact in was often shorter than the 3 months between litterbag collection times. This caused data gaps, particularly early on when we assumed longer than actual battery life. There were also issues with logger failure when soil entered the loggers, disrupting the battery connections. 

Additional Hobo Onset loggers (temperature only) from Moab USGS were installed in some blocks. Many of these disintrigated with time. (HT needs to check with USGS to see if any data were salvaged.)

Loggers followed the litterbag locations, with litterbags placed in five blocks at each site. Blocks were groups of the dominant shrub and intershrub patches. Thus, the goal was to have 5 shrub and 5 intershrub (= bare) patch loggers for each site.

The sites are:
Region	                  Site	                                            Shrub species	                          Site PI
Sonoran Desert	          Desert Botanical Garden	                          Larrea tridentata	                      Heather Throop
Chihuahuan Desert	        Jornada Basin LTER	                              Larrea tridentata	                      Jennie McLaren 
Colorado Plateau	        USGS Global change manipulation site at Moab, UT	Atriplex confertifolia	                Sasha Reed
Mojave Desert	            USGS common garden at Ridgecrest, CA	            Larrea tridentata	                      Todd Esque and Lesley DeFalco
Great Basin Desert	      Reynolds Creek Exp Watershed	                    Artemisia tridentata	                  Marie-Anne de Graaff 


Code is structured to use data from a Dropbox folder owned by Heather Throop. Access must be granted by Heather.

The project is structured with the following folders:
doc: contains text files and other documentation for the project
results: contains output from analyses such as figures.
src: source code (.R or .qmd) for analyses in R

The data levels are as follows:
L0 data - original data from the Kestrel loggers
L1 data - data from all loggers at all sites combined into a single file, site and location information added, date formatting corrected
L2 data - data file cleaned to remove duplicates logs, date and time columns added

Contact:
Heather Throop (heather.throop@asu.edu)

