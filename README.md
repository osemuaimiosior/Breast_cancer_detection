# Breast_cancer_detection

This machine learning model is made in other to help professionals in the medical field reduce the amount of work they have to do when attending to patients and the stress that comes with it. 
This machine learning model can be used by non medical practitioner to detect breast cancer for thousands of patients at once without them having visit the hospital. Non medical practitioners can be trained to carry out a digitized image of a fine needle aspirate (FNA), collect the needed data and run it through this model to detect breast cancer quickly  in a safe and secure environment.
This model of operations helps provide more jobs and some level of support for health care industry.
Other models can be created too to help doctors diagnose other aliments like malaria, typhoid and more.

## Dataset
The dataset used are computed from a digitized image of a fine needle aspirate (FNA) of a breast mass. They describe characteristics of the cell nuclei present in the image.
n the 3-dimensional space is that described in: [K. P. Bennett and O. L. Mangasarian: "Robust Linear Programming Discrimination of Two Linearly Inseparable Sets", Optimization Methods and Software 1, 1992, 23-34].

# Attribute Information:
1) ID number
2) Diagnosis (M = malignant, B = benign)
3-32)

Ten real-valued features are computed for each cell nucleus:

a) radius (mean of distances from center to points on the perimeter)

b) texture (standard deviation of gray-scale values)

c) perimeter

d) area

e) smoothness (local variation in radius lengths)

f) compactness (perimeter^2 / area - 1.0)

g) concavity (severity of concave portions of the contour)

h) concave points (number of concave portions of the contour)

i) symmetry

j) fractal dimension ("coastline approximation" - 1)

The mean, standard error and "worst" or largest (mean of the three
largest values) of these features were computed for each image,
resulting in 30 features. For instance, field 3 is Mean Radius, field
13 is Radius SE, field 23 is Worst Radius.

All feature values are recoded with four significant digits.
