# analytics_BirdSongs
 Analytics of Bird song audio files and locations -SpacioTemporal Analysis <br>
 As per VAST Challenge 2018 (Visual Analytics Community): <br>
 http://www.vacommunity.org/VAST+Challenge+2018+MC1
 
 
**Author - Jelena Lor** <br>
Python 2.7 <br>
*February 2019*

<br>

### Dependencies
- librosa (for audio load and analysis)
- os
- csv
- imageio
- seaborn
- datetime
- ipywidgets (for interative visualisation)
- The interactive feature does not work in Jupyter Lab, but it works if open via Anaconda Navigator


### Data
To run the notebook required the all the audio files from the VAST site: <br>
http://www.vacommunity.org/VAST+Challenge+2018#Mini-Challenge_1
<br>
the file is too large to upload onto the GitHub <br>
'ALL BIRDS' folder should be saved in the same directory as the notebook <br>

 
 ### SUMMARY
 
 - Interactive SpacioTemporal Analysis of bird movements (based on locations of collected audio files of bird songs)
 - Density plot to get insights into the bird's usual place of residence (by bird species)
 - Bird call and song patterns by time of day 
 
 <br>
 <br>
 
 **1) Data count by bird species**
 
![count_plot](https://user-images.githubusercontent.com/31029142/63639213-b8bb0300-c65e-11e9-9ad2-36699eb1eed1.PNG)

<br>

**2) Interactive plot displaying count of bird songs by year for a chosen bird species compared to a general trend (all species)**

<br>

![count_by_year](https://user-images.githubusercontent.com/31029142/63639215-beb0e400-c65e-11e9-8ab1-98aa34109c33.PNG)

<br>

**3) Interactive plot displaying count of bird songs by time of day for a chosen bird species compared to a general trend (all species)**

<br>

![count_by_tod](https://user-images.githubusercontent.com/31029142/63639219-c4a6c500-c65e-11e9-8dea-975c2ff1846f.PNG)

<br>


**4) Interactive plot displaying the record count (barplot) and density plot on the map by year for a chosen bird species**

<br>

![time_density_plot](https://user-images.githubusercontent.com/31029142/63639220-c6708880-c65e-11e9-8be1-f00e5ac67677.PNG)


**5) Interactive plot displaying the location of the collected bird's song audio file versus the density plot for a chosen bird species** <br>
*RoseCrested Blue Pipit reside in the area of the location where the first bird song audio was collected*

<br>

![density_plot1](https://user-images.githubusercontent.com/31029142/63639223-c83a4c00-c65e-11e9-9ff5-0ec65caac42f.PNG)

<br>

**6) Interactive plot displaying the location of the collected bird's song audio file versus the density plot for a chosen bird species** <br>
*Queenscoat DO NOT reside in the area of the location where the first bird song audio was collected*

<br>

![density_plot2](https://user-images.githubusercontent.com/31029142/63639224-cb353c80-c65e-11e9-8a91-13ee6d17e698.PNG)
