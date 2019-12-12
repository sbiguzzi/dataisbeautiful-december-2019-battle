# dataisbeautiful-december-2019-battle
submission for r/dataisbeautiful December 2019 battle

--Scope of challenge
  •	The challenge was to create a data visualization using the standard atmospheric data from 1976 found on this wiki page
    https://en.wikipedia.org/wiki/U.S._Standard_Atmosphere#1976_version.

--Files uploaded
  •	AtmosphereData.csv: The table I used to create the visualization
  •	AtmosphereWorkbook.twb: The Tableau workbook with the sheets and dashboard
  •	AtmosphereFinal.pdf: The Tableau dashboard exported as a pdf for submission

--Additional data
  •	I started with heights ranging from 0 to 85000 meters, adding additional rows for every 5000th meter.
  •	I added atmosphere the height limit for the troposphere, stratosphere, and mesosphere as separate rows if the limit was above a
    multiple of 5000 (I got this data from https://www.nasa.gov/mission_pages/sunearth/science/atmosphere-layers2.html).
  •	I then added additional landmark data for some famous height records by using Google.
  •	Finally, added a column to find the barometric pressure found at each height using the formulas from this wiki page
    https://en.wikipedia.org/wiki/Barometric_formula#Pressure_equations.

--Tableau workbook
  •	Added one field to make the different colored layer for each atmospheric stratum.
  •	Downloaded and edited clipart for each record.
  •	Created a title sheet, landmarks sheet, background color sheet, pressure line graph sheet, troposphere, stratosphere, and
    mesosphere text label sheets.
  •	Layered all the sheets on a dashboard and then saved it to a pdf.

--Explanation of final product
•	The final graph shows the increase in barometric pressure as the height increases, while showing different height records and the
  atmospheric layers.
