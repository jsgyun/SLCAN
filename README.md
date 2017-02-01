# End-to-end Learning of Image based Lane-Change Decision

## Authors
  - Seong-Gyun Jeong
  - Jiwon Kim
  - Sujun Kim
  - Jaesik Min

## Abstract
  We propose an image based end-to-end learning framework that helps lane-change decisions for human drivers and autonomous vehicles. The proposed system, Safe Lane-Change Aid Network (SLCAN), trains a deep convolutional neural network to classify the status of adjacent lanes from rear view images acquired by cameras mounted on both sides of the vehicle. Rather than depending on any explicit object detection or tracking scheme, SLCAN reads the whole input image to directly decide whether initiation of the lane-change at the moment is safe or not. Over 77k rear side view images are collected and annotated to train and test SLCAN. Experimental results show that the proposed framework achieves 96.98\% classification accuracy although the test images are from unseen roadways. We also visualize the saliency map to understand which part of image SLCAN looks at for correct decisions.

## Video results
<a href="http://www.youtube.com/watch?feature=player_embedded&v=d5xJSw6qSpo
" target="_blank"><img src="http://img.youtube.com/vi/d5xJSw6qSpo/0.jpg" 
alt="IMAGE ALT TEXT HERE" width="480" height="360" border="10" /></a>
