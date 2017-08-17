The task is following:

-	Create matadata of a files in metadata repository (for excel file the process is quite similar to csv)

-	Read the data from files
	o	for HDI data you need perform filtering of rows which split list of countries to a sections (e.g. use tFilter for this)
	o	also the data in HDI file are pivoted by years, so split each record into rows using tSplitRow component

-	Join three datasets together using country names and year as join condition (tMap component)

-	Output the data in a single file with following columns: Country, Year, HDI_rank, HDI_value, number_of_cases, detection_rate
	o	Sort the data by HDI_rank, Country and year before writing it to file (tSortRow)

-	Provide me with a file and a sources (at the beginning of next session I’ll describe how to export your project)
