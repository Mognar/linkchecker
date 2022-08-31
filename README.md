## linkchecker
Jupyter notebook to check MPs web addresses are still working

# Packages required for this script to run
requests
pandas

These pacakges only need to be installed once, the first time you use them. To do this, add a new cell to the top of the notebook and run the following code:
!pip install requests
!pip install pandas

This will install the pacakges on your device. 

# How to extract links to check
Requires a download of Members and their web addresses to a spreadsheet in the first instance. 
There should be an active spreadsheet named "YYYY MM Members web addresses for link checker script" in the Member data exports folder on SharePoint. 
Open this spreadsheet and refresh the query to update the list, then save a copy to your local device, in the same folder that you've saved this Jupyter script. 
Ensure the name of the spreadsheet in the script matches the actual name of the spreadsheet before running the script. 




