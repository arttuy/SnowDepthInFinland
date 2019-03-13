# Snow depth in Finland animimation

Animation of how snow depth in Finland has evolved during last 100 years.
Uses the data from Finnish Meteorological Institutes (FMI)  open database.

The api call code is forked from [juhanitakkunen/adaptive-alarm/](https://github.com/JuhaniTakkunen/adaptive-alarm)

## Current status
One api call to FMI open data can be done. The results are parsed to pandas DataFrame
and saved to 'test.csv'.

**Next steps**
1. Modify the api call to loop over years 1918-2019
2. Make animation
