**EMPS: Electron Microscopy Particle Segmentation** is a dataset for instance segmentation, semantic segmentation, and object detection tasks. It is used in the materials research. 

The dataset consists of 465 images with 11594 labeled objects belonging to 1 single class (*particle*).

Images in the EMPS dataset have pixel-level instance segmentation annotations. Due to the nature of the instance segmentation task, it can be automatically transformed into a semantic segmentation (only one mask for every class) or object detection (bounding boxes for every object) tasks. All images are labeled (i.e. with annotations). There are no pre-defined <i>train/val/test</i> splits in the dataset. Also, the dataset contains ***doi*** tag. The dataset was released in 2021 by the University of Cambridge.

<img src="https://github.com/dataset-ninja/emps/raw/main/visualizations/poster.png">
