# Structure from Motion
Affine structure from motion (SfM) is a computer vision technique that aims to reconstruct the 3D structure of a scene from a sequence of 2D images. The goal is to recover the 3D positions of the points in the scene, as well as the camera poses and intrinsic parameters.

Steps:
1.  Detected corners and used the second moment matrix to locate strong corners to use as keypoints.
2.  Programmed a Kanade-Lucas-Tomasi feature tracker from scratch to track a set of detected key points in an image over a sequence of images.
3.  Generated 3D points for the object by computing affine(motion) and 3D shape matrices from the tracked 2D keypoints.
