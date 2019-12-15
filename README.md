# matplotlib-challenge
UCSD Data Science Bootcamp HW5, Alexis Perumal, 12/15/19

Summary

The growing Pymaceuticals Inc., has 9 drugs in the development pipeline that they want to analyze for efficacy in arresting cancer. A placebo is included as a control. Timeseries data over a 45-day treatment period has been provided for three key indicators: tumor volume, # of metastatic sites, and survival rates. 


Approach

Analysis involved creating a jupyter notebook file and using Python, pandas and matplotlib to analyze the CSV dataset, generating tabular outputs and charts for the aforementioned indicators. Compounds studied include: Capomulin, Ceftamin, Infubinol, Ketaprill, Naftisol, Popriva, Ramicane, Stelasyn, Zoniferol.


Findings

1.	Tumor volume: Two drugs, Ramicane (22.3% reduction) and Capomulin (19.5% reduction), demonstrated statistically significant (95% confidence) reduction in tumor volume over the 45-day day period vs. growth for the other seven drugs and placebo.

2.	Metastatic sites: All compounds and the placebo showed an increase in metastatic sites over the trial period. Ramicane, Capomulin and Stelasyn had the lowest growth.

3.	Survival Rates: None of the drugs, nor the control, resulted in full survival. Capomulin had the highest survival rate at 84% followed by Ramicane at 80%.


Conclusion and Recommendations

1.	Ramicane and Capomulin showed materially better results across tumor volume reduction and slower growth in metastatic sites with statistical significance. Additionally, they also demonstrated the highest survival rates although the statistical significance of that difference can’t be evaluated. Overall, we recommend continued aggressive evaluation of these two drugs.

2.	Three other drugs also demonstrated a weaker, but still statistically significant beneficial response:
a.	Ceftamin with slower tumor volume growth
b.	Stelasyn, Infubinol, Naftisol with slower growth in metastatic sites.

These compounds may merit further evaluation in the event that Ramicane and Capomulin are disqualified based on further evaluation.

3.	None of the compounds did worse than the control with statistical significance.


Key Files:

• README-assignment.md - The Assignment, https://github.com/alexisperumal/matplotlib-challenge/blob/master/README-assignment.md

• Pymaceuticals/2019-12-10_pymaceuticals-Alexis.ipynb - Python notebook for the project (jupyter notebook file), https://github.com/alexisperumal/matplotlib-challenge/blob/master/Pymaceuticals/2019-12-10_pymaceuticals-Alexis.ipynb

• 2019-12-15_Pymaceuticals-Analysis.docx - Analysis report (MS Word file), https://github.com/alexisperumal/matplotlib-challenge/blob/master/2019-12-15_Pymaceuticals-Analysis.docx

• 2019-12-15_Pymaceuticals-Analysis.pdf  - Analysis report (PDF file), https://github.com/alexisperumal/matplotlib-challenge/blob/master/2019-12-15_Pymaceuticals-Analysis.pdf

