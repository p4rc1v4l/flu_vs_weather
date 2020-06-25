# flu_vs_weather
Project 1 repository. Try to correlate flu outbreaks with weather patterns.

1 Project Proposal.docx - initial proposal submitted for approval

# Original Data
'FluViewPhase2Data' - folder containing data downloaded directly from the CDC website: https://gis.cdc.gov/grasp/fluview/fluportaldashboard.html

'WEATHER_CSV' - folder containing data downloaded directly from the Weather Company website: https://www.wsitrader.com/

# Importing and Cleaning Notebooks and CSV exports
'2 ResamplingData.ipynb' - notebook using the WEATHER_CSV data to resample daily temperature data to weekly data and also combines all cities into one output file

'Complied_Weather.csv' - output CSV for temperature for all cities from previous file

'3 ILI Cases.ipynb' - notebook using the 'FluViewPhase2Data' to clean the ILI Totals by State and year and exports relevant columns

'4 Tested_Cases.ipynb - notebook using the 'FluViewPhase2Data' to clean the positive test totals by State and year and exports relevant columns

'4a Tested_Cases_2016-2020 NA.ipynb' - notebook using the 'FluViewPhase2Data' to try and sum the clinic and public health lab data but not in same form - NOT USED

'Data' - folder containing CSV exports from files 3 and 4 above

'5 Precip_V1.ipynb' - notebook using the 'WEATHER_CSV' data to resample daily precipitation data to weekly data and also combines all cities into one output file

'Complied_Weather_precip.csv' - output CSV for precipitation for all cities from previous file

# Analysis
'6 ILI_Cases_w_Weather.ipynb' - notebook combining 'ILI Totals for Deired States.csv' and 'Complied_Weather.csv' to look at relationships

'7 Tested_Cases_w_Weather.ipynb' - notebook combining 'Total Positives for Desired States.csv' and 'Complied_Weather.csv' to look at relationships

'8 precip_comparison.ipynb' - notebook combining 'ILI Totals for Desired States.csv' and 'Complied_Weather_precip.csv' to look at relationships

'Plots' - folder containing all the plots exported from files 6, 7, and 8 above

# Final Results
'9 Weather and the Flu_Final1.pptx' - Final PowerPoint presentation showcasing results

'10 Summary Report.docx' - Final Summary of results
