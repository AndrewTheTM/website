---
title: 'Precision and Accuracy in Travel Surveys'
categories:
  - Survey Manual
---
### Chapter-5-1

CHAPTER 5.0 PRECISION AND ACCURACY IN TRAVEL SURVEYS
====================================================

Note: Significant components of this chapter come from Tierney et al.’s FHWA Manual Introduction (Cambridge Systematics 1994). Other key contributors are Ho-Ling Huang, Peter Stopher and Clara Reschovsky.

Chapter needs: More current references & content. For example, precision & accuracy associated with new technologies (GPS, GIS, cell phone) are not discussed. Other issues noted in yellow highlight. 

5.1 Objectives of Survey Sampling
---------------------------------

A primary goal of most travel surveys is to collect data that allow analysts to estimate a range of travel-related and socioeconomic parameters that are often used to develop travel demand models, to meet other transportation planning needs, and to permit comparison to secondary data sources, such as census statistics, to determine the representativeness of the survey sample.

In collecting data from a sample of the population, measurement error can be divided into two types:

* Sampling errors; and* Non-sampling errors/biases.

The “total error” of a parameter estimate derived from a survey sample reflects both the sampling and non-sampling errors in the collected data.

Sampling errors are the random errors that are introduced into the survey simply because it is not possible for every member of the survey population to be included in the drawn sample.  **Sampling errors reflect the potential variability between the estimate of a parameter in the sample and its true value in the population.**  These errors affect the precision of the survey results.

Non-sampling errors arise from an assortment of problems that can occur during the survey design and data collection stages, which may cause survey measures and parameter estimates to be systematically incorrect.  **Non-sampling errors reflect how well the survey instrument is designed and the information is collected and includes non-response biases, caused by refusals and response biases which reflect a systematic distortion of survey responses.** These errors affect the accuracy of the survey results.

As a result, it can be stated that the goal of high quality sampling is to:

* Reduce sampling errors that can cause the parameter estimates and other measures to be imprecise; and* Reduce non-sampling errors or survey biases that can cause the measurements to be inaccurate.

To convey the concepts of accuracy and precision in travel surveys, Richardson, Ampt, and Meyburg (1995) use the analogy of sharpshooters firing at a target. Figure 5.1 shows four ways in which a target shooter can hit a target (Richardson, Ampt, and Meyburg, 1995). The top left target shows the results of a shooter who is both accurate (shots are centered on the bull’s eye) and precise (shots are all consistent with each other). The top right target shows the results of a precise, but inaccurate shot. This marksman’s shots are consistent with each other, but are not on target. The bottom left target shows the results of an accurate, but imprecise shooter. The shots are centered on the bull’s eye, but they are not well-grouped. The final bull’s eye shows the results of a marksman who is neither accurate nor precise in his shooting.

In travel surveys, as in this analogy, precise parameter estimates are reliable and consistent whether they are accurate or not. By increasing the sample size, travel surveyors can improve the precision of parameter estimates. This is because with a larger sample, the probability that units outside the sample have different characteristics due to chance is reduced. As with the targets in the analogy, survey accuracy is defined by how well a parameter estimate conforms to the true parameter value in the population (as illustrated by the bull’s eyes). 

Note: Stratification and other methods can also be introduced to reduce sampling error, if appropriate sample frames exist.

Because we can see the targets in Figure 5.1, we are able to make judgments about the success of the different marksmen. Clearly, the top left target where shots are both precise and accurate is the best outcome, while each of the others leaves something to be desired. Most people would also argue that the bottom left target (accurate although imprecise shots) represents the second best outcome because the shots are on target at least, with the other targets being less desirable.

This later condition is the one faced by travel surveyors. The actual values of model inputs and parameters are not known – that is exactly why the survey is being conducted. Travel surveyors are left with the challenging task of expending scarce study resources to determine the appropriate levels of precision and accuracy in parameter estimates without benefit of the knowledge of the true answers.

![](../attachments/153443000000031029_1.0)

 Source: A.J. Richardson, Elizabeth Ampt, and Amim Meyburg, Survey Methods for Transport Planning, Eucalytus Press, Melbourne, 1995.

Figure 5.1   The Sharpshooters: An Analogy for Survey Accuracy and Precision 

The “total error” of a parameter estimate, derived from data collected through a survey, is a combination of both the imprecision and inaccuracy in the survey data.  The mean squared error (MSE) is the corresponding measure of “total error” and is related to the level of precision and accuracy in the survey data as follows:

![](../attachments/153443000000031033_1.0)  <!--[if !vml]--><!--[endif]-->   (Eq. 5.1)

where *SE* = the standard error of the estimate (a measure of sampling precision); and *B* = the combination of all biases in the estimate (a measure of accuracy).

In cases where the standard error (*SE*) of the estimate is very large compared to the bias (*B*), the “total error” of the estimate is primarily a reflection of the imprecision of the survey data.  Alternatively, in cases where the precision of the survey data is satisfactory leading to low *SE* values, the “total error” of the estimate primarily reflects the inaccuracy of the survey data and the corresponding biases (*B*).

The next several sections of this chapter (Section 5.2 through 5.8) discuss how survey precision levels can be quantitatively measured and how they are influenced by sample size.  The last section of the chapter (Section 5.9) then discusses bias and accuracy issues.  Unfortunately, determining the level of accuracy (bias) of survey data almost always has to be a somewhat qualitative exercise.  Therefore, the most practical approach for tackling this problem is to take the steps, and spend the resources necessary to feel comfortable that the parameter estimates are reasonably accurate and free of bias – that is, to feel fairly sure that the marksman is on target, and then to spend the remaining resources to improve the precision of estimates (primarily by increasing the sample size, or using a more complex sampling method to reduce sampling error).

Note: For added, thoughtful exposition of these and other survey features, readers will do well to read Richardson et al. (1995) or Peter Stopher’s forthcoming book.

5.2 Sampling Methods and Sample Design
--------------------------------------

The development of a sample design can be characterized as an iterative process that is driven in part by the overall objectives of the survey but is often constrained by the limited resources and the information that is readily available on variables of interest.  The key issues associated with sample design are summarized in Figure 5.2, which provides a step-by-step approach that could ideally be used to address each of the different dimensions of the sample design process.

![](../attachments/153443000000034001_1.0)

Figure 5.2 Key Issues in Sampling for Travel Surveys

**What are the Primary Objectives and Constraints of the Survey?**

Often, there will be considerable uncertainty surrounding each of the key issues associated with sample design.  For example, a travel survey may serve a variety of multiple objectives, making it difficult to define a limited number of variables of interest that could be used as criteria of precision.  Furthermore, the limited available resources often dictate the survey design and methods.  Finally, the sample size calculations are often based on a range of assumptions about the distribution of the variable of interest in the study population.  In light of the uncertainty that may underlie different aspects of sample design, it would be useful to adopt an iterative approach to sample design, recognizing the interrelated decisions on different aspects of sample design and the limitations of the available information used to develop a sample design.

Therefore, to collect travel data for the development of policy-sensitive and statistically robust demand model inputs and parameters, it is important to identify and determine the following during the sample design process:

* The information that needs to be collected through the survey to provide the greatest degree of support to transportation planners and decision-making agencies;* The study population of interest whose travel patterns need to be understood and for which data need to be collected;* The appropriate sampling frame that has an exhaustive list of members of the study population from which respondents can be drawn;* The sampling unit that is required to provide the necessary information at the level of detail that is needed for the proposed analyses;* The constraints and their impacts on survey and sampling methods; and* The sample size that is required to measure the socioeconomic characteristics and travel behavior of the study population in a precise and accurate manner and to provide policy sensitive and statistically robust inputs to modeling.

In the following sections, we adopt a step-by-step approach to sample design and focus on each of the key issues presented in Figure 5.2.

The development of the sample design, the travel survey instrument, and the data collection method should ideally be driven by the overall objectives of the analysis. Common objectives include the design of a travel demand model, evaluation of transport policies, and/or anticipating public opinion regarding certain agency actions. The sample size requirements would thus account for the needs of the analytical system. Such an approach to sampling methodology, sampling frame, sampling unit, and sample size determination would focus on each analytical component and account for the critical variables most likely to be used in each stage.

However, the available resources allocated to the development and analysis of a survey often dictates different aspects of the travel survey development and data collection.  Budgets are often set prior to any technical analysis related to sample design, so that the determination of sample size often poses more challenges because of the need to keep within a predetermined budget.  Furthermore, since data collected through travel surveys may be used to support a variety of different travel modeling analyses (e.g., trip generation, trip distribution, mode choice, time-of-day) over prolonged periods of time, as well as a variety of policy analyses and other potential uses, data may also be used for purposes that were not initially intended or expected.  As a result, it is often difficult to identify a single measure or a limited set of measures that could be used as the ultimate criterion for developing an optimal sample design (Fielding and Gunn, 1985).

Although the budgetary constraints and multiple objectives of a survey further complicate the analysis for sample size requirements, it is important to recognize them as potential limitations and undertake an analysis to assess their impacts on the precision of the data that will be collected.  Such an analysis allows the examination of the tradeoffs between sample size for the whole sample and the expected degree of precision for variables that may be critical to the analysis.  Similarly, the analysis of the tradeoffs between sample size and precision can also be repeated for market segments of particular interest to the analysis.

What are the Variables of Greatest Interest and the Desired Level of Precision?
-------------------------------------------------------------------------------

The identification of the variables of interest follows directly from the explicit definition of the objectives of the travel survey. A list of variables of interest that are considered critical to the analysis and reflect the primary analysis objectives can be listed both for the whole sample and/or for market segments of particular interest.

For example, a travel survey that is geared towards developing trip generation models may require a desired level of precision for variables that reflect the travel patterns of a household or an individual respondent, such as the total number of daily trips, the trip rate per household member, or the mix of trip purposes.  Such a survey would likely focus on determinants of trip making including socioeconomic characteristics such as household size, number of workers in the household, income, or the level of automobile ownership.

Similarly, a travel survey that will be developed to estimate the mode choice behavior of commuters may focus either on the observed mode choice behavior by seeking a precise estimate of the transit market share for the whole sample, or for distinct market segments of interest.  In this case, the survey should focus on the variability of variables that determine respondents’ mode choice behavior, including the distribution of travel times and costs experienced by travelers in the study area.

The definition of a set of variables that are of greater importance to the survey and the corresponding analyses is critical in determining the required sample size.  In the step-by-step approach outlined in Section 5.4, sample size requirements are assessed by using a single variable of interest, with a known mean and variability in the study population.  The sample size estimation process can be repeated for each variable of interest and under a variety of desired precision and statistical significance options to arrive at a sample size that satisfies the requirements of the analysis.

Finally, the same process can be repeated for each market segment of interest.  In such a case, the objective of the analysis would be to ensure an adequate sample size for each distinct market segment of interest so that the estimates obtained within each of those segments would be sufficiently precise.

How Should the Study Population, Sampling Frame, and Unit Be Defined?
---------------------------------------------------------------------

The definition of the *study population*, discussed in Section 3.2, is critical in determining the respondents who would be eligible to be included as part of the study.

Following the definition of the study population, a sampling frame provides the means to reach each member of the study population who would be eligible to be surveyed.  A potential limitation of a sampling frame is that it may provide only a partially complete list of all eligible sampling units and may thus require to be augmented by additional sources.  When two or more data sources need to be combined, care must also be taken to minimize the duplicate entries and potential inconsistency that may appear in both sampling frames.  However, in travel surveys, sampling frames often do not exist, and would be inordinately expensive to create.  This may limit the sampling procedures by requiring that a representative sample is drawn using a procedure that does not require a sampling frame. In other cases, a multi-stage sampling method may be needed to get around the lack of a complete sampling frame.

Finally, the definition of a sampling unit is related to the type of information that needs to be collected and the desired degree of detail in the data.  For example, a study focusing on transit users’ travel patterns will be limited to collecting information from transit riders, while a survey aimed at analyzing activity patterns may use the household or the individual as the sampling unit.

**What Information Is Readily Available on the Variables of Interest?**

The calculation of the required sample size can be undertaken for each unknown outcome or random variable for which a certain level of precision is required.  However, the sample size calculations based on a particular random variable rely in turn on existing values for the mean and the variability of that variable in the study population.  Thus, it is important to define early in the sample design process different sources that could provide such information including:

* Recent household and/or travel survey(s) undertaken in the same study area;* Surveys in the study area that may have been collected for different purposes;* Recent household and/or travel surveys undertaken in another study area with similar characteristics to the study are of interest;* Expert or review panels and/or staff from local agencies familiar with the area;* The most recent Decennial Census or another national level demographic survey  (e.g., the US Census Bureau’s American Community Survey), should socioeconomic and travel-related information at different levels of geographic detail;

(A quick aside about using ACS: The ACS is different from traditional Decennial Census data in that it is collected all the time. It is NOT point in time data. The first question to ask is one-year data, 3-year data, or 5-year data. They are (and will be) available for different geographies. The next question is whether to trust the household totals or the person totals. They are controlled separately. As with any data set, ACS has its own peculiarities, but they are different from those that were fairly well known with Decennial data, thus all users of the data need to be mindful that they need to clear their mind of the past and start over in their critical assessment of data quality. It is becoming apparent that there are idiosyncrasies that pop up for specific geographies making it very difficult to assess any real bias in the ACS, but at the same time making it difficult to evaluate as a control for developing other surveys.)

These sources would be part of the background data assembly task, discussed in Section 2.2.

**Which Sampling Method Should be Used to Meet the Precision Requirements?**

The selection of a sampling method is interrelated with the broad objectives of the survey; the study population, and the corresponding appropriate sampling frame, and sampling unit; and the desired level of precision (Churchill, 1984).  Sampling methods can generally be classified in three different ways.  These categories differentiate probability versus non-probability sampling methods; single- versus multi-stage sample selection methods; and methods with a uniform versus differential probability of selecting an element in the population.

The *non-probability* methods can be used only in cases where the survey is not used to make inferences about the travel characteristics or the travel behavior of the study population as a whole.  Non-probability samples are not representative of the population from which they are drawn and are usually used only for exploratory purposes.  The non-probability methods include:

* Convenience sampling such as the administration of a travel survey of workers in a single office building;* Judgment sampling such as the administration of a vehicle ownership survey to residents of a higher-income suburb; and* Quota sampling such as the completion of 50 surveys per city block irrespective of and without controlling for differences in residential density.

In most cases, however, it is necessary to use a probability sampling method (or a close approximation to a probability sampling method) to obtain statistically valid estimates of population characteristics.  This requires the advance knowledge of, or the ability to assess, the probability of selection for each member of the sample.  To accomplish that, a probability sampling method is used where each sampling unit has a non-zero probability of being selected as part of the sample; this probability can be estimated by the analyst. Since this represents the situation for most travel surveys, the remainder of this chapter focuses on probability-based methods.

Probability sampling methods also allow the analyst to define different probabilities of selection for elements of the population in particular segments of the market and, accordingly, expand the sample to make it representative of the study population.  The probability sampling methods allow statistically valid inferences to be made about the population as a whole and include (Richardson, Ampt, and Meyburg, 1995):

* Simple random sampling where each population element has the same probability of being chosen;* Stratified sampling where the population is divided into smaller groups and a random sample is chosen within each group;* Cluster sampling where a sample of groups is selected and every member of the group is selected; and* Choice-based sampling which is a special case of stratified sampling and groups are formed based on an endogenous variable; and * Systematic sampling where sample items are chosen in a systematic manner (e.g., every 20th name in a telephone directory). (Note: Systematic sampling is not a true probability sampling method, but is an approximation to a probability sample.)

The differences among these methods and their relative merits are described in detail in Section 5.8.  The final choice of sampling method depends on the distribution of the variables of interest among the population. If all variables of interest – for example, auto ownership levels, household size, income levels, mode shares, etc. – are evenly distributed in the population, then a simple random sample of sufficient size may provide adequate representation of all variables.  However, it is often the case that a very large simple random sample would be needed to obtain a sufficient representation of different values for particular variables.  For example, there may be few households without cars, or few users of a particular mode of travel. In this case, a stratified or choice-based sampling plan may be required.  The choice of sampling method must be made in conjunction with the definition of sample size and the constraints on existing resources.

What Sample Size is Required to Satisfy These Precision Requirements?
---------------------------------------------------------------------

To estimate the total sample size needed to measure the variables of interest with a pre-determined desired degree of precision or level of confidence, the mean value of the variable and its variability in the population need to be known.  Assuming that the sample method, sampling frame, and sampling unit have been determined and that the proposed data collection method minimizes the sampling bias, the calculation of sample size can be viewed from two different perspectives. The analyst may be interested in determining:

* The sample size that would be required to provide a desired degree of precision under a specific level of statistical confidence for each of the variables of interest; or alternatively * The precision or level of confidence that can be expected for each variable of interest by collecting information from a given sample size.

The process of determining sample size and relating it to precision and level of confidence can be conducted either for the whole sample or for individual market segments of greater interest.  Although the same sampling principles are used in both cases, collecting an adequate sample for different market segments is expected to result in a larger sample size than would be required for the whole sample under the same precision and level of confidence requirements.

Are There Enough Resources to Collect Such a Sample?
----------------------------------------------------

The sample size calculations will result in a range of sample size estimates that would be necessary to satisfy the level of confidence and degree of precision desired for each of the variables of interest.  However, it is likely that the cost of the survey effort based on the calculated sample sizes may exceed the budget allocated for the survey.  If budget constraints dictate a sample size that is smaller than the “ideal” calculated sample size, the corresponding degree of precision and/or the level of confidence would be lower for at least some of the variables of interest.

In such a case, the methodology for sample size calculations can be used further to address the tradeoffs between various sample sizes and the corresponding degree of precision and level of confidence.  Furthermore, at this stage it is important to explore whether different sampling methods such as stratification, cluster, or choice-based sampling can be used to improve the expected precision and level of confidence of particular variables either for the whole sample or for the market segments of greatest interest to the analysis.

What is the Precision and Confidence Level Corresponding to a Smaller Sample Size?
----------------------------------------------------------------------------------

The same methodology used for sample size calculations can be used to quantify the tradeoffs between sample size, the level of confidence, and the degree of precision.  However, instead of calculating the sample size required for a desired degree of precision and level of confidence for the variables of interest, the question needs to be restated. That is, the objective of the analysis is now to calculate the level of confidence and degree of precision corresponding to sample sizes that would be smaller than the “ideal” sample size.  Such calculations allow the analyst to finalize the iterative sample design process by identifying the tradeoffs among sample size, level of confidence and degree of precision, and recognizing the strengths and weaknesses of each alternative sampling plan.

Finally, although smaller sample sizes would result in less precise estimates for some variables, a new travel survey would still provide a wealth of updated detailed data.  Thus, a new survey is likely to offer a considerably more accurate picture of travel patterns and socioeconomic characteristics than older data sources that are probably used for planning purposes.

5.3 A Brief Discussion of Sampling Principles
---------------------------------------------

A core issue in sampling design is cost of data acquisition, and how one selects sample size (where larger sample sizes results in greater precision) and data quality (where higher quality data result in less bias).  Because travel surveys are used to make inferences about the characteristics and the travel behavior of the study population, it is important to determine the range of sample sizes that would be required to achieve a desired level of precision and level of confidence for selected variables of interest.  Alternatively, it is equally important to determine the degree of precision and level of confidence that would be expected for each variable of interest under a range of sample sizes.  Thus, the analysis of sample size seeks to measure the tradeoffs between sample size and the corresponding levels of precision and confidence that can be achieved for selected variables of interest.

Sample size is determined by the distribution of values for the variable of interest as well as by the desired degree of precision and level of statistical significance or confidence. The two pieces of information that convey the information about the distribution of the variable of interest in the study population include:

* The mean value of the variable in the study population; and* A measure of its variability in the study population.

The mean value (m) provides a measure of the central tendency of the variable while its variance (σ2) and standard deviation (σ) provide measures of the variability/spread of the variable values (Table 5.1).   Similarly, the coefficient of variation (CV), which is equal to the ratio of the standard deviation of the variable and its mean, provides a measure of the relative variability of the variable values around the mean.

The most commonly used estimator in sample size determination is the average value of a variable in the sample denoted by <!--[if !vml]--><!--[endif]-->![](../attachments/153443000000031001_1.0).   The sample average (![](../attachments/153443000000031001_1.0)) is an estimator of the true mean value in the study population (m) and its standard error SE (![](../attachments/153443000000031001_1.0)) provides the basis for estimating sample size.   The standard error of the sample mean ![](../attachments/153443000000031001_1.0) depends on the variability of the variable in the population (as reflected by its variance, σ2) and the sample size (n) and is equal to:

![](../attachments/153443000000031005_1.0)

This suggests that for a given variability of the variable x in the population (given by σ 2) the standard error can be reduced by increasing the sample size (*n*).  Furthermore, for a given sample size (*n*) the magnitude of the standard error will reflect the spread of the variable values in the population as captured by the variance (σ2).  In cases where the variable values are clustered closely around the mean, the standard error will be small; in cases where the variable values are spread out, the standard error will have a correspondingly higher value.

The other two pieces of information that are used to determine sample size relate to the desired value of the standard error are:

* The degree of precision required for the analysis; and* The desired confidence/statistical significance that corresponds to the estimates used in the analysis.

Table 5.1 Notation Used in Sample Size Estimation [Notation used in scanned tables is non-standard. Population mean should be m & std dev should be s. Confidence levels also need some appropriate notation, e.g., “C”.]

![](../attachments/153443000000034005_1.0)

*A discrete variable *xi* takes a value of 1 if true and 0 otherwise for example, to calculate transit market share, a value of 1 is used for transit riders and a value of zero for all others. The proportion of transit riders, p, is equal to: 

![](../attachments/153443000000034009_1.0)

These two pieces of information can in turn be used to calculate the desired standard error of the average under a variety of precision and level of confidence scenarios.  As outlined in Section 5.4, the integration of the formulas that calculate the standard error of the average, and the corresponding desired standard error, allows the calculation of the sample size for a variable with a given population mean and variance and under the desired precision and level of confidence. Because both of these dimensions of the sample design reflect the ability of the sample to precisely measure the variable of interest, to achieve a higher level of desired precision and/or statistical confidence a larger sample would be needed, all other things being equal.

The degree of precision can be expressed either as an absolute (D) or as a relative deviation (d) from the mean variable value (Table 5.1). It reflects the difference between the true mean in the population and its estimate of the average from the sample.  Thus, for a study population characterized by an average income of $45,000, the desired degree of precision could be expressed as a D=+$1,800 or as a d=+4 percent deviation from the mean income. As either measure of deviation decreases, the size of the sample required to achieve the corresponding degree of precision increases.

The level of confidence (1) is expressed as a percentage. It represents the probability that a sample drawn under the same circumstances from the same study population will result in an estimate of the mean value that is within the given degree of precision. The level of confidence is reflected on the corresponding z-statistic value taken from the standard normal distribution. The higher the desired level of confidence in the sample estimates, the larger is the sample size required.

5.4 Calculation of Sample Size for a Simple Random Sample
---------------------------------------------------------

Note: This section needs significant revision, for clarity.
-----------------------------------------------------------

The simple random sampling method provides a foundation for other more complex probability sampling methods. Under the simple random sampling method, each population unit has an equal probability to be selected.

To estimate the sample size needed to measure any variable with a predetermined degree of precision, the following information is required:

* The mean value of the variable in the study population;* A measure of the variability of this variable in the study population;* The desired degree of absolute or relative precision; and* The desired statistical level of confidence.

The process of calculating the required sample size for a study based on a simple random sample can be illustrated best by using an example of a hypothetical household travel survey.  A Metropolitan Planning Organization (MPO) that covers an area with a population of about 200,000 residents and 120,000 households, is interested in conducting a household travel survey to understand better the travel behavior of study area residents.

To accomplish that, the agency planners need to draw a representative sample of households in the study area.  The study area is characterized by differences in income that are believed to have an important effect on the travel options available to its residents and their mode choices and travel behavior.  Furthermore, one of the primary thrusts of the modeling effort would be to model the determinants of transit market share.  As a result, the sample size calculation process needs to be repeated twice, once using household income as the variable of interest and again using the transit market share as the variable of interest.

To account for the variability in the study population and to obtain measures with a reasonable degree of precision, the MPO staff want to collect a large enough sample that will allow them to estimate the household income within +4% of the mean household income which is currently $45,000.  Furthermore, to assess the determinants of transit market under a variety of service improvements, MPO planners want to collect enough observations so that transit share estimated from the survey is within +10% of the observed transit market share of 15 percent.  For both the household income and the transit market share estimates that will be obtained from the household survey, MPO planners want to have a 95 percent confidence level.

The formulas that are used in the sample size calculations are summarized in Table 5.2.  For all practical purposes, the “correction” that applies to the sample variance (s2) estimate that enters Equation 5.9a has a negligible impact on sample size and can safely be omitted.  Thus, the remainder of this chapter will rely on the formulas assuming the population variance σ in Table 5.2 and Equations 5.2 to 5.9.

The sample size calculations based on household income are presented in Table 5.3 while the sample size calculations that are based on the transit market share are shown in Table 5.4.  As shown in Table 5.3, a sample size of just under 500 observations is needed to ensure that the estimate of average household income from the survey would be within four percent of the mean income value in the population at a 95 percent confidence level.  Similarly, about 710 observations would be needed to estimate transit market share from the survey at the desired precision and confidence levels.  As a result, a sample size of 750 observations would ensure that both variables of interest would be estimated satisfactorily from the collected survey data.

Table 5.2 Formulas Used in Sample Size Estimation based on Population Variance

![](../attachments/153443000000031017_1.0)

Table 5.3 Sample Size Estimates based on Household Income

![](../attachments/153443000000031021_1.0) 

 Table 5.4 Sample Size Estimates Based on Transit Market Share

![](../attachments/153443000000031025_1.0)  **A Step-by-Step Approach to Sample Size Determination**

In addition to above tables, a step-by-step approach to sample size calculations that outlines in greater detail each of the formulas used in calculating sample size based on the household income variable is presented below.

***Step 1: Estimate the Mean and Standard Deviation or the Coefficient of Variation***

First, estimates of the mean value and its corresponding standard deviation for household income need to be made.  These two measures provide a snapshot of the income distribution and can be calculated based on previous surveys, census data, or can be derived from estimates provided by other analysts and expert panels.

Mean: m = $45,000 (See Eq. 5.2)

Standard deviation: σ = $20,000 (See Eq. 5.3)

In cases where the mean and the standard deviation are not known and cannot be estimated with a reasonable degree of confidence, the coefficient of variation could also be used.  This measure reflects the relative magnitude of the standard deviation with respect to the mean and provides a measure that is readily comparable across different application environments and travel surveys.

Coefficient of variation: CV = σ/m = $20,000/$45,000 = 0.444 (See Eq. 5.5)

***Step 2. Set the Desired Confidence Level***

The desired statistical confidence level is set by selecting a confidence level and calculating the corresponding value for the z-statistic.  The values most often used in sample design and statistical analyses are the 95 percent confidence level (since a 5-percent rate of error is often acceptable) and the corresponding z-statistic value of 1.96.  Although the z-statistic values vary with the sample size, for a sample with 1,000 or more observations, the values in Table 5.5 can be used.

***Step 3. Determine the Desired Degree of Precision***

The acceptable range around the mean household income value reflects the degree of precision that is desired for the household survey estimates of income.  The desired degree of precision could be defined as relative (e.g., precision within +4 percent of the mean) or absolute (e.g., deviation of +$1,800 from the mean).

Relative precision: d = ± D/m = ±4%

Absolute precision: D = ±$1,800

***Step 4. Calculate the Standard Error of the Average***

The desired standard error of the average (SE (![](../attachments/153443000000031001_1.0))) encompasses three pieces of information that are important in sample size determination: the mean (μ) of the variable in the study population, the desired degree of precision (D or d), and the desired confidence level in the estimate from the survey (z statistic).  By applying Equation 5.7, we obtain:

SE***(***![](../attachments/153443000000031001_1.0)) = <!--[if !vml]--><!--[endif]--> ![](../attachments/153443000000031037_1.0)  12â‡’"> <!--[if !vml]--><!--[endif]--> ![](../attachments/153443000000031045_1.0) SE***(***![](../attachments/153443000000031001_1.0)) ***=*** <!--[if !vml]--><!--[endif]--> ![](../attachments/153443000000031041_1.0)12â‡’"> <!--[if !vml]--><!--[endif]--> ![](../attachments/153443000000031045_1.0) SE***(***![](../attachments/153443000000031001_1.0)) ***=*** ![](../attachments/153443000000031049_1.0) <!--[if !vml]--><!--[endif]--> = $918.40

***Step 5. Calculate the Uncorrected Sample Size***

An initial value of sample size can now be provided.  This uncorrected sample size value does not account for the size of the study population and may thus require a correction for the potential finite population effect.  By applying Equation 5.8 we obtain:

Uncorrected Same Size: n´ = ![](../attachments/153443000000031053_1.0) <!--[if !vml]--><!--[endif]-->= 474 obs.

 

Table 5.5 Correspondence Between Confidence level and z-Statistic Values ![](../attachments/153443000000034013_1.0)

1R.J. Jessen. *Statistical Survey Techniques,* Wiley, 1978.

***Step 6. Adjust Sample Size for the Finite Population Correction***

A finite population adjustment is not critical if the population for which we wish to draw inferences is rather large.  However, such an adjustment may have a measurable impact if the sample estimate is smaller than 10 percent of the study population.  To adjust for the finite population correction, an estimate of the size of the study population is needed.  Assuming a population size of N = 120,000 households and by applying Equation 5.9, we obtain:

Corrected Sample Size: ![](../attachments/153443000000031057_1.0)

5.5 Sensitivity of Sample Size to its Determinants
--------------------------------------------------

It is important to realize that the required sample size for a simple random sample depends on a multitude of variables (see Table 5.2).  Key variables include the desired confidence interval and level of precision, the mean and standard deviation (or variance) of the variable in the population, and the size of the population.  This section demonstrates the sensitivity of the sample size requirement to each of these variables, using the example of the previous section.  It should be noted that although the patterns noted here would hold for almost any travel survey context, some of the results shown are specific to this application.  A sensitivity analysis that is tailored to any problem under study can be set up in a spreadsheet using similar table structure and the equations presented in Section 5.4.

Sensitivity to Confidence Level
-------------------------------

Table 5.6 shows that the required sample size is extremely sensitive to the chosen confidence interval.  Dropping the confidence level from 95 percent to 90 percent in the example would result in a reduction in sample size by about 30 percent.  Conversely, increasing the confidence level to 99 percent would result in a 75 percent increase in the required sample size. Since the required sample size is proportional to the square of the z-statistic (as shown in Equations 5.7 and 5.8), the percentage changes in the sample size would hold for any sample size computation.  Given the cost implications of different sample sizes and the fact that the survey analyst can choose the desired confidence interval, this is a significant observation.

Table 5.6 Sensitivity of Sample Size to Confidence Level

![](http://wiki.zoho.com/pluginImg.zhtml?n=style&hei=20&wid=100) 

| Population Size | Mean | Standard Deviation | Confidence Level | z-Statistic | Relative Precision | Standard Error | Sample Size |
| N | m | s | C | z | d | SE( <!--[if !vml]--><!--[endif]-->) | n´ | n |
| 120,000 | $45,000 | $20,000 |  50.0% | 0.67 |  4.0% | $2,687 |  55 | 55 |
| 120,000 | 45,000 | 20,000 | 60.0 | 0.84 | 4.0 | 2,138 |  88 | 87 |
| 120,000 | 45,000 | 20,000 | 70.0 | 1.04 | 4.0 | 1,731 |  134 | 133 |
| 120,000 | 45,000 | 20,000 | 80.0 | 1.28 | 4.0 | 1,404 |  203 | 203 |
| 120,000 | 45,000 | 20,000 | 90.0 | 1.64 | 4.0 | 1,095 |  334 | 333 |
| 120,000 | 45,000 | 20,000 | 95.0 | 1.96 | 4.0 | 918 |  474 | 472 |
| 120,000 | 45,000 | 20,000 | 99.0 | 2.58 | 4.0 | 698 |  822 | 816 |
| 120,000 | 45,000 | 20,000 | 99.9 | 3.29 | 4.0 | 547 | 1,336 | 1,322 |



Sensitivity to the Desired Degree of Precision

Table 5.7 shows that the required sample size is even more sensitive to the desired level of precision.  Equation 5.8 in Table 5.2 shows that the sample size is inversely proportional to the square of the desired precision level.  So doubling the precision level would cut the required sample size by three quarters; while halving the level would quadruple the required sample size.  The implications of this sensitivity are tremendous given the analyst’s ability to choose the desired precision level.

Care must be taken, however, not only in defining the precision level, but the variables to be analyzed.  For example, say an area has existing mode shares of two percent transit and 98 percent auto.  If auto mode share is chosen as the analysis variable, a one percent or two percent precision level appears quite reasonable, and choosing the two percent level would require only one quarter of the sample size required for one percent.  However, this implies going from a 50 percent precision level for the estimate of transit mode share to 100 percent.  In this case, it would make sense to choose the transit mode share as the variable of interest.  Of course, since this variable would have a much lower mean, the resulting required sample size, even if the level of precision went up to five percent or even 10 percent, would still be greater than that for the auto mode share since the mean is much smaller (see Equations 5.7 and 5.8 and Table 5.8).

Sensitivity to Mean and Standard Deviation
------------------------------------------

Since the required sample size is inversely proportional to the square of the mean and directly proportional to the variance of the analysis variable, differences (or errors) in the mean and the variance can have a significant effect on the sample size requirement.  For example, Table 5.8 shows that a 10 percent change in the mean results in approximately a 20 percent change in the sample size requirement.  Table 5.9 shows similar results for changes in the standard deviation.  Given the uncertainty of estimates of means for certain variables, especially those not included in census data, this table demonstrates the caution that must be applied when determining sample sizes based on outside data sources.

Sensitivity to Population Size
------------------------------

Table 5.10 shows the sensitivity of the required sample size to the population size.  For large populations of over 50,000, the sample size is within one percent of the theoretical maximum given the population mean and variance and the desired precision and confidence level. For smaller populations (which, except in small MPOs or cities, would imply some sort of market segmentation), the sample size could be reduced somewhat.

Table 5.7 Sensitivity of Sample Size to Desired Degree of Precision



| Population Size | Mean | Standard Deviation | Confidence Level | z-Statistic | Relative Precision | Standard Error | Sample Size |
| N | m | s | C | z | d | SE () | n´ | n |
| 120,000 | $45,000 | $20,000 |  95.0% | 1.96 |  0.5% | $ 115 | 30,353 | 24,226 |
| 120,000 | 45,000 | 20,000 | 95.0 | 1.96 | 1.0 | 230 | 7,588 | 7,137 |
| 120,000 | 45,000 | 20,000 | 95.0 | 1.96 | 2.0 | 459 | 1,897 | 1,868 |
| 120,000 | 45,000 | 20,000 | 95.0 | 1.96 | 3.0 | 689 | 843 | 837 |
| 120,000 | 45,000 | 20,000 | 95.0 | 1.96 | 4.0 | 918 | 474 | 472 |
| 120,000 | 45,000 | 20,000 | 95.0 | 1.96 | 5.0 | 1,148 | 304 | 303 |
| 120,000 | 45,000 | 20,000 | 95.0 | 1.96 | 10.0 | 2,296 | 76 | 76 |
| 120,000 | 45,000 | 20,000 | 95.0 | 1.96 | 15.0 | 3,444 | 34 | 34 |
| 120,000 | 45,000 | 20,000 | 95.0 | 1.96 | 20.0 | 4,592 | 19 | 19 |
| 120,000 | 45,000 | 20,000 | 95.0 | 1.96 | 25.0 | 5,740 | 12 | 12 |
| 120,000 | 45,000 | 20,000 | 95.0 | 1.96 | 30.0 | 6,888 | 8 | 8 |
| 120,000 | 45,000 | 20,000 | 95.0 | 1.96 | 40.0 | 9,184 | 5 | 5 |
| 120,000 | 45,000 | 20,000 | 95.0 | 1.96 | 50.0 | 11,480 | 3 | 3 |
<><!--[if !supportMisalignedColumns]--> |  |  |  |  |  |  |  |  |  |  |  |  |

Table 5.8 Sensitivity of Sample Size to the Mean



| Population Size | Mean | Standard Deviation | Confidence Level | z-Statistic | Relative Precision | Standard Error | Sample Size |
| N | m | s | C | z | d | SE () | n´ | n |
| 120,000 | $10,000 | $20,000 | 95.0% | 1.96 |  4.0% |  $ 204 | 9,604 | 8,892 |
| 120,000 | 25,000 | 20,000 | 95.0 | 1.96 | 4.0 | 510 | 1,537 | 1,517 |
| 120,000 | 30,000 | 20,000 | 95.0 | 1.96 | 4.0 | 612 | 1,067 | 1,068 |
| 120,000 | 35,000 | 20,000 | 95.0 | 1.96 | 4.0 | 714 | 784 | 779 |
| 120,000 | 40,000 | 20,000 | 95.0 | 1.96 | 4.0 | 816 | 600 | 597 |
| 120,000 | 45,000 | 20,000 | 95.0 | 1.96 | 4.0 | 918 | 474 | 472 |
| 120,000 | 50,000 | 20,000 | 95.0 | 1.96 | 4.0 | 1,020 | 384 | 383 |
| 120,000 | 60,000 | 20,000 | 95.0 | 1.96 | 4.0 | 1,224 | 267 | 266 |
| 120,000 | 70,000 | 20,000 | 95.0 | 1.96 | 4.0 | 1,429 | 196 | 196 |
|  |  |  |  |  |  |  |  |  |  |  |
<><!--[endif]--> 
Table 5.9 Sensitivity of Sample Size to Standard Deviation



| Population Size | Mean | Standard Deviation | Coefficientof Variation | Confidence Level | z-Statistic | Relative Precision | Standard Error | Sample Size |
| N | m | s | CV | C | z | d | SE() | n´ | n |
| 120,000 | $45,000 | $ 5,000 | 0.111 |  95.0% | 1.96 |   4.0% |  $ 918 | 30 | 30 |
| 120,000 | 45,000 | 10,000 | 0.222 | 95.0 | 1.96 | 4.0 | 918 | 119 | 118 |
| 120,000 | 45,000 | 15,000 | 0.333 | 95.0 | 1.96 | 4.0 | 918 | 267 | 266 |
| 120,000 | 45,000 | 20,000 | 0.444 | 95.0 | 1.96 | 4.0 | 918 | 474 | 472 |
| 120,000 | 45,000 | 25,000 | 0.556 | 95.0 | 1.96 | 4.0 | 918 | 741 | 736 |
| 120,000 | 45,000 | 30,000 | 0.667 | 95.0 | 1.96 | 4.0 | 918 | 1,067 | 1,056 |
| 120,000 | 45,000 | 40,000 | 0.889 | 95.0 | 1.96 | 4.0 | 918 | 1,897 | 1,862 |
  
|  |  |  |  |  |  |  |  |  |  |  |  |  |

Table 5.10 Sensitivity of Sample Size to the Finite Population Correction



| Population Size | Mean | Standard Deviation | Confidence Level | z-Statistic | Relative Precision | Standard Error | Sample Size |  Ratio |
| N | m | s | C | z | d | SE( <!--[if !vml]--><!--[endif]-->) | n´ | n | n/n´ |
| 500 | $45,000 | $20,000 |  95.0% | 1.96 |  4.0% | $918 | 474 | 243 |  51.3% |
| 1,000 |  45,000 |  20,000 | 95.0 | 1.96 | 4.0 |  918 | 474 | 322 | 67.8 |
| 2,000 |  45,000 |  20,000 | 95.0 | 1.96 | 4.0 |  918 | 474 | 383 | 80.8 |
| 3,000 |  45,000 |  20,000 | 95.0 | 1.96 | 4.0 |  918 | 474 | 410 | 86.3 |
| 4,000 |  45,000 |  20,000 | 95.0 | 1.96 | 4.0 |  918 | 474 | 424 | 89.4 |
| 5,000 |  45,000 |  20,000 | 95.0 | 1.96 | 4.0 |  918 | 474 | 433 | 91.3 |
| 10,000 |  45,000 |  20,000 | 95.0 | 1.96 | 4.0 |  918 | 474 | 453 | 95.5 |
| 20,000 |  45,000 |  20,000 | 95.0 | 1.96 | 4.0 |  918 | 474 | 463 | 97.7 |
| 30,000 |  45,000 |  20,000 | 95.0 | 1.96 | 4.0 |  918 | 474 | 467 | 98.4 |
| 40,000 |  45,000 |  20,000 | 95.0 | 1.96 | 4.0 |  918 | 474 | 469 | 98.8 |
| 50,000 |  45,000  |  20,000 | 95.0 | 1.96 | 4.0 |  918 | 474 | 470 | 99.1 |
| 120,000 |  45,000  |  20,000 | 95.0 | 1.96 | 4.0 |  918 | 474 | 472 | 99.5 |
| 250,000 |  45,000 |  20,000 | 95.0 | 1.96 | 4.0 |  918 | 474 | 473 | 99.8 |
| 500,000 |  45,000  |  20,000 | 95.0 | 1.96 | 4.0 |  918 | 474 | 474 | 99.9 |
| 1,000,000 |  45,000 |  20,000 | 95.0 | 1.96 | 4.0 |  918 | 474 | 474 | 100.0 |
| 10,000,000 |  45,000  |  20,000 | 95.0 | 1.96 | 4.0 |  918 | 474 | 474 | 100.0 |
|  |  |  |  |  |  |  |  |  |  |  |  |  |

In summary, the required sample size can be very sensitive to several variables, especially the desired precision and confidence level set by the survey analyst.  If resource constraints require a reduction in the scope of the survey, a good deal of reduction in required sample size (and, therefore, cost) can often be obtained by relaxing the confidence level or precision somewhat.

5.6 Assessment of Degree of Precision
-------------------------------------

To quantify the tradeoffs between sample size and the corresponding degree of precision, the same principles underlying the sample size calculations can be used.  The objective of such an analysis is to calculate the degree of precision that corresponds to a sample size, smaller than the “ideal” sample size, that has already been calculated based on one or more variables.  Such calculations could be repeated for a range of sample sizes and variables to identify the precision that would be expected under alternative sample size scenarios for each variable of interest.

To assess the absolute or relative degree of precision that can be expected for a given sample size and a desired level of confidence, the following information is required (Table 5.11):

* The variance of the variable in the study population (σ2);* The desired statistical level of confidence (1-α) and the corresponding z statistic;* The sample size (n) and the population size (N); and* The mean (μ) of the variable in the population (required only in case the relative degree of precision is to be estimated).

The calculations for the degree of precision that corresponds to a given sample size can be illustrated best by relying on the same hypothetical household travel survey example mentioned earlier.  The formulas that are used in the precision calculations are summarized in Table 5.11.  The standard error of the average that corresponds to the variance of the variable and the given sample size and population size is shown in Eq. 5.10.  The absolute degree of precision can be calculated by accounting for the z statistic value corresponding to the desired level of statistical confidence (1-α) (see Eq. 5.11).

***Table 5.11 Formulas for Precision Given Sample Size n***

![](../attachments/153443000000031065_1.0)  


In addition to the absolute precision measure, when a relative degree of precision is needed, Eq. 5.11 can be modified slightly to take into account the mean value of the parameter. This is shown in Eq. 5.12.

In cases where the parameter variance and/or its mean are not readily available, the CV can be used instead. Since a standard error cannot be calculated directly in this case, the degree of relative precision would be calculated using the formula shown in Equation 5.13.

The precision equations outlined here have been applied to the household income example used in the previous section. Table 5.12 illustrates the calculations using two sets of inputs. In the first case, the mean and the variance of the parameter are assumed known, allowing us to calculate both the relative and the absolute degree of precision that correspond to a given sample size and confidence level.  In the second case, the relative degree of precision is calculated based on the CV instead of the mean and variance of the variable which are not known with certainty.  Using the “ideal” sample size that was earlier derived based on household income, the calculations presented in Table 5.12 result in a relative degree of precision of +4% and a corresponding absolute degree of precision of +$1,800.

Table 5.12 Degree of Precision for Household Income



| Inputs | Formulas | Estimates |
| Population size | N | 120,000 | SE() | Inputs | N, n, l |
| Standard Deviation | σ | $20,000 | Equation 5.10 | SE()= | $919 |
| Sample Size | n | 472 |   |   |   |
| Confidence Level | C | 95% | D | Inputs: | SE(), z |
| Z-Statistic | z | 1.96 | Equation 5.11 | D = | ±$1,801 |
| Mean | m | $45,000 | dEquation 5.12 | Inputs:d= | SE(m), z, m± 4.0% |
| Population SizeSample Size | Nn | 120,000472 |   |   |   |
| Coefficient of Variation | CV | 0.444 | dEquation 5.13 | Inputs: d= | CV, N, n, z± 4.0% |
| Confidence Level | C | 95% |   |   |   |
| Z-Statistic | z | 1.96 |   |   |   |

 

 The same process can be repeated for a range of sample sizes and for a variety of variables to identify the tradeoffs between sample size and the corresponding degree of precision that would be expected for variables of interest to the analysis.  Such an analysis would show that, for sample sizes that are smaller than the ideal, a lower degree of precision would be expected for particular variables.  To assess the value of the proposed survey properly, such a drop in precision would need to be contrasted with the possible lack of precision of the existing estimates currently used for planning purposes. 

5.7 Assessment of the Confidence Level
--------------------------------------

An alternative way of assessing the tradeoffs between sample size and the corresponding quality of data would be to compare the confidence level expected for a particular variable under different sample size scenarios.  The principles of such an approach are also rooted in the methodology used for sample size calculations and the approach would be very similar to the one used for estimating the degree of precision for a given sample size.  Again, the calculations for the expected confidence level could be repeated for a range of sample sizes and variables to identify the confidence level that would be expected under alternative sample size scenarios for each variable of interest.

To estimate the confidence level corresponding to a given sample size and a desired degree of precision, the following information is required (Table 5.13):

* The variance of the variable in the study population (σ2);* The desired absolute or relative degree of precision (D or d, respectively);* The sample size (n) and the population size (N); and* The mean (μ) of the variable in the population (in case the relative degree of precision is provided).

Table 5.13 Formulas for Confidence Level Given Sample Size n

![](../attachments/153443000000031069_1.0)

The calculations for the level of confidence corresponding to a given sample size are again illustrated by relying on the hypothetical household travel survey and the formulas that are used are summarized in Table 5.13. First, the standard error that corresponds to a given sample size, population, and variance of the variable is calculated (Eq. 5.10) note: Table 5.13 has a wrong number for this equation. Then, the z statistic that corresponds to a given absolute degree of precision can be calculated (Eq. 5.14) along with the confidence level (1-α) that corresponds to the calculated z-statistic.

In cases where the relative degree of precision is provided, the mean value of the variable is incorporated into the calculations as shown in Eq. 5.15. On the other hand, when the variance and/or its mean are not readily available, the CV can be used instead. Under this situation, since the standard error cannot be calculated directly, the confidence level calculations are based on the relative degree of precision as shown in Equation 5.16.

These equations have again been applied to the household income example used earlier. Table 5.14 illustrates the calculations using two sets of inputs. In the first case, the mean and the variance of the variable are assumed known, allowing one to estimate the level of confidence that correspond to a given sample size, the relative degree of precision, and the absolute degree of precision. In the second case, the confidence level is calculated based on the CV instead of the mean and variance of the variable. As before, using the “ideal” sample size derived for household income, the calculations presented in Table 5.14 result in a z-statistic of 1.96, which in turn corresponds to a confidence level of 95 percent.

The same process can be repeated for a range of sample sizes and for a variety of variables of interest to identify the tradeoffs between sample size and their corresponding confidence levels. By definition, the confidence level corresponds to sample sizes that are smaller than the “ideal” sample size would be lower than the desired 95 percent confidence level. However, such a drop in the confidence level would again need to be viewed in light of the existing data sources and the level of confidence that can be placed on the existing estimates. Because transportation planning applications often rely on dated data sources, the value of new information may overshadow the lower confidence level justifying the collection of new, more detailed travel and socioeconomic data.

Table 5.14 Level of Confidence for Household Income



| Inputs | Formulas | Estimates |
| Population size | N | 120,000 | SE( <!--[if !vml]--><!--[endif]-->) | Inputs | N, n, σ |
| Standard Deviation | σ | $20,000 | Equation 5.9 | SE()= | $918.8 |
| Sample Size | n | 472 |   |   |   |
| Absolute Precision | D | ± $1,800 of mean | z-Statistic | Inputs: | SE(), D |
| Z-Statistic | z | 1.96 | Equation 5.13 | z = | 1.96 |
| Relative PrecisionMean | dm | ± 4% of mean$45,000 | z-StatisticEquation 5.14 | Inputs:z= | SE(), d1.96 |
| Population SizeSample Size | Nn | 120,000472 |   |   |   |
| Coefficient of Variation | CV | 0.444 | z-StatisticEquation 5.15 | Inputs: z= | CV, N, n, d1.96 |
| Relative Precision | d | ± 4% of mean |   |   |   |

5.8 Complex Sample Designs
--------------------------

The selection of a sampling method is also interrelated with the broad objectives of the survey; the study population and the corresponding appropriate sampling frame and unit; the desired level of precision, level of confidence, and accuracy; and the sample size requirements for the whole sample or specific segments of the market.  The simple random sampling method offers the most straightforward means of selecting a sample because it results in an unbiased, self-weighting sample that is representative of the study population.  This method presents many advantages to the surveyor, including the following:

* If the sample (both recruited and the final respondents) are truly randomly selected, the survey should be unbiased, eliminating the need for post-survey weighting.* Every potential respondent is eligible to be recruited at any time. In a stratified sample, some potential respondents might be members of strata for which the sample has been filled. It may be impossible to tell if a respondent is eligible until he has been recruited.* It is cheaper than the more complex methods, both because no effort is wasted recruiting ineligible respondents, and because the development of the sampling plan itself will take less resources.* It is easy to understand and be accepted by non-technical decision makers and the public.

However, in cases where market segments of particular interest to the analysis may be underrepresented under a simple random sample design, other probabilistic methods such as *stratified sampling* and *cluster sampling* may be employed to provide the desired level of precision for variables and market segments of interest.  Of course, all require a sampling frame. Furthermore, *choice-based sampling* procedures may also be used to enhance the sample in cases where a particular segment of the population, which exhibits a behavior of particular interest to the study, is difficult to reach due to its low incidence in the population.

Systematic Sampling
-------------------

With the systematic sampling approach, as opposed to the random selection of sampling units from a sampling frame, sampling units are selected based on sequences that are separated by a pre-set interval.  Provided that the sampling frame order is relatively unbiased, this approach is essentially equivalent to the simple random sample.  In personal intercept surveys, field workers could be instructed to approach every `nth’ person passing a certain point.  Similarly, random-digit-dialing (RDD) telephone surveys could be conducted by calling every nth telephone number within a pre-specified set of telephone exchanges. 

Assuming that the systematic sampling method is as random as the simple random sample, the choice between the two survey methods, often, is a simple question of logistics or convenience.  For intercept surveys, it may be difficult for a survey field worker to choose a truly random sample; a systematic method would be much easier. And some experts feel that systematic sampling should only be used when a sampling frame is not available, but where the situation of the sampling lends itself to taking every *n*th element, such as in an intercept survey.

**Stratified Sampling**

The stratified sampling method is particularly useful in cases where segments of the study population need to be studied in greater detail, requiring a greater degree of precision, and in cases where the grouping of observations will result in homogeneous groups of respondents.  The homogeneity of each segment reflects the similarity in socioeconomic characteristics and travel behavior of respondents within each segment.

This method allows one to identify, focus on, and collect information from particular segments of the study population (also referred to as strata) by using either uniform or variable sampling rates.  Stratified sampling offers a means of differentiating among strata and reducing the sampling error within each stratum of interest.  Similarly, stratified sampling can also be used to reduce the amount of data collection needed by segmenting the survey population into more homogeneous strata and sampling at a higher rate from strata with a higher degree of variability/heterogeneity.

The definition of strata can be based on:

* Geographic boundaries such as strata that correspond to different towns or counties;* Characteristics of the travel environment under study such as low versus high-density areas, or areas with a good versus poor level of transit service; or* Socioeconomic characteristics of the sampling unit such as household income categories or automobile ownership.

The statistical theory behind the stratified sampling shares many similarities with the discussion presented under simple random sampling.  Since the most likely objective of the analysis under both sampling methods is to make inferences about the travel behavior of the population as a whole, a random sample of respondents needs to be drawn within each stratum. The sampling rate within each stratum also often varies across the various strata.  Initially, a uniform sampling rate can be examined as part of the sample design to allocate the sample size to different strata and to assess the expected effective yield of observations by stratum.  If the resulting number of observations for particular strata of interest is below the minimum number of observations required for the desired level of precision for that stratum, a range of variable sampling rates can be considered.  In such a case, higher sampling rates would be used to oversample lower-incidence strata while lower sampling rates would be applied to higher-incidence strata. A chapter reviewer writes: The desire to offer a simple explanation has actually resulted in incorrect statements being made about the two types of stratified sampling. They actually should be adopted for different reasons and this discussion is incorrect.

The two most common forms of stratified sampling in household travel surveys are geographic and demographic.  Geographic stratification may be done based simply on political boundaries or may include land use or transportation-based measures to define the stratification areas. Stratification simply by political boundaries is most useful when there are other survey objectives besides demand model development, where differences based on such boundaries rarely comes into play.  However, if information about households or travelers were desired for, say, county level data summaries, then political stratification would make sense. Reviewer writes: this is a wrong-headed explanation of reasons for geographic sampling.

As an example, consider the 1994 household activity survey (newer references needed) conducted in the Portland, Oregon area by Metro.  This survey used 10 geographically-defined strata for the Oregon part of the Portland metropolitan area (NuStats, 1994).  The strata are shown in Table 5.15. In this sampling plan, four of the strata (6 though 9) represent individual counties.  Five strata represent parts of Multnomah County, which contains the city of Portland.  These strata are defined by pedestrian environment and transit availability.  The tenth stratum represents a choice-based sample of park-and-ride users.  Reviewer writes: The example should not confound different types of stratification, as this one does.

Demographic stratification has been used in many surveys where the primary purpose has been to gather information for trip generation models.  Commonly, a two-way cross-classification based on the expected form of the trip generation models, such as household size by income or auto ownership, is used.  Table 5.16 shows the sampling framework for a 1990 household travel survey in the Pittsburgh, Pennsylvania area (Treadway, 1993) (newer references preferred)  In this survey, a cross-classification plan using two variables, persons per household and autos per household, was employed.  The agency conducting the survey, the Southwestern Pennsylvania Regional Planning Commission, had decided that developing a trip production model for home-based trips was their survey objective and had found through previous survey efforts that these two variables were significant in explaining trip production rates.

***Table 5.15 Portland Travel Survey Stratification***



| 1. Multnomah County - good pedestrian environment, land use mix, and transit- Multnomah County – bad pedestrian environment and transit- Multnomah County – good pedestrian environment and transit- Multnomah County – light rail corridor- Remainder of Multnomah County- Clackamas County- Washington County- Columbia County (part)- Yamhill County (part)- Park-and-ride users
 |



 ***Table 5.16 Pittsburgh Travel Survey Stratification***



|   | **Person/Household** |
| Autos/Household | 1 | 2 | 3 | 4 | 5+ | Total |
| 0 | 25 | 25 |   |   |   | 50 |
| 1 | 25 | 29 | 50 |   |   | 104 |
| 2 |   | 52 | 61 | 35 | 29 | 177 |
| 3+ |   |   | 48 | 29 | 25 | 102 |
| Total | 50 | 106 | 159 | 64 | 54 | 433 |



Note: Blank cells are included with those on the right or above. For example, there are 25 samples for 0 autos, 2+ persons and 25 for 1 person, 1+autos, etc.

It should be pointed out that under a geographic stratification, it may be known (or approximately known) where a household fits into the stratification plan before they are recruited.  While telephone exchanges provide imperfect matches with political or census boundaries, there is some correspondence that can be used.  However, it generally is impossible to determine a household’s income, number of autos, or number of persons without asking. This means that under a demographic stratification, there may be recruitment calls made to households who would cooperate, but would not fit the required stratification. This reduces the effective response rate for the survey.  Reviewer writes: Poor discussion of the issue.

Multi-stage Sampling – this section should doucment
---------------------------------------------------

In multi-stage sampling, the sampling units at the first stage are actually groups of the final sample units.  At the second stage, all of the units within a selected cluster may be included in the sample (called cluster sampling), or a second-stage subsample may be drawn randomly within each selected cluster.  Multi-stage sampling normally increases the sampling error over that of a simple random sample. Justification for such sampling is usually the lack of a sample frame, and the expense that would be incurred to develop one.  Workplace/establishment surveys can be examples of multi-stage or cluster surveys.  A sample of establishments is first selected from the population of all establishments within a study area.  If all employees and visitors/customers are then sampled within the selected establishment it is a cluster sample.  If only a portion are sampled, it is considered two-stage sampling.  A true cluster sample is often done in the case of a face-to-face or similar survey methodology, because it can lower the unit cost of the survey, although it is again likely to increase the required sample size for a given level of accuracy.

Household surveys may be conducted using both multi-stage and cluster sampling techniques.  For example, the study area may first be divided into tracts or neighborhoods and a sample of tracts is drawn. Second, within each tract, households are drawn randomly and within each randomly selected household, a respondent may also be drawn at random.  This is particularly effective for in-home interviews so that survey field workers can minimize travel time between households.  However, for mail and telephone surveys, cluster sampling is usually inappropriate.

The statistical theory on cluster sampling again follows the discussion presented under simple random sampling.  Because the most likely objective of the analysis remains on making inferences about travel behavior of the study population, a random sample of sampling units needs to be drawn at each stage of the cluster sampling.

Choice-based Sampling (Ben-Aliva & Lerman, 1985, and Lerman, Manski, & Atherton, 1975)
--------------------------------------------------------------------------------------

The choice-based sampling method offers a means of identifying respondents in low-incidence market segments which may need to be represented in the analysis.  Respondents who belong to such low-incidence market segments are therefore characterized by their choice behavior that forms the basis for the sampling frame.  Common example of the use of a choice-based sampling method is the focused collection of data from transit users and bicycle users, when the focus of the analysis will be on mode choice.

The most common use of data collected from choice-based sampling methods is in the development of mode choice models.  Even with the application of stratified sampling and variable sampling rates within different strata, it is possible that the low incidence for particular segments of the study population may result in too few observations for these groups.  A small number of observations from a particular group makes it difficult to study the determinants of its behavior, and often results in its exclusion from the model development and estimation.  However, despite the low incidence, it is often desirable to account for the behavior of smaller segments of the population to better understand the factors underlying their behavior.  A reviewer writes: It is hard to distinguish this from stratified sampling with variable sampling fraction. In fact, the problem here is that the description of choice-based sampling is incorrect.

Choice-based sampling offers a methodology to augment the existing sample drawn as a simple random or stratified sample.  In particular, respondents who belong in low incidence segments are intercepted and recruited for a pre-specified quota of additional surveys.  For example, transit riders in a corridor dominated by automobile traffic can be randomly sampled at transit stops while bike riders can be contracted and get randomly sampled through clubs that organize activities.  As a consequence of including such observations in the analysis, the variability in the behavior observed and analyzed increases considerably, resulting in an enriched model and providing valuable insights into behavioral determinants.  Furthermore, analytical (weighting) procedures for generating unbiased, consistent estimates with a choice-based sample can be used to control for any biases that may be introduced with the combination of randomly drawn and choice-based samples.

While the recruitment procedures may necessarily be different for respondents that are part of a choice-based recruitment process, the conducting of the interviews may not be.  While transit users, for example, could be asked questions while riding or waiting, they could also simply be recruited and then contacted for data retrieval in the same way as other respondents.  This provides an opportunity to collect more comprehensive information. It should also be noted that all information obtained through a choice-based recruitment process will not necessarily be associated with the behavior targeted by the sampling method.  A transit user may make other trips by auto or other modes, or may have others in the household who do so.

Balancing Multiple Objectives
-----------------------------

Many MPOs conduct travel surveys as inputs for their travel models. Thus they need to have a comprehensive look at different population segments. As mentioned in Choice Based Sampling above, careful selection for particular characteristics can be used to get at special populations, such as low-income, minorities, or young mobile professionals. At times it may also be necessary to vary sampling rates by geography in order to recruit sufficient samples of the desired populations. Once the survey data has been collected, the data is weighted so as to not over-represent the population that was over sampled. In addition to geographical variability, recruitment methods can vary. Surveys in the last few decades have utilized Random Digit Dialing (RDD) to recruit households economically. Unfortunately this undercounts segments of the population. This problem is getting worse with the proliferation of cell phones and households jettisoning their landlines (at the time of this writing 10% of households no longer have a landline and this will no doubt change over time). Another way to develop a sample is by using an address based sample draw. Using addresses provides a more comprehensive sample do draw from, but it also makes respondents harder to reach since it requires them to ‘opt-in.’ A work around for this problem, is to match the sample frame to published phone numbers. For the matched sample, the survey can proceed more like a traditional RDD protocol. For the unmatched portion, there needs to be a hook in order to garner participation. Incentives are one possibility, dramatic publicity is another, as is utilization of new technologies. 

5.9 Bias in Travel Surveys
--------------------------

Up to this point, this chapter has concentrated on ways of minimizing sampling errors that arise from, and reflect the use of, a sample of respondents, and the inherent variability of their responses.  As the examples have shown, it is possible to determine the impacts of sample size and sampling strategies on the precision of parameter estimates from survey data, and to use this information to develop mathematical estimates of sampling errors.  Survey teams can measure and, if resources permit, decrease sampling errors by increasing sample sizes and improving sampling strategies.

The other major sources of errors in survey data are the non-sampling errors that produce survey biases.  These errors can be at least as important as sampling errors, but to reduce their effect, survey teams need to apply different strategies.  Non-sampling errors differ from sampling errors in that they:

* Originate from several unrelated sources;* Are non-random – they have a pre-determined (often constant) effect on parameter estimates;* Are almost always unquantifiable; and* Do not improve with increased sample sizes.

Survey bias results from the failure to adequately address the variety of quality concerns shown in Stopher et al.’s (2008) Figure 4.2. The survey design and implementation problems that are generally responsible for bias include:

* Misidentification of the survey population;* Imperfect sampling frame and sampling loss (non-coverage);* Non-response;* Poor questions and survey instruments;* Field worker and interviewer errors; and* Coding, entry, and data processing errors.

The misidentification of the survey population, sampling frame problems, and sampling loss all have the potential to bias the survey results because valid units are left out of the sample. If the units that are left out have different characteristics than those that are in the sample, then the survey results will be biased. 

Table 5.17 shows an example of how an incomplete sampling frame can bias survey results. In this example, a telephone household survey is being conducted for an area with 50,000 households. Ten percent of the households in the region do not have phones, and those households without phones tend to have lower incomes. The actual percentage of households with incomes of less than $20,000 is 12 percent, but because only households with phones are included in the survey, the estimated percentage is 8.3 ± 2.7 percent. This estimate assumes that the income distribution of the survey respondents matches that of the households with telephones.

Non-response is probably the most serious potential bias. Even if the survey team is able to create a complete and accurate sampling frame, they still cannot ensure that every sampling unit will be willing or available to respond to the survey. If the responding units are different than the non-respondents, which is usually the case, then the survey results will be biased.

Table 5.18 shows how non-response can affect survey results. The table continues the example from the previous table. For this example, the response rate is assumed to be 50 percent, so the survey team needs to contact 6,000 of the 45,000 households with phones. The income distribution of the 6,000 households should closely resemble the income distribution of the sampling frame, but the income distribution of survey respondents may be significantly different. In the example, households with incomes between $40,000 and $100,000 are more likely to respond than the higher or lower income households. The effect is that the estimated income distributions are biased. Too few households are assigned to the lowest and highest income categories, and too many are assigned to the middle-income categories.

The remaining three sources of survey bias – problems with questions and response categories, interviewer/field worker errors, and survey office worker errors – contribute to bias because they affect the survey results in non-random ways. If survey questions are misleading or confusing, then some percentage of respondents will provide the wrong answer to the question by accident. Other respondents will skip the particularly confusing questions and questions that seek private information. Additionally, survey workers can record the wrong answer or influence respondents’ answers in some way when they ask questions, or office staff can miscode responses or enter them into the database incorrectly.

Table 5.17 An Example of Bias Due to an Incomplete Sampling Frame



|   | Households |   |   |   |   |
| Income Categories | With Phones | Without Phones | Total | Actual Household Distribution | RDD SurveyResults(90% Confidence) |
| Under $20,000 | 3,755 | 2,245 | 6,000 | 12.0% | 8.3% | + / - | 2.68% |
| $20,000 -$39,999 | 8,021 | 979 | 9,000 | 18.0 | 17.8 | + / - | 2.53 |
| $40,000 -$59,999 | 8,313 | 687 | 9,000 | 18.0 | 18.5 | + / - | 2.52 |
| $60,000 -$79,999 | 8,075 | 425 | 8,500 | 17.0 | 17.9 | + / - | 2.53 |
| $80,000 -$99,999 | 9,044 | 456 | 9,500 | 19.0 | 20.1 | + / - | 2.50 |
| $100,000 or more | 7,792 | 208 | 8,000 | 16.0 | 17.3 | + / - | 2.54 |
| All Categories | 45,000 | 5,000 | 50,000 | 100.0% | 100.0% |   |   |
|  |  |  |  |  |  |  |  |  |

Note: Assumes an RDD survey of 3,000 households, a 100% response rate, and no field or office problems.

 

 Table 5.18 An Example of Bias Due to Non-Response



| Income Categories | SamplingFrameDistribution | DrawnSampleDistribution | RDD SurveyResults(90% Confidence) |
| Under $20,000 | 3,755 | 8.3% | 500 |   8.3% | 162 | 5.4% | + / - | 1.76% |   |
| $20,000 -$39,999 | 8,021 | 17.8 | 1,070 | 17.8 | 345 | 11.5 | + / - | 1.66 |   |
| $40,000 -$59,999 | 8,313 | 18.5 | 1,108 | 18.5 | 624 | 20.8 | + / - | 1.66 |   |
| $60,000 -$79,999 | 8,075 | 17.9 | 1,076 | 17.9 | 589 | 19.6 | + / - | 1.66 |   |
| $80,000 -$99,999 | 9,044 | 20.1 | 1,207 | 20.1 | 768 | 25.6 | + / - | 1.64 |   |
| $100,000 or more | 7,792 | 17.3 | 1,039 | 17.3 | 512 | 17.1 | + / - | 1.67 |   |
| All Categories | 45,000 | 100.0% | 6,000 | 100.0% | 3,000 | 100.0% |   |   |   |

Note: Assumes an RDD survey of 3,000 households, a 50% response rate, and no field or office problems.

These survey problems can further affect bias levels for the survey results. Table 5.19 continues the example from the previous tables to illustrate bias from these sources. In this table, it is assumed that the overall non-response levels are the same as for Table 5.18. The item non-response rate for income is 10 percent, so even though the survey team has 3,000 total responses, only 2,700 of them have valid income categories. As is usually the case, the respondents who fail to provide income data are not representative of the whole sample. They are more likely to be in the highest income category. The results shown also could include the response errors that are suspected to be fairly common in income questions.

Table 5.19 An Example of Bias Due to Question Wording, Field Errors, and office Errors



| Income Categories | Sampling FrameDistribution | Actual Survey Respondent Distribution | RDD Survey Results(90% Confidence) |
| Under $20,000 | 3,755 |  8.3% | 162 |  5.4% | 145 |  5.4% | + / - | 2.85% |   |
| $20,000 -$39,999 | 8,021 | 17.8 | 345 | 11.5 | 321 | 11.9 | + / - | 2.76 |   |
| $40,000 -$59,999 | 8,313 | 18.5 | 624 | 20.8 | 608 | 22.5 | + / - | 2.56 |   |
| $60,000 -$79,999 | 8,075 | 17.9 | 589 | 19.6 | 557 | 20.6 | + / - | 2.58 |   |
| $80,000 -$99,999 | 9,044 | 20.1 | 768 | 25.6 | 705 | 26.1 | + / - | 2.47 |   |
| $100,000 or more | 7,792 | 17.3 | 512 | 17.1 | 364 | 13.5 | + / - | 2.64 |   |
| All Categories | 45,000 | 100.0% | 3,000 | 100.0% | 2,700 | 100.0% |   |   |   |

Note: Assumes a survey of 3,000 households, a 50% response rate, and some field and office problems.

The total bias of a parameter estimate is the combined effect of these individual components. Biases from each individual source can work in the same direction or work in different directions, so that they partially cancel out one another. The bias introduced by using the imperfect sampling frame and the bias introduced by non-response both work to artificially decrease the estimate of the number of households of the lowest income category. On the other hand, the imperfect sampling frame biases the estimated number of households in the highest income category upwards, while the question wording and the field and office errors decrease the estimate.

It is important to note that bias is unrelated to sample size. If the examples from above assumed that the sample size was 10,000 instead of 3,000, only the level of precision would change. The survey team would be more certain that the actual percentage of households in the lowest income category is around 5.4 percent (the 90 percent confidence limits would be ± 0.6 percent, rather than ± 1.7 percent). Unfortunately, the actual answer would be 12 percent.

Designing the survey should include methods to measure unavoidable bias. Some bias comes from the missed households and how they differ from participating households. A follow up with some of the non-responding and refusal households can yield clues about how they differ. Any differences that are identified can be controlled or corrected. Another source of bias in household travel surveys can come from missed trip reporting, particularly vehicle trips. GPS devices can be used to augment respondent recall. If it is not practical to put GPS into all households’ vehicles (or ask all respondents to carry a personal unit) than a subsection of the overall sample can be selected. Careful consideration needs to be taken when considering the protocols for determining this sample. If this aspect is presented as a normal part of the survey than there is no introduction of bias for the technologically savvy or those not fearful of being tracked. Comparisons of GPS trip data and reported trip data can determine the extent of trip underreporting.

Although it is usually impossible to eliminate all bias, it may be possible to correct for it. When the magnitude of the total bias of a parameter estimate can be measured through independent means, the total error of an estimate can be calculated. In these cases, the survey results can often be weighted so that they reflect actual conditions more accurately. For instance, for income levels and other socioeconomic measures, the survey team may be able to use Census data to determine the overall level of bias.

However, for many key survey results, such as trip rates or the socioeconomic characteristics of certain subpopulations, such as transit riders, there is no way to determine the amount of bias in the survey results. The only way to determine the actual parameter value would be to conduct another survey or a census, which would be vulnerable to the same biases.

The most common approach to dealing with potential survey bias is to take as many steps as possible to limit its presence while designing the survey, to correct for those biases which can be corrected, and then to assume that the overall level of bias is negligible compared to the imprecision in the survey-derived parameter estimates. In reporting survey error, surveyors commonly report sampling errors and simply discuss potential biases qualitatively. This approach is probably naively optimistic in many cases, but the difficulty or impossibility of measuring and correcting for many biases makes the strategy reasonable and often preferred.

The potential problem with this common approach is illustrated by an example. Suppose a household travel survey measures the average daily person trip rate to be 3.4 trips, with a standard deviation of 2.2 trips. The trip information is collected through travel diaries which require respondents to record all their trips in a 24-hour period. Further suppose that actual respondent trips can be determined for the period (e.g., through the use of hand-held GPS tracking devices as many are now demonstrating), and that the travel diary data is found to bias the survey results by 0.1 trips per person (per day).

As Equation 5.1 in Section 5.1 shows, the “total error” for the survey trip rate estimate is the combination of the standard error of the survey and the total bias (B). For smaller sample sizes, the precision errors dominate the bias. For example, for a sample size of 100:

SE2 = ![](../attachments/153443000000031077_1.0) <!--[if !vml]--><!--[endif]--> = 0.0484

B2 = (0.1)2 = 0.1

The sampling error term is roughly five times the bias term. However, as the sample size increases, the constant bias becomes more important compared to the decreasing sampling error. When the sample size is 500, the standard error term is about 0.01, approximately the same as the bias term. When the sample size is 5,000, the bias term dominates the sampling error. Using the sampling error as a measure of total error is reasonable for smaller sampling sizes (and larger sampling errors), but as the sample size increases, the sampling error estimates no longer accurately reflect the potential error in parameter estimates.

**REFERENCES** 

Ben-Akiva, M. and S. Lerman. (1985) *Discrete Choice Analysis: Theory and Application to Travel Demand,* The MIT Press.

Cambridge Systematics, Inc. (1994) *Travel Survey Manual.* U.S. Department of Transportation, U.S. Environmental Protection Agency. 

Churchill, G.A. (1984) *Marketing Research: Methodological Foundations*, The Dryden Press.

Fielding, F. and H. Gunn. (1985) *Sample Design Workshop Summary in Ampt, E. S., Richardson, A.J. and Brög, W.*  New Survey Methods in Transport, VNU Science Press: Utrecht, The Netherlands, p. 25.

Lerman, S.R., C.F. Manski, and T. J. Atherton. (1975) *Non-random Sampling in the Calibration of Disaggregate Choice Models,* Final report prepared by Cambridge Systematic, for the U.S. Department of Transportation.

NuStats, Inc. (1994) *“Sample Productivity Plan.”* Technical Memorandum. Austin, Texas.

Richardson, A.J., E.S. Ampt, and A. Meyburg. (1995) *Survey Methods for Transport Planning*, Eucalyptus Press, Melbourne. p.97.

Stopher et al. (2008) Method for Household Travel Surveys. A Synthesis of Highway Practice. Transportation Research Board. National Research Council.

Treadway, T.B. (1993) *“Small Scale Stratified Sample Home Interview Survey for the Pittsburgh Region.”* Proceedings of the Fourth National Conference on Transportation Planning Methods Applications.

  


---

Note: In this chapter, the level of confidence (l-I, often taking a value of 95 percent) is used for discussion purposes instead of the corresponding level of statistical significance (I, often taking a value of 0.05).

