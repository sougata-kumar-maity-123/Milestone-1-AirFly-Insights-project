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
 <br>
 -Loaded the raw flights dataset using pandas.


3. Data Description
<br>
  -| id | Unique identifier |
<br>
  -| year | Flight year |
<br>
  -| month | Flight month |
<br>
  -| day | Flight day |
<br>
  -| dep_time | Actual departure time |
<br>
  -| sched_dep_time | Scheduled departure |
<br>
  -| dep_delay | Departure delay (min) |
<br>
  -| arr_time | Arrival time |
<br>
  -| sched_arr_time | Scheduled arrival |
<br>
  -| arr_delay | Arrival delay (min) |
<br>
  -| carrier | Airline code |
<br>
  -| flight | Flight number |
<br>
  -| origin | Origin airport |
<br>
  -| dest | Destination airport |
<br>
  -| air_time | Flight duration |
<br>
  -| distance | Distance traveled |
<br>
  -| hour | Departure hour |
 <br>
  -| minute | Departure minute |
<br>
  -| name | Airline name |


<br>
<br>
 3.Feature Engineering
<br>
  -Create column Flight Date
 <br>
  -Create column day_of_week
 <br>
  -Create column route
 <br>
  -Create column cancelled 
 <br>
  -Create column on_time 

 <br>
 <br>
 4.Data Cleaning
 <br>
 - Remove the missing values
 <br>
 - Check Duplicate (0 duplicate found)
 <br>
 Original shape: (336776, 26)
 <br>
After dropping missing rows: (327346, 26)
<br>
<br>

###Save processed data 
<br>
 -Save the processed dataset
