# railway_analysis
Analysis is devided into 2 parts. 
For the first part analysis is done to look for 
seasonal change in patterns in SL and 3A classes based on occupancy 
of current and last year. Data is recorded for JAN-15 01-10 and MAY-15 01-10
to account for seasonal variation.

For the second part train wise comparison is performed for 4 selected 
trains of central railway:
1. Coimbatore Exp (Mumbai to Bangalore)
2. Kushinagar Exp (Mumbai to Gorakhpur)
3. Jhelum Express (Jammu to Pune)
4. Kolkata Mail (Mumbai to Howrah)

An attempt is made to look for patterns based on no of passengers and 
percentage of utilization for 3A and SL classes.

For perfromaing the analysis Hierarchical clustering is used.
To prepare the distance matrix Euclidean distance is used and to 
merge the clusters Ward's minimum variance criterion is used.
