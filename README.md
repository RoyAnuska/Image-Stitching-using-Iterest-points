# Image-Stitching-using-Interest-points
Panorama creation using BoW methodology

The major steps for image stitching and panorama creation is as follows:-
1. Detect key points and extract local invariant descriptors (SIFT) from the two input images.
2. Match the descriptors between the two images and also eliminate outliers using RANSAC algorithm.
3. Estimate a Homography matrix using the matched feature vectors.
4. Apply a warping transformation using the homography matrix obtained.
5. Visualize the results and the matching key points

For more details please go through the attached documents
[Image Stitching Report.pdf](https://github.com/RoyAnuska/Image-Stitching-using-Iterest-points/files/11924696/Image.Stitching.Report.pdf)
