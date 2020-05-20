# opioid use in Indiana
In this project, I use the opioid sales data from the [Washington Post](https://www.washingtonpost.com/graphics/2019/investigations/dea-pain-pill-database/) to find out what risk factors are significantly associate with opioid use in Indiana  <br />
The assocciated risks factor are mainly collected in [bureau census](https://www.census.gov/library/publications/2011/compendia/usa-counties-2011.html#POP) and a few other sources.  <br />
By using the spatial temporal model for data from 2006-2011, I was able to find that unemployment rate and white proportion are the most significant risk factors. Counties that have higher unemployment rate consume higher opioid on average, and counties that have higher white population consume less opioid on average.  <br />
Using the model, I also predicted the average opioid use in Indiana in 2012 and get MSE of 28.2. <br />
The detailed report is in file [report.docx](https://github.com/oceancode1997/opioid-use-in-Indiana/blob/master/report.docx?raw=true) <br />
The data I collected is in file [data.rds](https://github.com/oceancode1997/opioid-use-in-Indiana/blob/master/Data.rds?raw=true). The data included: <br />
  - opioid_used_per_person = the amount of opioid used by person in each county from 2006-2012. <br />
  - coordinates: the coordinates of 92 counties in Indiana. <br />
  - spatialdata: the spatial predictors. <br />
  - SpatialTemporal: the Spatial temporal predictor. <br />

The detailed code is in R file: [project opioid.Rmd](https://github.com/oceancode1997/opioid-use-in-Indiana/blob/master/project%20opioid.Rmd) or html file [project_opioid.html](https://github.com/oceancode1997/opioid-use-in-Indiana/raw/master/project_opioid.html)
