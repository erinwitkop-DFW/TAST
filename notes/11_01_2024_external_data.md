## Nov. 1, 2024 

# Goals:
1. Finish downloading sunrise sunset
2. Download tides and flow data


# Notes:
1. Finish formatting sunrise sunset data   
    - got the data downloaded and formatted into time format for sunrise sunset

2. Download tides and flow data
    - Use link from James: https://tides.net/washington/2306/?year=2024&month=08
    - This link lists a tide chart for Puget Sound, Rocky Point, Eld Inlet Tides but it is a graph and not raw data
    - switched to using NOAA tide gauge data because it allows you to download text data for tides
    - https://tidesandcurrents.noaa.gov/noaatidepredictions.html?id=TWC1115&legacy=1
    - Downloading data month by month from May - end of August as a text file 
    - export as 24 hour clock
    - after individually exporting going to combine all into single excel document 
    - was able to correctly load the tide data 

3. Load TAST data

    - The TAST data was included on the "Master detection file_TAST.xlsx" spreadsheet. 
    - There are fewer dates that I was anticipating, so I asked James if this was the full study period and what the full study period dates were
    - There were also blanks in the time on/off data for 6/2 and 6/3, I'm assuming thats because the TAST was on continously but I'm checking with James 

4. Load CFS data
    - here is the data source from James for the CFS: https://waterdata.usgs.gov/monitoring-location/12080010/#parameterCode=00065&period=P7D&showMedian=false 
    - data from USGS 
    - Again download data from May-Aug
    - downloaded data for the past year as a text file
    - Copying and pasting into a spreadsheet
    - downloaded data on Discharge in cubic feet per second and put into excel, need to work on formatting another day 

5. Notes from check-in with James

    - on the Master file pivot table there are values that are incorrect and it will mishear pings and record it as real data 
    - tag bio data tab shows all the fish that were actually tagged, by week 26 the lake inlet is done and the lake outlet is done 
    - there are several tags that are definitely outliers and are not a fish
    - week 30 was the end, everything after week 24 should be zeros with no fish detected 
    - Week 24 was TAST off, they pulled the tast, when there is no data that means the tast just wasn't in the water 
    - summary table tab: all fish were detected at the inlet, only 60% of fish made it out 
    - why dying? lots of predators in the lake and then hard shift to the salt water. they also get transferred alot, and when they don't get enough fish back they take fish from other hatcheries 