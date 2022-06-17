# Diamond-Price-predition
In this project we will Try to predict the price of Diamonds depends on some features related to them 
## Dataset 
You will find dataset in the repo with name of "diamond.csv"
# Features description 
A data frame with 53940 rows and 10 variables:
- #price
price in US dollars (\$326--\$18,823)
- #carat
weight of the diamond (0.2--5.01)
- #cut
quality of the cut (Fair, Good, Very Good, Premium, Ideal)
- #color
diamond colour, from J (worst) to D (best)
- #clarity
a measurement of how clear the diamond is (I1 (worst), SI2, SI1, VS2, VS1, VVS2, VVS1, IF (best))
- #x
length in mm (0--10.74)
- #y
width in mm (0--58.9)
- #z
depth in mm (0--31.8)
- #depth
total depth percentage = z / mean(x, y) = 2 * z / (x + y) (43--79)
- #table
width of top of diamond relative to widest point (43--95)
## Preprocssing 
For this dataset we will try to encode categorical Data detecting outliers and standarized the data 
## ML model used 
-  Descision tree 
-  KNN
-  linear regression 
## Score 
- Decision tree with overall accuracy of 98%
- KNN regressor with n =3 with overall accuracy of 96%
- Linear regression with overall accuracy of 91%
