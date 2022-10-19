# assignment05
The code in assignment05.qmd utilizes crime data to summarize and map homicides and percent of arrests for each census tract in Chicago. Thus, the main goal of this code is to create two maps, one of homicides and one of the percent of arrests leading from homicides. A short paragraph commenting on the implications of the maps is also included. The code brings in crime data as well as shapefiles from Chicago's Data Portal, cleans and formats the crime data to only include information about homicides in the last 10 years, and creates the two aforementioned maps. Finally, the last portion of code illustrates how to use (tidycensus) to bring in data that matches data brought in by a URL string with packages httr and jsonlite. The assignment05.qmd is the Quarto file where all of the code was written and analysis conducted. That .qmd file is used to generate assignment05.html, which is the main report. The .gitignore file lists the file types to be ignored. You will need to include a folder in your working directory, called something like /data, as well as the crimes-reduced.csv found on Canvas under the Assignment05 page to run. You will also need to download and extract the Chicago Census shapefile and place the full extracted folder in your /data folder. You may also need a Census key to bring in the data for #5. Once you have the .csv and shapefiles in a /data folder in your working directory and the specified packages loaded, the code will reproduce assignemnt05.html
