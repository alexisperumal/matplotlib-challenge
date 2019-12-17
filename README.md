# matplotlib-challenge
UCSD Data Science Bootcamp HW5, Alexis Perumal, 12/16/19

Summary

The growing Pymaceuticals Inc., has 3 drugs in the development pipeline that they want to analyze for efficacy in arresting cancer. A placebo is included as a control. Timeseries data over a 45-day treatment period has been provided for three key indicators: tumor volume, # of metastatic sites, and survival rates. 


Approach

Analysis involved creating a jupyter notebook file and using Python, pandas and matplotlib to analyze the CSV dataset, generating tabular outputs and charts for the aforementioned indicators. Compounds studied include: Capomulin, Infubinol, Ketapril.


Findings

1.	Tumor volume: Capomulin (19.5% reduction), demonstrated statistically significant (95% confidence) reduction in tumor volume over the 45-day day period vs. growth for the other two drugs and placebo.

2.	Metastatic sites: All compounds and the placebo showed an increase in metastatic sites over the trial period. Capomulin had the lowest growth.

3.	Survival Rates: None of the drugs, nor the control, resulted in full survival. Capomulin had the highest survival rate at 84%. 


Conclusion and Recommendations

1.	Capomulin showed materially better results across tumor volume reduction and slower growth in metastatic sites with statistical significance. Additionally, it also demonstrated the highest survival rates although the statistical significance of that difference can’t be evaluated. Overall, we recommend continued aggressive evaluation of Capomulin.

2.	Infubinol demonstrated a weaker, but still statistically significant beneficial response on metastatic site response but had the lowest survival rate.



Key Files:

• README-assignment.md - The Assignment, https://github.com/alexisperumal/matplotlib-challenge/blob/master/README-assignment.md

• 2019-12-10_pymaceuticals-Alexis-v2.ipynb - Python notebook for the project (jupyter notebook file), https://github.com/alexisperumal/matplotlib-challenge/blob/master/Pymaceuticals/2019-12-10_pymaceuticals-Alexis-v2.ipynb

• 2019-12-15_Pymaceuticals-Analysis-v2.docx - Analysis report (MS Word file), https://github.com/alexisperumal/matplotlib-challenge/blob/master/2019-12-15_Pymaceuticals-Analysis-v2.docx

• 2019-12-15_Pymaceuticals-Analysis-v2.pdf  - Analysis report (PDF file), https://github.com/alexisperumal/matplotlib-challenge/blob/master/2019-12-15_Pymaceuticals-Analysis-v2.pdf

