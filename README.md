These jupyter notebooks layout an assessment of the impact of the Mississippi River Plume barrier layer on the response of the upper ocean to Hurricane Ida and Ida's intensity. This work is the basis for the second chapter of my M.S. thesis. 

The number at the start of the notebook filenames indicates the position of each notebook in the workflow of the project.

This work uses the python implementation of the 1D Price-Weller-Pinkel (PWP) model provided by https://github.com/earlew/pwp_python_00 .

The initial conditions for the model are dervied from underwater glider observations available through ERDDAP.
The boundary conditions are dervied from output from NOAA's High Resolution Rapid Refresh model. I have included the forcing data used in the experiments in this study (./data/HRRR_Ida_windsOnly_1629339767_08-25-00_initime.nc). The HRRR output used in this study was stored by RUCOOL so those individual files are not included but the code used to process that output into the forcing for PWP is included (./notebooks/02_pull_forcing.ipynb) for posterity.

I have included a list of references for anyone interested in barrier layer research.
