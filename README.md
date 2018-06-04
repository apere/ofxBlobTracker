# ofxBlobTracker
Classic and simple blobTracker implementation used on CCV ( Created by Ramsin Khoshabeh ) + Finger Tracking

Tested on Sierra 10.13 64-bit

Modifications:

- ofxBlob.h: Outdated distance function. Updated following https://openframeworks.cc/learning/02_graphics/how_to_use_glm/
- ofxContourFinder.cpp: Unknown CvContourRetrievalMode and cvConvexHull - solved following https://github.com/patriciogonzalezvivo/ofxBlobTracker/issues/5
