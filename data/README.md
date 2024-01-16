# Data description

## Background

This data were orignally collected from public sources for the project associated with the manuscript _“Comparative Effectiveness of mRNA-1273 and BNT162b2 COVID-19 Vaccines Among Older Adults: A Systematic Review and Meta-Analysis Using the GRADE Framework”_.
This is available on the MedRxiv pre-print server.
Find the link to access the article here: https://medrxiv.org/cgi/content/short/2023.11.21.23298832v1


## Description

This folder consists of COVID-19 outcome data for individual given either Moderna or Pfizer vaccines.
Different files contain data for different outcome type data.
They are all _contrast-based_ outcomes meaning that they are a relative comparison statistic between the two types of vaccines.

The data have been anonymised so that study/author and vaccine labels are replaced by an index ID. The original data can be obtained from the package authors.

## Outcome meaures

There are five outcome measures available. Data for each of these is contained in their own folder. These can be thought of as increasing in severity. The sample sizes become smaller for more severe outcomes.

* infection
* symptomatic infection
* severe infection
* hospitalisation
* death

## Outcome format

There are 5 possible forms that the output statistics can take. Not all types are available for all outcomes.

* `rate_data` - Rate/hazard ratio data
* `bin_data` - Binary data
* `ve_data` - Vaccine effectiveness data
* `lhr_data` - Log-hazard ratio data
* `lor_data` - Log-odds ratio data

## Data definitions

The scales used in the data are defined below.

#### Binary data
These are the counts of the number of events of interest from some sample or group at risk.
The data are provided in terms of counts and sample size.

#### Hazard ratio (HR)
The _hazard_ is an instantaneous probability or rate of occurence of an event of interest over a period of time.
The _hazard ratio_ is then the relative difference between two hazards i.e. $h_1 = \alpha h_0$ where $h_0$ is the baseline hazard and $\alpha$ is the hazard ratio.
The data are provided in terms of mean and standard errors.

#### Relative risk (RR)

_Risk_ is the probability of the occurance of an event of interest. This is estimated by the ratio of the number of events $x$ over the sample size $N$, i.e. $x/N$.
The _relative risk_ (also called _risk ratio_) is the relative difference between two risks, i.e. $p_1/p_0$, estimated by $(x_1 N_0)/(x_0 N_1)$.

#### Odds ratio (OR)
The odds of an event of interest is the ratio of the probability of the event over the probability of the event not occuring, i.e. $p_1/(1-p_1)$.
The _odds ratio_ is the relative difference between two odds, i.e.

$$
\frac{p_1/(1-p_1)}{p_0/(1-p_0)}.
$$

#### Vaccine effectiveness (VE)
_Vaccine effectiveness_ is a measure of how well vaccines work in the real world (similar to _vaccine efficacy_ which is a measure in a controlled clinical trial).
However, there is no single definition for VE. It is variously defined as 1-OR, 1-RR or 1-HR.


## Column names and desctiptions

The total list of fields in the data is given below. Not all fields are in all data sets, depending on the type of data e.g. binary or continuous. The asterisk indicate that this field is not available in the anonymised data.

* `study_id/author_id` - Unique study ID number
* *`author/study` - Lead author name of article and year of publication
* `age` - Age group of data set
* *`arm` - intervention name
* `arm_id` - Unique intervention ID number
* *`intervention1` - First, reference COVID-19 vaccine name
* *`intervention2` - Second, comparison COVID-19 vaccine name
* `interv_id1` - First, reference COVID-19 vaccine unique ID
* `interv_id2` - Second, comparison COVID-19 vaccine unique ID
* `N1` - Sample size of intervention1
* `N2` - Sample size of intervention2
* `n1` - Number of cases for intervention1
* `n2` - Number of cases for intervention2
* `r` - Number of cases
* `n` - Total time at risk
* `yi` - Mean of number of outcome
* `vi` - Variance of number of outcome
