# My Radio Astronomy Utilities
This repository contains those Jupyter notebooks that are useful for HI observations. So far these are two notebooks: one that helps plan observations and one that helps to semi-automatically reduce HI observations from the Australian Telescope Compact Array (ATCA). 

The notebook to plan observations shows how to make visibility plots over 24h including the sun. 

The semi-automatic HI data reduction pipeline is based on Miriad and thus on mirpy, which only works with Python 2.7. The pipeline allows you to reduce all observations within one project, if the data has been sorted into folders of single observations. A folder of a single observation should include data for bandpass calibration, for phase calibration and the on-source science data. 
