# Monocular_3d_object_detection

 The mass adoption of autonomous vehicles can help reduce road casualties and improve safety for the driver, passengers and even pedestrians. However, the cost of autonomous vehicles is one of the major factors that may hinder the adoption rates. Indeed, sophisticated sensors such as Radar and LiDAR help contribute to the high cost. To reduce the cost of autonomous vehicles, monocular 3D object detection can be utilised since this technology does not rely on the aforementioned sensors. Moreover, 3D object detection may be advantageous over 2D object detection in the field of autonomous vehicles since 3D object detection provides more information such as the object's size, position, and orientation. However, to ensure that monocular 3D object detection can be reliable, the network must be tested and evaluated on various adverse conditions such as fog, rain, snow and sandstorms. Indeed, this project investigates the performance of the CenterNet which is a 3D object detection network and proposes an end-to-end network which improves the performance of the network in adverse conditions. This is achieved by utilising the AOD-Net which acts as a dehazing network in order to generate a clearer scene for the object detector.
 
<p float="left">
  <img src="/img/dehazed_objectpred_groundtruth.jpg" width="250" />
  <img src="/img/hazy_objectpred_1.jpg" width="250" /> 
  <img src="/img/dehazed_objectpred_1.jpg" width="250" />
</p>
