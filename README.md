# Energy label importer
This is an omporter to connect EP-online to a selection of households using BAG 'Verblijfsobject ID'.
It can freely used by anyone wanting to get their own selection of an EP-online database on energy labels.

The energy label files itself are too large to share but can be downloaded from https://www.ep-online.nl/PublicData


## Using the label importer

1. Download the energy label files from https://www.ep-online.nl/PublicData and store in a folder called *data_energy_labels*
2. Change the fileName in the f_readCSV function to the new name.
3. Get the required household IDs from BAG by using the PDOK plug-in in QGIS and load *verblijfsobjecten* for a selected area.
4. Copy the household IDs to the first column of the *residence_objects_template*
5. Run the model and click on the button
