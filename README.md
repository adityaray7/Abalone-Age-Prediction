This Project is a part of Assignment under a course at IIT Mandi. 
 
 About the Dataset : Abalones are marine snails. The dataset has been prepared
with the aim of making age predictions easier. Customarily, the age of abalone is determined by
cutting the shell through the cone, staining it, and counting the number of rings through a microscope.
But it is a tedious and time-consuming task. Therefore, other measurements, which are easier to
obtain, are used to predict age.

Attribute information:
Given is the attribute name, attribute type, the measurement unit, and a brief description. The number
of rings is the value to predict: either as a continuous value or as a classification problem.
Name / Data Type / Measurement Unit / Description

1. Length / continuous / mm / Longest shell measurement
2. Diameter / continuous / mm / Diameter of the shell calculated as perpendicular to length
3. Height / continuous / mm / Height of the shell with meat in shell
4. Whole weight / continuous / grams / Weight of whole abalone
5. Shucked weight / continuous / grams / Weight of meat
6. Viscera weight / continuous / grams / Gut-weight (after bleeding)
7. Shell weight / continuous / grams / Weight of the shell after being dried
8. Rings / integer / -- / Number of rings in a shell. (Adding 1.5 to the number of rings gives the
   age of abalone in years)
 
 --------------------------------------------------------------------------------------
 
Aim:

1. Plot best fit line using linear regression model using attribute with highest
    pearson correlation coeffecient with the target attribute and also finding the accuracy.
2. Build multivariate linear regression model using all the attributes.
3.  Plot best fit line using polynomial regression model using attribute with highest
    pearson correlation coeffecient with the target attribute for different values of degree and
    also finding the accuracy along with best p value.
4.  Build multivariate polynomial regression model using all the attributes for different 
    values of degrees.
