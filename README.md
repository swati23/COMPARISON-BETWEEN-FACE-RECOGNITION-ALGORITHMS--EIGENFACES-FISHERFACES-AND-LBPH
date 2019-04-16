# COMPARISON-BETWEEN-FACE-RECOGNITION-ALGORITHMS--EIGENFACES-FISHERFACES-AND-LBPH
# comparative study of three most recently methods for face recognition (eigenfaces, fisherfaces, Local binary pattern using histogram (LBPH))
The Eigenfaces method then performs face recognition by:
•	Projecting all training samples into the PCA subspace.
•	Projecting the query image into the PCA subspace.
•	Finding the nearest neighbour between the projected training images and the projected query image
# FISHERFACES
fisherface method is able to take advantage of within-class information, minimising variation within each class, yet still maximising class separation. So we can say that,
•	FLD maximizes the between-class scatter
•	FLD minimizes the within-class scatter 
The Fisherface is especially useful when facial images have large variations in illumination and facial expression. 
# LOCAL BINARY PATTERN USING HISTOGRAMS
•The basic idea of Local Binary Patterns is to summarize the local structure in an image by comparing each pixel with its neighborhood. Take a pixel as center and threshold its neighbors against. 
•If the intensity of the center pixel is greater-equal its neighbor, then denote it with 1 and 0 if not. You’ll end up with a binary number for each pixel, just like 11001111. So with 8 surrounding pixels you’ll end up with 2^8 possible combinations, called Local Binary Patterns or sometimes referred to as LBP codes.

# Overall performance on the basis of percentage scale:

Methods	Neutral	Illumination	Expression	Pose


PCA   	0.8027	0.8108	       0.8455	    0.7736


LDA	    0.9150	0.9189	       0.8902	    0.8302


LBP	    0.9422	0.9730	       0.9106	    0.9245
				
So,LBP achieves the highest accuracy in different training sets.
