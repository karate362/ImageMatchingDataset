# ImageMatchingDataset

In each dataset folder are the following files:

1. Positive/Negative folder: Contains truly/falsely matched image pairs, named as x_ref.jpg and x_test.jpg, x = 1,2,3,…,N.

2. Positive.mat/Negative.mat: SIFT feature matching results, stored in MATLAB mat format. In each mat is a N-by-4 cell array, each row is [u_ref, v_ref, u_test, v_test], meaning the 2d position of the matched feature points on ref and test images.

3. camPara.txt: Store the 3-by-3 camera intrinsics matrix.
