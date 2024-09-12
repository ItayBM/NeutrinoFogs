Files and Folder:
The main two files are a mathematica notebook in the spectra folder, and an ipython notebook. I will first describe those two, and then the rest alphabetically.

NeutrinoFogElectroWIMPs.ipynb is a python notebook that reproduces the results of the paper. One does not have to have NEST to run it, since we saved things that were already ran in order to make it accessible to all. 

Also, inside the Spectra folder, the DoS1S2Analyses.nb file allows one to run event by event simulations using saved NEST data, or alternatively simulate WIMP events and background spectra. 

Detector_G3new.hh:  is a NEST detector file (except some names of variables are changed), identical to the standard LZ file. One can use either this one or the NEST one.

discoveryexclusiondict.pkl: is a pickle file containing the comparisons of different detection/exclusion methods. (see the ipython notebook to run this one)
dRdER$Max.txt: A file with WIMP dR/dER under a certain astro model
dRdER$MB.txt: A file with WIMP dR/dER under a certain astro model (the fiducial one)
dRdER$Min.txt:A file with WIMP dR/dER under a certain astro model 
OtherNuNRBkg.csv is the background for the non-solar neutrino NR events. See ipython notebook for usage.
pythonS1Data is the S1 data needed for the ipython notebook. 
pythonS2Data is the S2 data needed for the ipython notebook. 
readme.md is this file
RnContaminationERBkg.csv is the Radon contamination ER background for the notebook (not used in the paper, but available if needed).
SolarNuER.csv is the background from ER events from solar nu (see ipython for usage). 
SolarnuNRBkg.csv is the background from ER events from solar nu (see ipython for usage).
Spectra folder has the necessary data to run simulations on mathematica, as well as the aformentioned mathametica file.