# PREDICTION OF DIAMOND'S PRICES USING FEEDFORWARD NETWORK

## DATASET

A data frame with 53940 rows and 10 variables:

1. Price : price in US dollars (\$326--\$18,823)
2. Carat : weight of the diamond (0.2--5.01)
3. Cut : quality of the cut (Fair, Good, Very Good, Premium, Ideal)
4. Color : diamond colour, from J (worst) to D (best)
5. Clarity : a measurement of how clear the diamond is (I1 (worst), SI2, SI1, VS2, VS1, VVS2, VVS1, IF (best))
6. x : length in mm (0--10.74)
7. y : width in mm (0--58.9)
8. z: depth in mm (0--31.8)
9. Depth : total depth percentage = z / mean(x, y) = 2 * z / (x + y) (43--79)
10. Table : width of top of diamond relative to widest point (43--95)

## GOOGLE COLAB

To predict this regression problem , Google colab notebook is used with the application of Numpy, Pandas, Scikit-learn and Tensorflow Keras.

## MODEL PREDICTION AND RESULT

The structure of the model has 2 dense layers which use activation function of 'relu' and followed by output layer using 'linear'. 

Using Mean Squared Error and Mean Absolute Error as metrics, the result at epoch 20 with batch size of 10 is 337.5805 and 693978.6250 respectively. 


 
