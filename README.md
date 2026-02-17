# Code to find mid eclipse times and calculate OC values for eclipsing binary systems

This repository hosts code and sample data that was used as part of a project to gain more data towards confirming the detection of circumbinary planet candidates. There are three main notebooks presented (data_processing, model_creation, and mid_eclipse_timing) that each represent a different stage of the data collection or analysis process. Additionally, there is some sample data found in (place) to make running and exploring this code simpler.

The first notebook covers the data collection and cleaning process. Here, we download lightcurves for our different sources, as well as compile data from other telescopes to help increase our baseline and sensitivity to long term trends. The notebook also covers the normalisation of these lightcurves from different telecscopes to allow for the creation of one long lightcurve. The product of this notebook is the lightcurve files found in Data/combined_lightcurves.

The second notebook covers our process for modelling the eclipses within these systems. We use the lightcurves generated in the first notebook to generate eclipse models, widths, and timing. The product of this notebook is a file called eclipse_models.csv that contains the necessary data to find the mid eclipse timings for the entire lightcurve.

The third notebook is used to generate windows around expected mid eclipse times and then find and calculate the mid eclipse times of all eclipses present within the lightcurve. These timings are then used to generate OC values which can be plotted to show the time evolution of the source. The product of this notebook are tbales containing OC values and various plots showing the eclipse timing process and the OC values themselves.

On top of the notebook, a folder named Data contains various data products that are helpful for running this code. The first 2 notebooks create files that are written to Data, so take care when running them to not override any existing data. As is, Data contains all the information necessary to run all notebooks without any additional data or code. There is also a file containing a list of packages and versions used by this code (environment.yml) to help with any debugging/dependency issues that may be caused from version conflicts. A non-exhaustive list of known issues is also given as a pdf, including descrptions of the problems, proposed solutions, and example plots.

If you have any questions/concerns about this code, please feel free to contact me at jfer9940@uni.sydney.edu.au. I'd be more than happy to help however I can :)

