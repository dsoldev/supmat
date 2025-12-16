# 3D-Heatmap-of-Object-Pose-Estimation-Estimation-Supplementary-Material

This page supports the article "3D Heatmap for Object Pose Estimation" with the follwing:
* 3D heatmaps blender files for LM-O dataset objects

# Abstract

Object pose estimation is crucial for applications such as industrial robotics, bin picking, and augmented-reality overlays, as it enables systems to determine the orientation and position of objects in three-dimensional space. However, accurately estimating pose remains challenging, particularly in complex, occlusion-rich scenes or under heavy occlusions. In this work, we build upon previous results by incorporating targeted architectural and training modifications that enhance performance, resulting in an improved pose estimation network. Our model was evaluated on the LM-O (LineMOD-Occluded) dataset, achieving a BOP benchmark score of 69.3\%, which aggregates multiple standard 6D pose metrics, with an inference time of 0.804~s per frame on a NVIDIA RTX 2060.

Additionally, we extend earlier model explainability strategies by generating occlusion-based 2D heatmaps and projecting them onto the object surface to produce 3D heatmaps. These visualizations highlight object components that influence each prediction, offering deeper insight into the model's decision-making process and promoting transparency in pose estimation. Our 3D heatmap algorithm was also applied for comparison to SurfEmb-RGB, and the resulting interpretable, fast, and accurate pipeline is well-suited for safety-critical robotic cells and AR devices, where both high performance and explainability are essential.

# 3D Heatmaps
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