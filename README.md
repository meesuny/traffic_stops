# Introduction to the traffic_stops page

This repository will analyze police traffic stop data collected in various Virginia localities from July 2020 to August 2022.  While some analysis of this data is available on the government website at https://data.virginia.gov/stories/s/rden-cz3h, this project will undertake a more fulsome analysis and also cross reference the traffic stop data along with additional data to gain further insight into traffic stop behavior by Virginia police of various localities.


# Background
Racial profiling in traffic stops has been an ongoing issue in community policing.  While it is impossible to completely remove any preexisting biases from the traffic stop process, we can identify and address any systematic issues that may underlie the process.  This study will identify and examine any racially motivated differences between the various localities in Virginia and also compare this against previous analyses done in 2000 using data collected from the Richmond, VA police department.  

Analysis of KY traffic stop data:  https://link.springer.com/article/10.1007/s11077-008-9065-z
Previous analysis of Richmond, VA traffic stop data:  https://journals.sagepub.com/doi/abs/10.1177/1098611101004001001?casa_token=XMTOgzS7iecAAAAA:ZkV1f6W_D41YbTTK_nj8bTS2A1n_Et-IZzJTXdkYinbLQfAejRY-dx_R4HLXXLdNO_-XFB7ktA2G
Previous survey of VA traffic stop information:  https://journals.sagepub.com/doi/abs/10.1177/1098611106296479?casa_token=8_YGwEQKDqYAAAAA:op2tLZ_ucQEAKdwh9WgwBR_9H36y8JJ3I6hf5CDT_YfCjbxtLP5lbD7h8t7KvuhqfeDA2oT_1IHw
Distinguishing certain officers as being more biased than others:  https://www.sciencedirect.com/science/article/pii/S0927537120301160?casa_token=7yqMDCWchMwAAAAA:j-HIhXDP67CToyWWtlGuIKOjZqeBIJe6JivpEHWbUh27I5JSjbiO-QArPvz9BWW6TEJtFK_7xw


# Data

The primary source of traffic stop data will be this site: https://data.virginia.gov/Public-Safety/Community-Policing-Data-July-1-2020-to-August-31-2/2c96-texw.
Due to the volume (1.88 rows with 20 columns), the data will be extracted to Rivanna using an API.  Additional data on community demographics will be gathered from the Weldon Cooper Center, and this data together with the traffic stop data will be stored in a relational database.  Finally, the text of the specific code sections that were cited as violations in the data will be gathered (i.e., scraped) from the government website (https://law.lis.virginia.gov/vacodefull/title46.2/) and presented together with all other analysis in the final dashboard.  



# Potential Analyses


# Challenges


