# Dominant_Color_Extraction
It is a Machine Learning problem using the K-Means Clustering algorithm.

In this problem, the K most dominant colors in an image are extracted out and the image is repainted using those colors.

K-Means Clustering Algorithm is an Unsupervised Learning Algorithm ,i.e., It doesn't have any training dataset. In this problem,
all the given data points are alloted to one of the K randomly initialised centres based on least distance. Then each centre is updated 
on the basis of mean of all points assigned to it. This process is repeated for some iterations until we get good approximation 
of K clusters out of the data.

In this case, all the pixels are data points having (R,G,B) vaues and the K most dominant colors finally divide the image into 
K clusters having those colors.
