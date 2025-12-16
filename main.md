# Supplementary Materials Page
## 3D-Heatmap-of-Object-Pose-Estimation-Estimation-Supplementary-Material

This page supports the article "3D Heatmap for Object Pose Estimation" with the follwing:
* 3D heatmaps blender files for LM-O dataset objects

### Abstract

Object pose estimation is crucial for applications such as industrial robotics, bin picking, and augmented-reality overlays, as it enables systems to determine the orientation and position of objects in three-dimensional space. However, accurately estimating pose remains challenging, particularly in complex, occlusion-rich scenes or under heavy occlusions. In this work, we build upon previous results by incorporating targeted architectural and training modifications that enhance performance, resulting in an improved pose estimation network. Our model was evaluated on the LM-O (LineMOD-Occluded) dataset, achieving a BOP benchmark score of 69.3\%, which aggregates multiple standard 6D pose metrics, with an inference time of 0.804~s per frame on a NVIDIA RTX 2060.

Additionally, we extend earlier model explainability strategies by generating occlusion-based 2D heatmaps and projecting them onto the object surface to produce 3D heatmaps. These visualizations highlight object components that influence each prediction, offering deeper insight into the model's decision-making process and promoting transparency in pose estimation. Our 3D heatmap algorithm was also applied for comparison to SurfEmb-RGB, and the resulting interpretable, fast, and accurate pipeline is well-suited for safety-critical robotic cells and AR devices, where both high performance and explainability are essential.

### 3D Heatmaps
* Blender file for Ape: [ape.blend](https://dsoldev.github.io/heatmap3d/ape.blend)
* Blender file for Benchvise: [benchvise.blend](https://dsoldev.github.io/heatmap3d/benchvise.blend)
* Blender file for Bowl: [bowl.blend](https://dsoldev.github.io/heatmap3d/bowl.blend)
* Blender file for Camera: [camera.blend](https://dsoldev.github.io/heatmap3d/camera.blend)
* Can blender file for Can: [can.blend](https://dsoldev.github.io/heatmap3d/can.blend)
* Cup blender file for Cup: [cup.blend](https://dsoldev.github.io/heatmap3d/cup.blend)
* Driller blender file for Driller: [driller.blend](https://dsoldev.github.io/heatmap3d/driller.blend)
* Duck blender file for Duck: [duck.blend](https://dsoldev.github.io/heatmap3d/duck.blend)
* Glue blender file for Glue: [glue.blend](https://dsoldev.github.io/heatmap3d/glue.blend)
* Holepuncher blender file for Holepuncher: [holepuncher.blend](https://dsoldev.github.io/heatmap3d/holepuncher.blend)
* Lamp blender file for Lamp: [lamp.blend](https://dsoldev.github.io/heatmap3d/lamp.blend)
* Phone blender file for Phone: [phone.blend](https://dsoldev.github.io/heatmap3d/phone.blend)

---

## ICIP2023-6D-Pose-Estimation-Supplementary-Material

This page supports the article "Modeling and Interpreting 6-D Object Pose Estimation" submitted for ICIP 2023 with the follwing:
* Iteractive version of Figure 3
* $R_x$ plot that was removed from Figure 3 because of spcae restriction
* The Pose_network results that was removed from the article
* Figure 3 colored by $cos(r1)$ and $cos(r2)$

### Abstract

This work aims to estimate the 6-Degrees of Freedom Pose of an object using simple convolutional neural networks. The problem is that most methods require previous knowledge of the 3D model of the object of interest, which could be unobtainable. We mitigate the problem by simplifying the object’s 3D model to a single and generic primitive solid to create a model that could estimate the pose of unknown objects. Besides that, we study the interpretability of the neural network by using visualization techniques to understand how the network is splitting the high-dimension feature space to reach a Pose estimation.

### Rotation Feature Plot
* Cored by Type: [rotation_feature_type](https://dsoldev.github.io/icip23supmat/rot_networks/moved_tetrahedron_ResNet50/type.html)
* Cored by $R_x$: [rotation_feature_r1](https://dsoldev.github.io/icip23supmat/rot_networks/moved_tetrahedron_ResNet50/r1.html)
* Cored by $R_z$: [rotation_feature_r2](https://dsoldev.github.io/icip23supmat/rot_networks/moved_tetrahedron_ResNet50/r2.html)
* Cored by $cos(R_x)$: [rotation_feature_cos_r1](https://dsoldev.github.io/icip23supmat/rot_networks/moved_tetrahedron_ResNet50/cos(r1).html)
* Cored by $cos(R_z)$: [rotation_feature_cos_r2](https://dsoldev.github.io/icip23supmat/rot_networks/moved_tetrahedron_ResNet50/cos(r2).html)

### Pose Feature Plot
#### Feature Layer
* Cored by Object: [feature_layer_obj](https://dsoldev.github.io/icip23supmat/pose_networks/resnet50_combined_loss/feature_layer/object.html)
* Cored by $R_x$: [feature_layer_roll](https://dsoldev.github.io/icip23supmat/pose_networks/resnet50_combined_loss/feature_layer/roll.html)
* Cored by $R_y$: [feature_layer_pitch](https://dsoldev.github.io/icip23supmat/pose_networks/resnet50_combined_loss/feature_layer/pitch.html)
* Cored by $R_z$: [feature_layer_yaw](https://dsoldev.github.io/icip23supmat/pose_networks/resnet50_combined_loss/feature_layer/yaw.html)
* Cored by $t_x$: [feature_layer_tx](https://dsoldev.github.io/icip23supmat/pose_networks/resnet50_combined_loss/feature_layer/tx.html)
* Cored by $t_y$: [feature_layer_ty](https://dsoldev.github.io/icip23supmat/pose_networks/resnet50_combined_loss/feature_layer/ty.html)
* Cored by $t_z$: [feature_layer_tz](https://dsoldev.github.io/icip23supmat/pose_networks/resnet50_combined_loss/feature_layer/tz.html)

#### Rotation Branch Layer 1
* Cored by Object: [rot_dense1_object](https://dsoldev.github.io/icip23supmat/pose_networks/resnet50_combined_loss/rot_dense1/object)
* Cored by $R_x$: [rot_dense1_roll](https://dsoldev.github.io/icip23supmat/pose_networks/resnet50_combined_loss/rot_dense1/roll)
* Cored by $R_y$: [rot_dense1_pitch](https://dsoldev.github.io/icip23supmat/pose_networks/resnet50_combined_loss/rot_dense1/pitch)
* Cored by $R_z$: [rot_dense1_yaw](https://dsoldev.github.io/icip23supmat/pose_networks/resnet50_combined_loss/rot_dense1/yaw)

#### Rotation Branch Layer 2
* Cored by Object: [rot_dense2_object](https://dsoldev.github.io/icip23supmat/pose_networks/resnet50_combined_loss/rot_dense2/object)
* Cored by $R_x$: [rot_dense2_roll](https://dsoldev.github.io/icip23supmat/pose_networks/resnet50_combined_loss/rot_dense2/roll)
* Cored by $R_y$: [rot_dense2_pitch](https://dsoldev.github.io/icip23supmat/pose_networks/resnet50_combined_loss/rot_dense2/pitch)
* Cored by $R_z$: [rot_dense2_yaw](https://dsoldev.github.io/icip23supmat/pose_networks/resnet50_combined_loss/rot_dense2/yaw)

#### Translation Branch Layer 1
* Cored by Object: [t_dense1_object](https://dsoldev.github.io/icip23supmat/pose_networks/resnet50_combined_loss/t_dense1/object)
* Cored by $t_x$: [t_dense1_tx](https://dsoldev.github.io/icip23supmat/pose_networks/resnet50_combined_loss/t_dense1/tx)
* Cored by $t_y$: [t_dense1_ty](https://dsoldev.github.io/icip23supmat/pose_networks/resnet50_combined_loss/t_dense1/ty)
* Cored by $t_z$: [t_dense1_tz](https://dsoldev.github.io/icip23supmat/pose_networks/resnet50_combined_loss/t_dense1/tz)

#### Translation Branch Layer 2
* Cored by Object: [t_dense2_object](https://dsoldev.github.io/icip23supmat/pose_networks/resnet50_combined_loss/t_dense2/object)
* Cored by $t_x$: [t_dense2_tx](https://dsoldev.github.io/icip23supmat/pose_networks/resnet50_combined_loss/t_dense2/tx)
* Cored by $t_y$: [t_dense2_ty](https://dsoldev.github.io/icip23supmat/pose_networks/resnet50_combined_loss/t_dense2/ty)
* Cored by $t_z$: [t_dense2_tz](https://dsoldev.github.io/icip23supmat/pose_networks/resnet50_combined_loss/t_dense2/tz)