# Code to find mid eclipse times and calculate OC values for eclipsing binary systems

This repository hosts code and sample data that was used as part of a project to gain more data towards confirming the detection of circumbinary planet candidates. There are three main notebooks presented (data_processing, y, and z) that each represent a different stage of the data collection or analysis process. Additionally, there is some sample data found in (place) to make running and exploring this code simpler.

The first notebook covers the data collection and cleaning process. Here, we download lightcurves for our different sources, as well as compile data from other telescopes to help increase our baseline and sensitivity to long term trends. The notebook also covers the normalisation of these lightcurves from different telecscopes to allow for the creation of one long lightcurve. The product of this notebook is the lightcurve files found in Data/combined_lightcurves.

The second notebook covers our process for modelling the eclipses within these systems. These eclipse models will be used to fit our eclipses in the lightcurves to obtain mid eclipse timing.

The third notebook is used to calculate mid eclipse times and compare them to expected mid eclipse times to generate OC values.

