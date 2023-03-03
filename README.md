<h1 align="center">
Chi Square & ANOVA hypothesis tests
</h1>

<p align="center">
<img src="https://www.investopedia.com/thmb/jgSEMXKV6NiQsbOGPw_ptsWtp8c=/750x0/filters:no_upscale():max_bytes(150000):strip_icc():format(webp)/Term-Definitions_hypothesistesting-4981dc2cf6024d7ca9f5497ab86cee73.jpg" alt="" title="" width="50%" height="50%">
</p>
<p align="center">
<i>(Image Source: https://www.investopedia.com/terms/h/hypothesistesting.asp)</i>
</p>


## I. Main goals:
- Practice using different Chi Square & Analysis of Variance (ANOVA) tests on sample data sets
- Create nice .pdf report using R Markdown

## II. Tests conducted:
1. Test the goodness of fit of a distribution using Chi-square: 
    - used to determine whether an observed set of data fits a particular theoretical distribution, such as the normal distribution or the Poisson distribution
    - the Chi-square statistic is calculated by taking the sum of the squared differences between the observed and expected frequencies, divided by the expected frequencies

2. Test two variables for independence using Chi-square
    - used to determine whether two categorical variables are independent of each other, often employed to analyze contingency tables
    - the Chi-square statistic in this case is calculated using the frequencies of two independent categories

3. Test homogeneity of proportions using Chi-square
    - used to determine whether two or more populations have the same proportion of individuals with a particular characteristic or attribute
    - it compares the observed proportions in each population to the expected proportions that would be obtained if the populations had the same proportion of individuals with the characteristic of interest

4. One-way ANOVA to see if there is a significant difference between pairs of means
    - tests whether there is a statistically significant difference in means across the groups, while taking into account the variability within each group
    - results determined by the F-statistic, which is the ratio of the between-group variability to the within-group variability

5. Two-way ANOVA to see if there is a significant difference in the main effects or the interaction between variables
    -  used to determine whether there is a significant difference in the means of two or more groups, while taking into account two categorical independent variables that may influence the dependent variable
    -  also computes the F-statistics for each of these components, and tests whether they are significant at the specified significance level
