# ComputerVision3D_GraphCut
You need Imagine++ library (http://imagine.enpc.fr/~monasse/Imagine++/)

We computer a disparity map of a pair of images using the graph cut method. The graph used for graph-cut method can be seen as several layers of the image put on top of each others, where one layer corresponds to a certain disparity. The algorithm computes the minimum cut and therefore finds which disparities minimize the overall energy of the pair of images.