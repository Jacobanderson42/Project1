# Project1

Project 1 from B ME 450

GitHub link
https://github.com/Jacobanderson42/Project1/blob/master/Project_1.ipynb

Colab link
https://colab.research.google.com/drive/1sI9hxufA91SKLDljeopnamduUe96_sR1

# Problem Statement

This project was looking to analyze the data that is taken by the CTD research arrays. We look to be able to plot 
the speed of sound versus depth for each of the dives over a period of a day. We also are looking to find the effect 
of time of day, location, and season, on the speed of sound profile.

# Background/solution/results

The CTD device is used to take measurements of the conductivity, temperature, and depth of seawater at various depths during a
“dive” where the device moves from its location up towards the surface and back down. During these dives data is recorded throughout
the dive giving results for various depths. This data can then be used to calculate things such as salinity and speed of sound.
In order to gain insight into the effects of speed of sound python code was used to analyze the data provided by the Ocean
Observatories Initiative. This code takes an input in the form of a CSV file that contains the raw data from the OOI website. 

This data is then analyzed and the necessary information is extracted from the CSV file that has been uploaded. One the data is
imported the calculation for speed of sound is done using the temperature, salinity, and depth data. The data is then separated 
into dives based on the change in depth of the CTD. With the index of each dive start and end, the dives are then plotted on the 
same axes. The data is then separated by its time into two categories, one for daytime and one for nighttime. This is based 
on the time for sunrise and sunset at that location. The data is then averaged by dividing up the depth into equal sections 
and finding all speed of sound values that correspond with depths within that range. This allows for the analysis of the speed 
of sound at a given location for use in calculations. The graphs of the data for each of the 7 arrays can be seen below for the 
summer and winter seasons.

# Graphs for each dive:
![](https://github.com/Jacobanderson42/Project1/blob/master/Images/Dives/AxialDeep_Summer_Dives.png)
![](https://github.com/Jacobanderson42/Project1/blob/master/Images/Dives/AxialDeep_Winter_Dives.png)
![](https://github.com/Jacobanderson42/Project1/blob/master/Images/Dives/AxialShallow_Summer_Dives.png)
![](https://github.com/Jacobanderson42/Project1/blob/master/Images/Dives/AxialShallow_Winter_Dives.png)
![](https://github.com/Jacobanderson42/Project1/blob/master/Images/Dives/OregonOffshoreDeep_Summer_Dives.png)
![](https://github.com/Jacobanderson42/Project1/blob/master/Images/Dives/OregonOffshoreDeep_Winter_Dives.png)
![](https://github.com/Jacobanderson42/Project1/blob/master/Images/Dives/OregonOffshoreShallow_Summer_Dives.png)
![](https://github.com/Jacobanderson42/Project1/blob/master/Images/Dives/OregonOffshoreShallow_Winter_Dives.png)
![](https://github.com/Jacobanderson42/Project1/blob/master/Images/Dives/OregonShelf_Summer_Dives.png)
![](https://github.com/Jacobanderson42/Project1/blob/master/Images/Dives/OregonShelf_Winter_Dives.png)
![](https://github.com/Jacobanderson42/Project1/blob/master/Images/Dives/OregonSlopeDeep_Summer_Dives.png)
![](https://github.com/Jacobanderson42/Project1/blob/master/Images/Dives/OregonSlopeDeep_Winter_Dives.png)
![](https://github.com/Jacobanderson42/Project1/blob/master/Images/Dives/OregonSlopeShallow_Summer_Dives.png)
![](https://github.com/Jacobanderson42/Project1/blob/master/Images/Dives/OregonSlopeShallow_Winter_Dives.png)

# Graphs for day versus night:
![](https://github.com/Jacobanderson42/Project1/blob/master/Images/Day%20vs%20Night/AxialDeep_Summer_DayvsNight.png)
![](https://github.com/Jacobanderson42/Project1/blob/master/Images/Day%20vs%20Night/AxialDeep_Winter_DayvsNight.png)
![](https://github.com/Jacobanderson42/Project1/blob/master/Images/Day%20vs%20Night/AxialShallow_Summer_DayvsNight.png)
![](https://github.com/Jacobanderson42/Project1/blob/master/Images/Day%20vs%20Night/AxialShallow_Winter_DayvsNight.png)
![](https://github.com/Jacobanderson42/Project1/blob/master/Images/Day%20vs%20Night/OregonOffshoreDeep_Winter_DayvsNight.png)
![](https://github.com/Jacobanderson42/Project1/blob/master/Images/Day%20vs%20Night/OregonOffshoreShallow_Summer_DayvsNight.png)
![](https://github.com/Jacobanderson42/Project1/blob/master/Images/Day%20vs%20Night/OregonOffshoreShallow_Winter_DayvsNight.png)
![](https://github.com/Jacobanderson42/Project1/blob/master/Images/Day%20vs%20Night/OregonSlopeDeep_Summer_DayvsNight.png)
![](https://github.com/Jacobanderson42/Project1/blob/master/Images/Day%20vs%20Night/OregonSlopeShallow_Summer_DayvsNight.png)
![](https://github.com/Jacobanderson42/Project1/blob/master/Images/Day%20vs%20Night/OregonSlopeShallow_Winter_DayvsNight.png)

# Graphs for average ssc curve:
![](https://github.com/Jacobanderson42/Project1/blob/master/Images/Average/AxialDeep_Summer_Average.png)
![](https://github.com/Jacobanderson42/Project1/blob/master/Images/Average/AxialDeep_Winter_Average.png)
![](https://github.com/Jacobanderson42/Project1/blob/master/Images/Average/AxialShallow_Summer_Average.png)
![](https://github.com/Jacobanderson42/Project1/blob/master/Images/Average/AxialShallow_Winter_Average.png)
![](https://github.com/Jacobanderson42/Project1/blob/master/Images/Average/OregonOffshoreDeep_Summer_Avereage.png)
![](https://github.com/Jacobanderson42/Project1/blob/master/Images/Average/OregonOffshoreDeep_Winter_Avereage.png)
![](https://github.com/Jacobanderson42/Project1/blob/master/Images/Average/OregonOffshoreShallow_Summer_Avereage.png)
![](https://github.com/Jacobanderson42/Project1/blob/master/Images/Average/OregonOffshoreShallow_Winter_Avereage.png)
![](https://github.com/Jacobanderson42/Project1/blob/master/Images/Average/OregonShelf_Summer_Avereage.png)
![](https://github.com/Jacobanderson42/Project1/blob/master/Images/Average/OregonShelf_Winter_Avereage.png)
![](https://github.com/Jacobanderson42/Project1/blob/master/Images/Average/OregonSlopeDeep_Summer_Avereage.png)
![](https://github.com/Jacobanderson42/Project1/blob/master/Images/Average/OregonSlopeDeep_Winter_Avereage.png)
![](https://github.com/Jacobanderson42/Project1/blob/master/Images/Average/OregonSlopeShallow_Summer_Avereage.png)
![](https://github.com/Jacobanderson42/Project1/blob/master/Images/Average/OregonSlopeShallow_Winter_Avereage.png)

# Conclusions
It can be seen from the graphs that there is some variance in the speed of sound profile depending on a number of variables
including, number of dives, location, season, and time of day.

The number of dives between the shallow and deep profilers varies greatly. For the shallow profilers there is an average of 
17 dives where as for the deep profilers there is an average of about 3 dives per day.
	
The maximum speed of sound happens at a deeper depth in the winter than in the summer. This can be seen in a number of the 
graphs where the summer tends to show the max speed of sound almost at the surface where the winter graphs have a distinct drop 
in depth before reaching the max speed of sound. This is due to colder surface temperatures that decrease the speed of sound 
near the surface. In summer, the surface temperatures heat up and the speed of sound near the surface increases, thus the max 
speed of sound happens at a lower depth in the summer.
	
The max speed of sound in the day tends to happen at a lower depth than at night. This is reflected in the graphs by a 
rise in the depth of max speed of sound. As the depth increases the speed of sound profile for day and night are the 
same since the surface temperature has little effect at these depths.

The season tends to have an effect on the speed of sound near the surface due to an increase in surface temperature. As 
discussed previously, the max speed of sound happens at a lower depth due to an increase in surface temperature. The value 
of the maximum speed of sound also tends to increase as the overall temperature of the water near the surface increases 
compared to winter. Another difference in the speed of sound profile between summer and winter is that the change in speed 
of sound with depth is more dramatic in the summer since the maximum speed of sound is higher. This means that to get to 
the normal speed of sound for the ocean temperatures, the speed of sound must change more rapidly as compared to winter.


Comparing the locations in this case is somewhat difficult as most of the data doesn’t line up to allow a direct comparison. 
The Oregon Offshore Cabled Shallow Profiler Mooring and the Axial Base Shallow Profiler are two that are similar and easy to 
compare. In comparing these it can be seen that the Offshore profiler has a higher maximum speed of sound as compared to the 
axial base profiler. This may be due to differences in salinity and temperatures due to the proximity to the shore.

# References
https://oceanobservatories.org/ \
https://sunrise-sunset.org/api
