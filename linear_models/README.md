# Analysis of the relationship between brain IQ and its dimension
This folder contains a Markdown notebook created for the Applied Linear Models course project.
The objective is to develop a linear model to explore association between some explanatory
variables (*Height*, *Gender*, *Weight* and *Size*) and the response variable (*IQ*).

## Description
The data are based on a study by Willerman et al. (1991) of the relationships between brain size, 
gender and intelligence. The research participants consisted of 40 right-handed introductory psychology students, 
with no history of alcoholism, unconsciousness, brain damage, epilepsy or heart disease, who were selected 
from a larger pool of introductory psychology students with total Scholastic Aptitude Test Scores higher 
than 1350 or lower than 940. The students in the study took four subtests of the Wechsler (1981) 
Adult Intelligence Scale-Revised. Among the students with Wechsler full-scale IQ's less than 103, 
10 males and 10 females were randomly selected. Similarly, among the students with Wechsler 
full-scale IQ's greater than 130, 10 males and 10 females were randomly selected.

The dataset contains 5 variables that are:

- Gender
- IQ: It represents the score obtained at the assessment test; this is a valid measure of the intelligence because
  it is the most plausible measurement which can be taken, and it is also a reliable measure since it is precise and stable,
  and if the experiment could be retaken, the values obtained probably would not change much
- Weight: It is the person's weight, expressed in pounds
- Height: It is the brain height, expressed in inches
- Size: It represents the brain dimension, expressed in pixel

## Example
<pre>
gender  iq   weight   height  size
Female  133  118      2.67    816932
Male	 140	151	    3.00	  1001121
Male	 139	143	    3.04	  1038437
Male	 133	172	    2.84	  965353
</pre>
