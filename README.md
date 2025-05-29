# PRODIGY_DS_05
Analyze and visualize patterns in the US\_Accidents\_March23.csv dataset using Python libraries like Pandas, Seaborn, and Matplotlib. The dataset includes details such as time, weather, and road conditions during accidents across the United States.

Data Preprocessing:

* Converted Start_Time to datetime format.
* Extracted:
  Hour of the accident
  Day of the Week from Start_Time
* Handled missing data:
  Filled missing Weather_Condition with Unknown
  Filled missing Bump values with False

Visualizations:

1. Accidents by Hour of the Day
* Displays the number of accidents for each hour (0–23).
* Helps identify peak hours for traffic incidents.
  
2. Accidents by Day of the Week
Shows accident distribution from Monday to Sunday.
Highlights the busiest and safest days on roads.

3. Top 10 Weather Conditions During Accidents
 Identifies the 10 most frequent weather conditions during accidents.
 Useful for understanding how weather impacts road safety.

4. Accidents Involving Road Bumps
 Simple count of accidents where a road bump was involved (Bump = True).
 Can help in assessing whether road bumps influence accident rates.

Libraries Used:

pandas
matplotlib.pyplot
seaborn


