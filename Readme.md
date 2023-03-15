<b>Task</b><p>
A/B test analysis:<p>
Building a graph of cumulative revenue by groups.<p>
Building a graph of the cumulative average bill by groups.<p>
Construction of a graph of the relative change in the cumulative average check of group B to group A.<p>
Plotting the cumulative average number of orders per visitor by group.<p><p>
Plotting the relative change in the cumulative average number of orders per visitor of group B to group A.<p>
Building a scatter plot of the number of orders by users.<p>
Counting the 95th and 99th percentile of the number of orders per user. Boundary selection to define anomalous users.<p>
Building a scatter plot of order costs.<p>
Calculate 95th and 99th percentile order values. Boundary selection to detect anomalous orders.<p>
Calculation of the statistical significance of differences in the average number of orders per visitor between groups on "raw" data.<p>
Calculation of the statistical significance of differences in the average check of the order between groups according to "raw" data.<p>
Calculation of the statistical significance of differences in the average number of orders per visitor between groups on "cleaned" data.<p>
Calculation of the statistical significance of differences in the average check of the order between groups according to "cleaned" data.<p>
Make a decision based on the test results and explain it. Solution options:<p>
1. Stop the test, record the victory of one of the groups.<p>
2. Stop the test, record the absence of differences between groups.<p>
3. Continue the test.<p>
Data Description<p>
File /datasets/orders.csv.<p>
transactionId - order identifier;<p>
visitorId - identifier of the user who made the order;<p>
date — date when the order was made;<p>
revenue — order revenue;<p>
group — the A/B test group the order belongs to.<p>
File /datasets/visitors.csv.<p>
date - date;<p>
group — A/B test group;<p>
visitors - the number of users on the specified date in the specified A/B test group