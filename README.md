# Milestone-1-AirFly-Insights-project
Author- Sougata Kumar Maity
## Dataset Information

### Actual data Dataset
- Rows: 336,776
- Columns: 21
- Source: https://meet.google.com/qre-ihpf-sek

### Processed Dataset
- Rows: 327,346
- Columns: 26
- Missing Values in : 0

  
### Workflow
1. Data Loading
 -Loaded the raw flights dataset using pandas.

2. Data Description
 -| id | Unique identifier |
<br>
 -| year | Flight year |
 -| month | Flight month |
 -| day | Flight day |
 -| dep_time | Actual departure time |
 -| sched_dep_time | Scheduled departure |
 -| dep_delay | Departure delay (min) |
 -| arr_time | Arrival time |
 -| sched_arr_time | Scheduled arrival |
 -| arr_delay | Arrival delay (min) |
 -| carrier | Airline code |
 -| flight | Flight number |
 -| origin | Origin airport |
 -| dest | Destination airport |
 -| air_time | Flight duration |
 -| distance | Distance traveled |
 -| hour | Departure hour |
 -| minute | Departure minute |
 -| name | Airline name |

3.Feature Engineering
 -Create column Flight Date
 -Create column day_of_week
 -Create column route
 -Create column cancelled 
 -Create column on_time 

 
4.Data Cleaning
 - Remove the missing values
 - Check Duplicate (0 duplicate found)
 Original shape: (336776, 26)
After dropping missing rows: (327346, 26)


###Save processed data 
 -Save the processed dataset
