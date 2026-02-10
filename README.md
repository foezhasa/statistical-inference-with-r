# statistical-inference-with-r
Quantitative Methods in Political Science: Homework 3

This repository contains the data analysis and statistical reporting for Homework 3 of the Quantitative Methods in Political Science course. The project focuses on the practical application of frequentist statistics, specifically regarding sampling distributions, confidence intervals, and hypothesis testing through both analytical and simulation-based methods.

🛠 Technical Skills Demonstrated

Statistical Software:

R (RMarkdown)

Methodology:

Analytical calculation of Standard Errors and Confidence Intervals

Monte Carlo simulations and bootstrapping for non-parametric inference

Probability density estimation and visualization

Subgroup analysis and difference-in-proportions testing

Packages used:

viridis (for color-blind friendly visualizations)

Project Overview
Part 1 & 2: Sampling Distributions & Merkel Ratings

Calculated the confidence intervals for approval ratings of Chancellor Merkel

Key Insight: Demonstrated how increasing sample size ($n=50$ to $n=150$) narrows the confidence interval, increasing the precision of the estimate

Simulation: Validated analytical results by simulating 10,000 sampling distributions

Part 3: The Smart Mannheim Students Problem

An investigation into IQ distributions and sampling bias

Analyzed the difference between observing an individual outlier versus a sample mean outlier

Visualizing Uncertainty: Generated a plot of 100 simulated confidence intervals to demonstrate that a 95% CI contains the true population mean in 95 out of 100 repeated trials, rather than containing 95% of individual data points

Part 4: Proportions & Plebiscite Validity

A forensic statistical look at a military dictator's claim of 68% voter support using a sample of 180 voters

Gender Gap: Calculated support rates between men (59%) and women (45%)

Findings: Using pnorm, determined the probability that the dictator's claim of 68% support is true given the sample data is statistically negligible ($p \approx 0$)

Conclusion: Provided statistical evidence to support claims of potential “foul play” in the reported election results

How to Run

Ensure you have RStudio installed

Clone this repository

Open Homework3.Rmd

The setup chunk will automatically check for and install the viridis package if missing

Click Knit to generate the PDF or Word report
