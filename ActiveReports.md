### Current Active Data Repository: 
Here is a list of current datasets/projects. Most projects have data taken directly from Socrata API. Thus a data repository is not needed; however secondary tables would need to be pyshically created

**Note:** Open the interactive reports on a desktop browser

1) [Saint Paul Traffic Stop Dataset](https://information.stpaul.gov/Public-Safety/Traffic-Stop-Dataset/kkd6-vvns)
* Last Report Made: May 6th, 2019 | Update Rate: Annual
* Description: Traffic Stop Data initiated by Saint Paul Police from 2001 to 2018. More details for reason of stop provided after 2017.
* Row Entry: Case Number | Geo-Identifier: [Police Grid](https://information.stpaul.gov/Public-Safety/Saint-Paul-Police-Grid-Shapefile/ykwt-ie3e) / Police District Grid
* Initial Data-Clean: No
* Interactive Report/Notebook: [Frogtown/Saint Paul Traffic Stop Report; 04/07/19](https://nbviewer.jupyter.org/github/sustainabu/OpenData_Saint_Paul/blob/master/_Frogtown%20Traffic%20Data/Saint%20Paul%20Traffic%20Stop%20Report_Presentation.ipynb)

2) [Saint Paul Crime Incident Dataset](https://information.stpaul.gov/Public-Safety/Crime-Incident-Report-Dataset/gppb-g9cg)
* Last Report Made: September 13th, 2019 | Update Rate: Bi-monthly
* Description: List all Crime Incidents since August 14, 2014 
* Row Entry: Incident Number | Geo-Identifier: [Police Grid](https://information.stpaul.gov/Public-Safety/Saint-Paul-Police-Grid-Shapefile/ykwt-ie3e) / [Neighborhood](https://information.stpaul.gov/City-Administration/District-Council-Shapefile-Map/dq4n-yj8b) 
* Initial Data-Clean: Messy
* Interactive Report/Notebook: [Frogtown, MN, Crime Map 09/13/19](https://nbviewer.jupyter.org/github/sustainabu/OpenData_Saint_Paul/blob/master/_Frogtown%20Crime_Map/FG_Crime_Map.ipynb)

3) [Saint Paul Vacant Buldings Dataset](https://information.stpaul.gov/Buildings-Housing-Economic-Development/Vacant-Buildings-Dataset/fgbn-288b)
* Last Report Made: May 7nd, 2019 | Update Rate: Monthly?
* Description: List all the current "vacant" buildings based on their starting vacancy date. The report will look different depending on time it is run.
* Row Entry: Vacant Building | Geo-Identifier: [Ward](https://information.stpaul.gov/City-Administration/Council-Ward-Shapefile-Map/tseu-m286) / [Neighborhood](https://information.stpaul.gov/City-Administration/District-Council-Shapefile-Map/dq4n-yj8b) / Census tract 
* Initial Data-Clean: Yes
* Interactive Report/Notebook: [Saint Paul, MN, Vacant Building Report; 05/06/19](https://nbviewer.jupyter.org/github/sustainabu/OpenData_Saint_Paul/blob/master/_Saint%20Paul%20Vacant%20Building%20Report/Saint%20Paul%20Vacant%20Building%20Report.ipynb)

4) [Saint Paul Voting/Election Dataset: 06/24/19](https://www.sos.state.mn.us/media/2641/registered-voter-list-request-form.pdf)
* Last Report Made: July 31st, 2019 | Update Rate: Static (till new data is provided)
* Description: Looks closely at the Saint Paul voting to show inequities in local elections. The report has a qualitative section providing an explanation for inequities as well as appropiate solutions. It campaign orientated.
* Row Entry: Precinct | Geo-Identifier: [Ward](https://information.stpaul.gov/City-Administration/Council-Ward-Shapefile-Map/tseu-m286) / [Precinct](https://www.sos.state.mn.us/election-administration-campaigns/data-maps/geojson-files/) 
* Initial Data-Clean: No
* Interactive Report/Notebook: 
    * [Press Friendly/Data Only: Saint Paul 2015 City Council Voting Report; 06/24/19](https://nbviewer.jupyter.org/github/sustainabu/OpenData_Saint_Paul/blob/master/_Saint%20Paul%20City%20Council%20Election%20Analysis/Saint%20Paul%202015%20City%20Council%20Voting%20Report_06-24-19%20%5BData%20Only%5D.ipynb)
    * [(Full Report) Saint Paul 2015 City Council Voting Report; 06/24/19](https://nbviewer.jupyter.org/github/sustainabu/OpenData_Saint_Paul/blob/master/_Saint%20Paul%20City%20Council%20Election%20Analysis/Saint%20Paul%202015%20City%20Council%20Voting%20Report_06-24-19.ipynb)
