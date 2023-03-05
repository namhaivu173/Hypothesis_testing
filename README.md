<h1 align="center">
Chi Square & ANOVA hypothesis tests
</h1>

<p align="center">
<img src="https://www.investopedia.com/thmb/jgSEMXKV6NiQsbOGPw_ptsWtp8c=/750x0/filters:no_upscale():max_bytes(150000):strip_icc():format(webp)/Term-Definitions_hypothesistesting-4981dc2cf6024d7ca9f5497ab86cee73.jpg" alt="" title="" width="50%" height="50%">
</p>
<p align="center">
<i><sub>(Image Source: https://www.investopedia.com/terms/h/hypothesistesting.asp)</sub></i>
</p>


## I. Main goals:
- Practice using different hypothesis testing methods, including both parametric and non-parametric types:
    - Chi Square and Analysis of Variance (ANOVA) tests
    - Sign test, the Wilcoxon Rank Sum test, the Wilcoxon Signed-Rank test, the Kruskal-Wallis test, and the Spearman Rank Correlation Coeffcient test
- Create nice .pdf report using R Markdown

## II. Tests conducted:
### Part 1: Parametric tests
1. <b>Test the goodness of fit of a distribution using Chi-square:</b> used to determine whether an observed set of data fits a particular theoretical distribution, such as the normal distribution or the Poisson distribution

2. <b>Test two variables for independence using Chi-square:</b> used to determine whether two categorical variables are independent of each other, often employed to analyze contingency tables

3. <b>Test homogeneity of proportions using Chi-square:</b> used to determine whether two or more populations have the same proportion of individuals with a particular characteristic or attribute

4. <b>One-way ANOVA:</b> tests whether there is a statistically significant difference in means across the groups, while taking into account the variability within each group

5. <b>Two-way ANOVA:</b> used to determine whether there is a significant difference in the means of two or more groups, while taking into account two categorical independent variables that may influence the dependent variable

### Part 2: Non-parametric tests
1. <b>Sign Test:</b> used to compare the median of two paired groups or to test if a single sample median is equal to a known value

2. <b>Wilcoxon Rank Sum Test:</b> also known as the Mann-Whitney U test, is used to compare the median values of two independent samples and it is an alternative to the two-sample t-test when t-test's assumption is not met

3. <b>Wilcoxon Signed-Rank Test:</b> used to compare the median values of two related samples or to test if a single sample median is equal to a known value and it is an alternative to the paired t-test when t-test's assumption is not met

4. <b>Kruskal-Wallis Test:</b> used to compare the median values of two or more independent samples and it is an alternative to the one-way ANOVA when ANOVA test's assumption is not met

5. <b>Spearman Rank Correlation Coeffcient Test:</b> used to measure of the monotonic relationship between two variables, meaning that as one variable increases, the other either increases or decreases
