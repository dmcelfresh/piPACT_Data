# piPACT_Data
Data analysis software for the 2020 PiPACT independent project (run through MIT BWSI).
Written in Python3 and exported as a Jupyter Notebook file.
There are two parts to this code. The first will prompt the user for a filepath condtaining a .csv document. If the filepath is valid, the code will generate a Pandas dataframe along with other useful information. This information includes: the total number of scans, the unique addresses (and how many there are), the amount of time the scanner collected data, and the maximum, minimum, mean, and standard deviation values for both TX Power and RSSI. This code can be run with multiple files, but only one at a time.
The second will prompt the user for various .csv files and distances. The RSSI values will be extracted from each file and combined with that file's seperation distance to create a scatter plot. This plot will show a general trand between RSSI values and the distance between two devices given the constraints of the experiment.

To use, download the .ipynb file and open it in Jupyter Notebook. Run the importation cell first, then choose which cell you would like to run next. The code will prompt you for filepaths and other information to generate the statistical and graphical results.
