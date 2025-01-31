## Oct. 31, 2024 

# Goals:
1. Meeting with James
2. Organize repository
3. Download needed external data sources


# Notes:
1. James briefed me on the description of the project

    - Goals of study:
        1. Assess the effects of the TAST device at stopping sea lion predation on fish passing from tumwater hatchery out to capital lake and then out to the bay
        2. Assess survival of Chinook in Capital Lake
        3. This was a pilot year of the study. Use the data to draw any potential conclusions regarding the effectiveness of the TAST device in order to determine whether a future study is warranted

    - Study design:
        1. Tag 50 chinook and release in two release groups
            1. Released 25 tagged fish with a large release group. Coincided with drought conditions and poor overall chinook survival from the release
            2. Released 25 tagged fish with a second large release group, weather conditions much better, lots of rain, experienced high survival 
        2. Only 3 data receivers, one at bridge close to hatchery, next downstream as you exit capital lake and then another right at the mouth of Budd Bay where the sea lions are
        3. TAST device was turned on and off at different intervals, it was not randomized or standardized, though it was correctly recorded

    - Additional variables to assess:
        1. Day/Time (night or day)
        2. flow cfs 
        3. Where in the tide cycle the detection was
        4. TAST device on/off
        5. Release group

    - Data structure:
        1. Each row TEMP_STATS_DESC == DET is a single detection. Each row lists the serial number of the receiver and the individual fish tab

    - Data analysis ideas:
        - Aggregate TAST on/off by weeks with similar lengths of time and time of day start/end for analysis

2. Organize repo
    - created repository with multiple different folders to organize documents and data

3. Download and organize external data sources

    1. Day and night times:
        - downloading from website provided by James: https://www.timeanddate.com/sun/usa/seattle?month=6&year=2024
        - Only need days between 5/24 to 8/24
        - Copying and pasting one month at a time into excel spreadsheet from this website