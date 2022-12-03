# **PyBer_Analysis**
### Module 5 Challenge
## **Overview**
    The task was to organize and analyze fare data for a ride-sharing company "PyBer". Cities were categorized by three demographics, 'Urban', 'Suburban', and 'Rural', with total drivers, rides (transactions), and driver count per demographic as the key elements to analyze.

### *Resources* 
    city_data.csv
    ride_data.csv
    Jupyter Notebook running Python 3.7.15
## **Summary**
#### An analysis of this data concluded that:
The largest gap between almost all values of data happened between the 'Rural' and 'Urban' city types, with 'Suburban' largely filling in the averages in-between the two. 

!![Pyber Summary](../../../../../C:/BootCamp/Class%20Projects/Module_5_MatPlotLib/PyBer_Analysis/Resources/Pyber_Summary.png)

With fewer populations (and therefore fewer of both drivers and customers) in Rural areas, the drivers make much more on average per ride. However, the much higher cost-per-ride could also easily be attributed to longer distances between destinations, which also contributes to higher fares, which would negatively result in fewer customers because the cost is so high. 
Likewise, there are far more people in densely populated Urban areas, and therefore more customers, but also more drivers. With more saturation of drivers and most likely shorter distances, the average fare for the rider is quite low (good for customers), but the average fare per driver is also low (bad for drivers).

Whlie the task was to sort and analyze the data and certainly NOT to offer an opionion on business affairs, I would certainly hope that city fares in general were potentially raised slightly. This would help bridge the gap between the Rural and Suburban areas per-ride fares for the drivers, but at the risk of lowering the total number of riders because of higher cost. Equal but opposite would be to lower the cost-per-mile of the Rural rides in order to help costs for the riders, but at the detriment to the drivers for having to complete more rides to make the same wages.

### *Potential Problems*

Two parameters I would like to see to back this idea up would indeed be a trip duration and a distance-per-trip. That would allow you to find the average fare-per-mile or fare-per-minute, which I imagine would also be quite different from Urban and Rural areas. 

