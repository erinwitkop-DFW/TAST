## Nov. 7, 2024 

# Goals:
1. Reformat the TAST data to allow for joining with detection data
2. Load CFS data
3. Load release group 1 or 2 data
4. Start joining data 

## Notes:
1. Reformat TAST data to allow for joining with detection data
    - to allow for joining the best way is to ask whether a given detection falls between the range of on time periods or the range of off time periods
    - decided to create a new reformatted excel spreadsheet by hand that has start and end times for each on off period
    - need to think about how to extend across multiple days...
    - could just only join with when the tast was ON and assume that the TAST was off for all other times
    - I think James may be interested also in the duration of OFF data so I've decided to include this too
    - What I'm confused about is that the listed hours on or off do not match up with the number of hours between one row of on and the next row of off.
    - asking James if he can help clarify this before I continue reformatting

2. Loading the cfs data 
    - https://waterdata.usgs.gov/monitoring-location/12080010/#parameterCode=00065&period=P7D&showMedian=false 
    - I previously gathered the data and now I just need to load it into R
    - 150759_00060 = discharge in cubic feet per second 
    - got the data correctly loaded

3. Load the release group 1 or 2 data
    - James says this is in the "In "tag bio data" tab
    - got this loaded will likely need to do some reformatting later

4. Loading in the all detections file 
    - loaded in correctly, removed some extraneous columns and made a datetime column

5. Joining sunrise sunset
    - after getting the dates and times correctly formatted I was able to do this 

6. Joining tide data and calculating tide height for each time

    - still trying to figure out the best method for approximating this. It doesn't look like I'll be able to use actual recorded data because though NOAA has a chart I can't find a way to download data at something like ten minute intervals
    - going to need to think about this more!