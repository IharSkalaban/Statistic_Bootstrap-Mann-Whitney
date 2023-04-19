### Experiment description
Here is a table with the results of the A/B test. The numeric column shows the revenue values for each user for the period of the experiment.

#### Description of the columns
1. value - values of the experiment metric
2. variant - Variant of the test (Control, Treatment)

#### The task
1. Calculate p-value in three ways: t-test, U-test, bootstrap mean
2. Compare the result between the test and the control for all of these cases
3. Write conclusions that can be drawn based on the analysis of the applied criteria.

#### After conducting data research, the following conclusions can be made:

    - we cannot compare averages between groups, because the distribution is skewed to the right (there are samples)
    - only the Bootstrap method is used to estimate the median
    - t-test and Mann-Whitney may be less accurate if the population distribution is skewed
    - The t-test may result in overestimation of the mean.
    - The Mann-Whitney test may not detect significant differences between groups, because it is based on ranks, not values
