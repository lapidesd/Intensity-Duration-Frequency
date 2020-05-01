# Intensity-Duration-Frequency
A program to calculate decreasing power law IDF function

[![DOI](https://zenodo.org/badge/259444778.svg)](https://zenodo.org/badge/latestdoi/259444778)

The jupyter notebook IDF_calculation.ipynb contains a python program which demonstrates how to calculate a power law IDF curve from readily available information. The first example is for the Walnut Gulch Experimental Research Watershed, for which IDF datapoints can be found at https://www.tucson.ars.ag.gov/unit/Publications/PDFfiles/2249.pdf. The second example is for Las Reliez Creek in Contra Costa County, CA. Depth-Duration-Frequency data can be found at https://www.contracosta.ca.gov/5745/Documents-and-Standards. From Depth-Duration-Frequency charts, we tabulated depth-duration data at 5, 10, 15, 30, and 60-minute intervals. These were then converted into intensity-duration data by dividing the depths by the durations for each data point. Intensity-duration data were fit to a decreasing power law function, and the resulting values for each return period are printed with uncertainties, and the curves are plotted together with the tabulated data.

For those new to jupyter notebook:

Jupyter notebook is an open-source python platform. The program is separated into blocks, which should be run sequentially. The first block contains dependencies for the program. They can be installed using the command line: pip install *dependency*. The second block contains the data collected from online sources for Walnut Gulch and Las Reliez respectively. The third block converts the depth-duration data into intensity-duration data. The final blocks solve for IDF curves and display the results for Walnut Gulch and Las Reliez separately.
