# breast_cancer_diagnosis
ML Models to diagnose breast cancer based on [Wisconsin dataset](https://archive.ics.uci.edu/ml/datasets/Breast+Cancer+Wisconsin+(Diagnostic))

It contains 30 input features based on which predictions (benign (B) or malignant (M)) are made.

Features are obtained from an image of Fine Needle Aspirate (FNA) of breast mass.
 There are 32 atributes: ID,diagnosis, 30 real-valued input features.



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

Several of the papers listed above contain detailed descriptions of
how these features are computed. 

The mean, standard error, and "worst" or largest (mean of the three
largest values) of these features were computed for each image,
resulting in 30 features.  For instance, field 3 is Mean Radius, field
13 is Radius SE, field 23 is Worst Radius.


## Conclusion

  ANN is created and trained and tested with validation dataset along with various other classification models.
It is observed that ANN has best performance among the trained models. 
