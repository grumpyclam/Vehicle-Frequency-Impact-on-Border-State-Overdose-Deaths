# Vehicle-Frequency-Impact-on-Border-State-Overdose-Deaths


**Research Question**

Is there a correlation between the volume of vehicles observed at the most frequented ports of entry in border states and recorded drug overdose deaths in U.S. Mexico and Canada border states?


**Scope of the project**

  The scope of the project was to import, clean, merge, visualize, run correlation and hypothesis testing via linear regression on the final data set. I individually visualized vehicle frequency and drug overdose deaths by themselves as well as together, I did this by state, time series, and kernel density plots. Correlation and hypothesis testing via linear regression were also visualized. The project did not include columns longitude, latitude, individual drugs, and individual vehicles in my visualizations or regression testing.


**Data Selection**

I have both csv files however they are too large to load into github. Feel free to ask me for them, they can also be found below.

  Both datasets were publicly avalible on data.gov and able to be freely downloaded in multiple formats. I downloaded the Department of Transportation, Customs and Border Protection dataset here via csv file: https://catalog.data.gov/dataset/border-crossing-entry-data-683ae. The Centers for Disease Control, National Vital Statistics System is avalible for download from a dashboard here: https://www.cdc.gov/nchs/nvss/vsrr/drug-overdose-data.htm.


**Statistical Significance**

**Hypothesis:**

H_0= The less vehicles that pass through the most frequented ports in each state, the less occurrence of overdose deaths in U.S. Mexico and U.S. Canda bordering states there will be.
 
H_a= The more vehicles that pass through the most frequented ports in each state, the larger the occurrence of overdose deaths in U.S. Mexico and Canada bordering states there will be.

**Statistical Test**:
Linear Regression

**Metrics Generated**:
	T-statistic, and P-value.

**Alpha value**:
	a= 0.05% 

**Conclusion:**

There is sufficient evidence to reject the null hypothesis and support the claim that the more vehicles that pass through the most frequented ports in each state, the larger the occurrence of overdose deaths in U.S. Mexico and Canada bordering states there will be.				The linear regression model used in the hypothesis testing was used to assess the statistical significance of the relationship between the independent and dependent variables. The independent variable here being the vehicle frequency total and the y variable being drug overdose deaths. The metrics used to determine statistical significance were the T-statistic and P-Value, as well as correlation coefficient. If the T-statistic is large it means that the chances of the data being not due to chance, which means the relationship is significant. The P-value is similar, the closer the value is to zero, the stronger the relationship between independent and dependent variables. 
  
The results from the t-statistic were far away from zero, being 51.012. Being that the number is so large, this tell me that the relationship between vehicle frequency and drug overdose deaths is strong. The p-value was nearly zero, which tells me that there is a very low chance of the relationship between the two variables being a fluke. Correlation via corr() was 0.800, in terms of Pearsons correlation, the closer to 1, the more positive relationship between variables. This verifies that my original hypothesis was true and we can reject the null hypothesis.


**Practical significance**

  The findings of the analysis are significant for United States Border Patrol, which means that the results are also significant for the United States Department of Homeland Security. This is because Border patrol is under the Department of Homeland Security. Since the hypothesis proved to be true, it means that vehicle frequency has a positive relationship with drug overdose deaths in the same states at which they entered the United States. This means that resources from the federal government should be allocated appropriately for Border Patrol. An example of the resources that could be allocated would be money for investment in big data technology that could be used for facial recognition, hiring of data analysts, scientists, and engineers who work specifically for Border Patrol. Resources can also be allocated to states with larger drug overdose deaths. Things like money for drug rehab centers, preventative drug education, and border patrol agents and training to detect drug smuggling.

**Summary of Conclusions**

For this project, the end goal was to find the correlation and relationship between high volume port vehicle border crossings and drug overdose deaths within those same states. I set out to get an answer via a hypothesis test using linear regression as the model. The t-statistic and p-value proved a very strong relationship that was not based on chance, between vehicle frequency and drug overdose deaths. I also used correlation to help verify the results of the linear regression. Multiple visualizations were done as well. With this information, the Department of Transportation, Customs and Border Protection, can now help allocate resources appropriately to states who need it most. This is also the case with allocating funds to states who have the highest levels of drug overdose deaths. I used multiple visualizations for this project. I looked at vehicle frequency total and drug overdose deaths individually before I combined them together to visualize them. I then visualized correlation and linear regression for the hypothesis test. 
