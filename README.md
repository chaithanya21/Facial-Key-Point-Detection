# Facial-Key-Point-Detection
This project will be all about defining and training a <b>convolutional neural network(CNN)</b> to perform <b>Facial Keypoint Detection</b>, and using <b>Computer Vision</b> techniques to transform images of faces.

<img src="https://github.com/chaithanya21/Facial-Key-Point-Detection/blob/master/Images/key_pnts_image.png" width="550">

Facial Keypoints (also called Facial Landmarks) are the small magenta dots shown on each of the faces in the image above. In each training and test image, there is a single face and <b>68 keypoints, with coordinates (x, y),</b> for that face. These keypoints mark important areas of the face: the eyes, corners of the mouth, the nose, etc. These keypoints are relevant for a variety of tasks, such as <b>face filters, emotion recognition, pose recognition,</b> and so on. Here they are, numbered, and you can see that specific ranges of points match different portions of the face.
<br>
<br>
<img src="https://github.com/chaithanya21/Facial-Key-Point-Detection/blob/master/Images/landmarks_numbered.jpg" width="350">

<h2>Dataset</h2>

This set of image data has been extracted from the [YouTube Faces Dataset](https://www.cs.tau.ac.il/~wolf/ytfaces/), which includes videos of people in YouTube videos. These videos have been fed through some processing steps and turned into sets of image frames containing one face and the associated keypoints.
