## The Power of Plots

Pymaceuticals Inc., a burgeoning pharmaceutical company based out of San Diego, specializes in anti-cancer pharmaceuticals. In its most recent efforts, it began screening for potential treatments for squamous cell carcinoma (SCC), a commonly occurring form of skin cancer.


We have access to the complete data from their most recent animal study. In this study, 250 mice identified with SCC tumor growth were treated through a variety of drug regimens. Over the course of 45 days, tumor development was observed and measured. The purpose of this study was to compare the performance of Pymaceuticals' drug of interest, Capomulin, versus the other treatment regimens.


Given the task by the executive team to generate all of the tables and figures needed for the technical report of the study and for a top-level summary of the study results.


**The final report will include the following below:**
- A summary statistics table consisting of the mean, median, variance, standard deviation, and SEM of the tumor volume for each drug regimen

- Bar plots that show the number of data points for each treatment regimen using Pandas's DataFrame.plot() and Matplotlib's pyplot

- A box plot of the final tumor volume for the most promising treatment regimens: Capomulin, Ramicane, Infubinol, and Ceftamin; and highlighting any potential outliers in the plot. Additionally, display the calculation of the quartiles and IQR and quantitatively determine if there are any potential outliers across all four treatment regimens.

- A line plot of time point versus tumor volume for a single mouse treated with Capomulin

- A scatter plot of mouse weight versus average tumor volume for the Capomulin treatment regimen. Additionally, show the calculation of the correlation coefficient and linear regression model and plot this linear regression model on top of the scatter plot.


**Observations and Insights:** 
250 mice identified with squamous cell carcinoma (SCC) tumor growth were treated through a variety of drug regimens. Over the course of 45 days, tumor development was observed and measured.
- Of the drug regimens used, Capomulin and Ramicane were the treatments seen in mice with the lowest average tumor volume whereas Ketapril and Naftisol regimens had the highest average of tumor volume.

- The distribution of data of the four treatment regmines of Capomulin, Ramicane, Infubinol, and Ceftamin show that Ramicane had the lowest tumor volume data distribution compared to Capomulin, whereas Infubinol had the highest tumor volume data distribution. It should be noted that there was an outlier in the Infubinol treatment where tumor volume was low for one subject.

- The correlation coefficient between both mouse weight and tumor volume is 0.84 indicating that the strength of this correlation is strong. This would mean that mouse weight has an influence on tumor volume.

- Treatment Regimens Capomulin and Ramicane had more opportunities to be used compared to Propovia, this may mean that Capomulin and Ramicane subjects lived longer than Propovia subjects.

Overall, Ramicane is the treatment regimen comparable to Capomulin in reducing the tumor volume of squamous cell carcinoma (SCC) in mice.


