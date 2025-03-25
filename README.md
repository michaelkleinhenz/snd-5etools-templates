# SnD Templates for 5eTools Data Sources

This is a template to display 5eTools monsters/items/spells in the 2025 format. 

# Installation

Follow these steps to install the template(s):
* Download the source package for 5eTools from the 5eTools GitHub repository. You can find the current GitHub repository link on the 5eTools website at https://5e.tools/ (look at the FAQ section on the main page)
* Unzip the source package and retrieve the `data` directory. This contains the data we want to import as a data source in SnD.
* Open SnD and import the file `items.json` and the directories `bestiary` and `spells` from the `data` directory retrieved above. For this, enter the `Data Sources` tab in SnD and use the import feature on the top right to import. Remember the names for the data sources you set during the import.
* Install the templates in this repository, then enter the `Templates` section in SnD, open one of the newly installed templates, click on `Edit` on the top, select `Data Sources` in the template editor menu. Remove the existing data source and add your imported data source matching the template (bestiary, items, spells). Click `Save`.

This will enable the templates for use with the imported data from 5eTools.
