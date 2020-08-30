# matplotlib-challenge
Homework 5 Matplotlib

Look across all previously generated figures and tables and write at least three observations or inferences that can be made from the data. Include these observations at the top of notebook.

1. Mouse ID g989 duplicates through the data frame when it was merge. After cleaning the data frame we can clearly observe in the bar chart that: the Drug regimen Propriva is affected on its Total number of Mice tested for the treatment , because meanwhile every Drug treatment has 25 mice tested in Total, the Total Number of Mice for Propriva has only 24 mice (1 Mouse ID less). Also it appears that female and male mice were carefully selected based on a delicate correlation of 50/50 , however when we take out the female mouse g989 the percentage drops to 49.60% female VS 50.40% male. Ultimately female participants had the last or greatest timepoint of recovery with the max of 45 days taken (all 5 mice on top of Final Tumor Volume df were female and all 4 recovered until the last day of testing).


2. The most effective drug regimen tested in mice is Capomulin  with the lowest interquartile range 7.781863460000004. This means it is the Drug Regimen that appears to has more consistency on the treatment results over the others ('Ramicane' = 9.098536719999998, 'Infubinol' = 11.477135160000003,'Ceftamin' = 15.577752179999997 ). Moreover Capumulin mean is the closest one in the total of Final Tumor Volume mean of Each Mouse Across 4 Drug Regimens box plot (look for red diamond). When I picked randomly mouse ID x401 in mice on Capomulin Drug regimen, the results on the line plot are promising reducing the Tumor Volume from 45 mm3 to almost 27 mm3 in a timepoint of 40 days. Comparison on weight and Tumor Volume had and equilibrium with a linear regression that could predict the consistency of future tests with y0,89 variance and a slope tendency x22.76.

3. Overall the performance of 'Pymaceuticals Inc.' drug of interest, Capomulin, is a very effective Drug Regimen to reduce tumor volume on mice. Only Ramicane has the potential of effectiveness when we compared the performance of Pymaceuticals drug regimen. Top 4 Drug regimens would be a) 'Capomulin', b) 'Ramicane', c) 'Infubinol', d) 'Ceftamin' respectively .

4. It is recommended for  the pharmaceutical company 'Pymaceuticals Inc.': to advance on clinical testing phase of Capomulinon and register its Drug for further use on humans and cancer treatment. Perhaps 'Pymaceuticals Inc.' should also consider Ramicane as a backup plan, Drug shows potential  in results of various testing on the the anti-cancer drug. Capomulinon fails in the small discrepancy on future tests, it is very safe to say it will continue positive treatment.
