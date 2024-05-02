# pandas_plotting - Pymaceuticals

## Analysis
Pymaceuticals completed studies across 10 distinct treatment regimens to assess the impact of each on tumor volume. The tested regimens were as follows:

Capomulin, Ceftamin, Infubinol, Ketapril, Naftisol, Placebo, Propriva, Ramicane, Stelasyn, Zoniferol.

Across all studies, 51% of mice used were male and 49% were female. Summary statistic collected accross all treatment regimens assessed the mean, median, variance, standard deviation, and standard error of the mean (SEM). Placebo statistics - Mean: 54.03, Median: 52.59, Variance: 61.17, Standard Deviation: 7.82, SEM: .581

Analysis of the treatment regimens Capomulin, Ramicane, Infubinol, and Ceftamin showed that Ramicane produced the lowest median final tumor volume followed by Capomulin. One possible outlier was indicated in the Infubinol regimen - mouse c326 recorded a tumor volume at 36.32 mm3 which is below the calculated lower bound for the regimen.

Further analysis was completed on results of the Capomulin treatment regimen to show a positive correlation (Pearson R = .84) between mouse weight and average tumor volume - a higher mouse weight showed a higher average tumor volume. 

Within the Capomulin regimen, the data of mouse y793 was examined based on tumor volume over the time points recorded. The line graph of the data shows a negative correlation - as time increases the tumor volume decreases. 

## References

This assignment was completed individually and guided by the EdX provided starter code. Xpert Learning assistant and class materials were used to aid in the coding of the IQR for loop and syntax of plotting.

