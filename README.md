# SVD-image-classification
Singular Value Decomposition for Image Classification

The aim of this project is classify the given hand-written digital numbers (only 1 and 8) into two class.

**Project Definition**

  We were given 200 pictures of handwritten 8 and 1 by the size of 16, 16. However, they are not like real picture, 
each of them were flatten into the size of 1x256. Then, if we we need all the pictures, we are going to get a matrix size of 200x256 for
each 8 and 1.
  
  In order to find basis of this all pictures (200x256) for 8 or 1, they will be factorized by using 'np.linalg.svd' function. Then, we 
  will get three diffrent matrices (U, S, V). S represents a diagonal matrix that has a eigenvalues on its diagonal. V has a basis for the
  those pictures (200x256) on its rows.

The steps that are going to be followed like,

1- Upload the training dataset

2- Exhibit them to see how it looks like

3- Factorize the dataset by following the Singular Value Decomposition

4- Visualize the basis of the factorized dataset

5- Upload the test dataset

6- And classify the test dataset

If you need more clarification, firstly try to comprehend the python-code, otherwise you can also email me.

