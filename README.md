# RangeFinderCal

Quickly developed this in LabVIEW over a weekend to help a friend gather simutaneous data from multiple range finders attached to an Arduino for his Masters Thesis.

The Arduino looks like a serial interface to the host computer. To start look up the com port from the devices list (look at the Universal Serial Bus devices list in the Device Manager) and set the com port in the set up portion of the GUI. The Arduino should be already programmed to acquire from the attached devices in its main loop.

Going to the next tab, if successfully connected, the graphs should start updating and reflect any changes in movement. Note that the acquired data is averaged. 

From there you can acquire the data and save it to a CSV file to be viewed in a spread sheet viewer for convenience.

ToDO:

* Add user persistance such as configuration items, screen position. 
* Add diagnostic logging
* Refine the averaging code.

