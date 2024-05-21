Image animation consists of generating a video sequence so that an object in a
source image is animated according to the motion of a driving video. Our frame
work addresses this problem without using any annotation or prior information
about the specific object to animate. Once trained on a set of videos depicting
objects of the same category (e.g. faces, human bodies), our method can be applied
to any object of this class.  To support complex motions,we use a representation 
consisting of a set of learned keypoints along with their
local affine transformations. A generator network models occlusions arising during
target motions and combines the appearance extracted from the source image and
the motion derived from the driving video.
