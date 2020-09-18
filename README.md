# Udacity-Final-Project-AB-Testing
After learning the classes AB Testing courses from Udacity, I would like to try the final project to test my ability. My first time to use GitHub. All the process would be implemented by Jupyter Notebook as well as R. So excited to start my GitHub journey!

An experiment was conducted in which potential Udacity students were divided into two groups: experimental and control group. This experiment is used to test one change made by Udacity platform can help reduce the number of frustrated students who left the free trial because they didn't have enough time. The experiment group was asked to input more time to study, after clicking the ‘start free trail button’, whereas the control group was not. 

1. First we define the null hypothesis and alternative hypothesis by carding whole process. 
2. Second, after determining the test, we also choose three invariant metrics(cookies,clicks and click through probability) while three variant metrics for evaluation (gross conversion,retention and net conversion). 
3. Third, we measure the variability about three evaluation metrics by calculating analytically instead of empirical calculating since the unit of diversion is cookie which is the same of the unit of analyze. 
4. Fourth, we need to calculate the size of testing, we use the online calculator to ensure the different sizes for three metrics. We also introduce the Jupyter Notebook to use another method to calculate the size.
5. Fifth, after determining the size, if we assume there is no other experiment works simultaneously, if we use the size which meet three metrics and 100% traffic, the duration will be 119 days. This duration is unrealistic since it will result to some business costs and risks, therefore, we choose the size which meet two metrics (gross conversion,net conversion). In this case, the duration is much shorter(18 days).
6. Sixth,since in the most of circumstances, we can’t divert 100% of the traffic due to realistic implementations and risks, if we divert 80% of the traffic, the duration is 22 days. 
7. Seventh, we move to the process of analyzing. We want to do the sanity check first to ensure that our experiment works correctly.
8. Finally, after passing the sanity check, we can analyze our results about different metrics and then we can also use the sign test to validate results.
