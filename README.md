# Object-Detection-using-SIFT-and-SURF-

The detector.py file detects objects using the SIFT(Scale Invariant Feature Transform) class of OpenCV.
The object that was being detected was a notebook in this case, the picture has been provided in the repository.

SURF(Speeded-Up Robust Features) can be used to improve faster detection but with reductions in accuracy.
SURF can be used by modifying these lines:

MIN_MATCH_COUNT=30
//reduce the MIN_MATCH_COUNT to a higher value as the features detected by SURF are far greater than SIFT

detector=cv2.xfeatures2d.SIFT_create() //to:- detector=cv2.xfeatures2d.SURF_create()


