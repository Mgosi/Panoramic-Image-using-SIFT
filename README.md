# Panoramic-Image-using-SIFT
Creating a Panoramic image from 2 images using SIFT, and wrap
1.  Creating SIFT images to find the key points of the 2 images. 

<p align="center">
  <br><br>
  <img src="sift1.jpg" align = "center" width = 300>
  <figcaption><p align="center">SIFT Image Left</p></figcaption>
</p>

<p align="center">
  <br><br>
  <img src="sift2.jpg" align = "center" width = 300>
  <figcaption><p align="center">SIFT Image Right</p></figcaption>
</p>

2.  Then perform Homography which relates the transformation between two plane by using RANSAC Algorithm

3.  KNN matching is then applied to find the similar points in the two images.

<p align="center">
  <br><br>
  <img src="matches_knn.jpg" align = "center" width = 450>
  <figcaption><p align="center">KNN Matches</p></figcaption>
</p>

4.  Find the 10 best matches

<p align="center">
  <br><br>
  <img src="matches.jpg" align = "center" width = 450>
  <figcaption><p align="center">KNN Matches</p></figcaption>
</p>

4.  We then warp the 2 images to get the panoramic image

<p align="center">
  <br><br>
  <img src="pano.jpg" align = "center" width = 450>
  <figcaption><p align="center">Panorama</p></figcaption>
</p>
