# **Bike Sharing Venture Proposal**<br><br>

## Overview of Project

### Executive Summary
The purpose of this project is to develop a business proposal for a bicycle-sharing program in Des Moines, Iowa.  Bike rider data from a bike-sharing program in New York City for August 2019 was used to make the case for a similar business in Des Moine.  One major assumption was that the majority of bike usage was during the summer months such as August. 
For this project, the visualization tool Tableau was used to create the data graphs, charts and other visual tools for analyzing and presenting the data.  

### Data Sources
The data used in this analysis was gathered from the New York City Citi Bike program.  The data archives are publicly available on the [Citi Bike site](https://ride.citibikenyc.com/system-data).

### Software Used
Tableau Desktop 2022.2.1
Pandas Library 1.3.5
Jupyter Notebook:
IPython          : 7.31.1
ipykernel        : 6.9.1
ipywidgets       : 7.6.5
jupyter_client   : 6.1.12
jupyter_core     : 4.9.2
jupyter_server   : 1.13.5
jupyterlab       : 3.3.2
nbclient         : 0.5.13
nbconvert        : 6.4.4
nbformat         : 5.3.0
notebook         : 6.4.8
qtconsole        : 5.3.0
traitlets        : 5.1.1

### Tableau 
[Tableau Public link](https://public.tableau.com/app/profile/david.mk6453/viz/Challenge_14_tableau/BikeSharingVentureProposal?publish=yes)

<br><br>

## Results 

<br><br>

### User Breakdown
| ![fig.1](https://github.com/mrmarken/bikesharing/blob/main/Images/dash_customer_breakdown.png) |
| :---: |
| **Figure 1.** Bike-Sharing Customer Breakdown |
| In NYC, there were over 2.3M trips that occurred during the month of August with 81% of the riders in the "subscriber" category and that Men were the primary user of this program (65%). |

<br><br>

### Trip Duration for all Users
| ![fig.2](https://github.com/mrmarken/bikesharing/blob/main/Images/checkout_times_for_users.png) |
| :---: |
| **Figure 2.** Trip Duration (per minute) |
| 99% of all rides are under 60 minus with the majority of rides taking 20 minutes or less. |

<br><br>

### Trip Duration by Gender
| ![fig.3](https://github.com/mrmarken/bikesharing/blob/main/Images/checkout_times_by_gender.png) |
| :---: |
| **Figure 3.** Trip Duration by Gender (per minute) |
| Male riders make up the larger population of users (65%) |

<br><br>

### Starting and Ending Locations
| ![fig.4](https://github.com/mrmarken/bikesharing/blob/main/Images/dash_start%26end_locations.png) |
| :---: |
| **Figure 4.** Starting and End Locations |
| The locations where bike rides start and end tend to be in business-heavy locations throughout NYC. |

<br><br>

### Bike Rides per Hour
| ![fig.5](https://github.com/mrmarken/bikesharing/blob/main/Images/august_peak_hours.png) |
| :---: |
| **Figure 5.** Hourly Usage on Average |
| The overall average usage per day indicates heavy usage during the morning and evening commute hours. |

<br><br>

### Trips per Day per Hour
| ![fig.6](https://github.com/mrmarken/bikesharing/blob/main/Images/trips_by_weekday_per_hour.png) |
| :---: |
| **Figure 6.** Number of Trips on Weekdays by Hour of Day |
| The majority of rides take place during the weekdays (Mon-Fri).  The data points to high usage during commute hours (8-9AM). |

<br><br>

### Trips by Gender (per Day and by Hour)
| ![fig.7](https://github.com/mrmarken/bikesharing/blob/main/Images/trips_by_gender_(weekday_per_hour).png) |
| :---: |
| **Figure 7.** Number of Trips by Gender (per Day and by Hour)  |
| The majority of the bike-sharing users are male and they use the bikes for commuting to/from work |

<br><br>

### Trips by Gender (per Day and by Hour)

| ![fig.8](https://github.com/mrmarken/bikesharing/blob/main/Images/user_trips_by_gender_by_weekday.png) |
| :---: |
| **Figure 8.** Bike Rides per Day |
| Thursday and Fridays tend to be the highest-usage days in a given week in August followed by Tuesday for male subscribers.
On the opposite side, casual users ("customers") tend to use the services primarily on the weekends.|

<br><br>

## Summary

Based on the Tableau story produced for bike sharing activities in New York City, it can be summarized that:
* Bike-sharing stations are in high demand in business-heavy areas
* Subscribers make up the majority of users of this service
* Males make up the majority (65%) of users 
* The majority of trips took less than 20 minutes

The data suggests that starting a bike-sharing program in Des Moines may be a good business venture as long as the bike-sharing stations are located near business-heavy areas.  However, it is recommended that further analysis on the NYC bike-sharing data is performed to understand a few key items.  Given the following two visualizations on bike usage and bike repair:
| ![fig.9](https://github.com/mrmarken/bikesharing/blob/main/Images/bike_utilization.png) |  ![fig.10](https://github.com/mrmarken/bikesharing/blob/main/Images/repairs_by_bikeID.png) |
| :---: | :---: | 
| **Figure 9.** Bike Utilization | **Figure 10.** Bike repairs per each BikeID |


An additional analysis should help provide a better understanding of any relationship between bike usage (e.g. mileage) and bike repairs and how those costs can be further mitigated.

### Additional Recommendations
Lastly, in order to provide a deeper analysis of taking on such an endeavor in Des Moines, it is recommended that the following data sets are visualized and analyzed in the future:
* Usage throughout a calendar year to understand how the seasons affect the bike-sharing program engagement
* Analyze data from other cities that are similar to Des Moines in terms of size, gender breakdown, public transportation options and usage, and population density.
* Breakdown of age groups to better understand the user population


