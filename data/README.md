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
