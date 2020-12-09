# Awesome visual place recognition (VPR) datasets
This repository provides a curated list of awesome datasets for **Visual Place Recognition (VPR)**, which is also called **loop closure detection (LCD)**. It is a significant component in V-SLAM (Visual Simultaneous Localization and Mapping) systems. 

We will update the list if new VPR dataset is presented.

Our survey paper on deep learning-based visual place recognition contains detailed information about these datasets:
> Xiwu Zhang, Lei Wang, and Yan Su. **Visual Place Recognition: A Survey From Deep Learning Perspective**. [_Pattern Recognition_](https://www.sciencedirect.com/journal/pattern-recognition), November 2020, doi: https://doi.org/10.1016/j.patcog.2020.107760.

![Dataset examples](https://ars.els-cdn.com/content/image/1-s2.0-S003132032030563X-gr5_lrg.jpg)



## Datasets used in VPR.

| Topic             | Name                                                         | Year | Image type      | Environment     | Illumination       | Viewpoint          | Ground Truth       | Labels             | Extra Information |
| ----------------- | ------------------------------------------------------------ | ---- | --------------- | --------------- | ------------------ | ------------------ | ------------------ | ------------------ | ----------------- |
| Generic           | [New College and City Centre](http://www.robots.ox.ac.uk/~mobile/IJRR_2008_Dataset/data.html) [1] | 2008 | RGB             | Outdoor         | slight             | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | GPS               |
|                   | [New College Vision and Laser ](https://ori.ox.ac.uk/older-projects/new-college-dataset/) [2] | 2009 | Gray\.          | Outdoor         | slight             | :heavy_check_mark: | :heavy_check_mark: |                    | GPS, IMU, LiDAR   |
|                   | [Rawseeds](http://www.rawseeds.org/home/)                    | 2006 | RGB             | Indoor/Outdoor  |                    | :heavy_check_mark: | :heavy_check_mark: |                    | GPS, LiDAR        |
|                   | [Ford Campus](http://robots.engin.umich.edu/SoftwareData/Ford) | 2011 | RGB             | Urban           | slight             |                    | :heavy_check_mark: |                    | GPS, IMU, LiDAR   |
|                   | [Malaga Parking 6L](https://www.mrpt.org/malaga_dataset_2009) | 2009 | RGB             | Outdoor         |                    |                    | :heavy_check_mark: |                    | GPS, IMU, LiDAR   |
|                   | [KITTI Odometry](http://www.cvlibs.net/datasets/kitti/eval_odometry.php) | 2012 | Gray\./ RGB     | Urban           | slight             |                    | :heavy_check_mark: |                    | GPS, IMU, LiDAR   |
| Long\-term        | [St\. Lucia](https://wiki.qut.edu.au/display/cyphy/St+Lucia+Multiple+Times+of+Day) | 2010 | RGB             | Urban           | :heavy_check_mark: | slight             |                    |                    | GPS               |
|                   | [COLD](https://www.nada.kth.se/cas/COLD/)                    | 2009 | RGB             | Indoor          | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | LiDAR             |
|                   | [Oxford RobotCar](https://robotcar-dataset.robots.ox.ac.uk/) | 2017 | RGB             | Urban           | :heavy_check_mark: |                    | :heavy_check_mark: |                    | GPS, IMU, LiDAR   |
|                   | [Gardens Point Walking](https://goo.gl/tqmWyq)               | 2014 | RGB             | Indoor/ Outdoor | :heavy_check_mark: | :heavy_check_mark: |                    |                    | \-                |
|                   | [MSLS](https://www.mapillary.com/dataset/places)             | 2020 | RGB             | Urban           | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: |                    | GPS               |
| Across seasons    | [Nurburgring and Alderley](https://wiki.qut.edu.au/display/cyphy/Michael+Milford+Datasets+and+Downloads) | 2012 | RGB             | Urban           | :heavy_check_mark: |                    | :heavy_check_mark: | :heavy_check_mark: | \-                |
|                   | [Nordland](https://nrkbeta.no/2013/01/15/)                   | 2013 | RGB             | Outdoor         | :heavy_check_mark: |                    | :heavy_check_mark: |                    | GPS               |
|                   | [CMU](http://3dvis.ri.cmu.edu/data-sets/localization/)       | 2011 | RGB             | Urban           | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: |                    | GPS               |
|                   | [Freiburg \(FAS\)](http://aisdatasets.informatik.uni-freiburg.de/freiburg_across_seasons/) | 2014 | RGB             | Urban           | :heavy_check_mark: |                    | :heavy_check_mark: | :heavy_check_mark: | GPS               |
|                   | [VPRiCE](https://goo.gl/R0QYU2)                              | 2015 | RGB             | Outdoor         | :heavy_check_mark: | :heavy_check_mark: |                    |                    | \-                |
| RGB\-D            | [TUM RGB\-D](https://vision.in.tum.de/data/datasets/rgbd-dataset) | 2012 | RGB\-D          | Indoor          |                    | :heavy_check_mark: | :heavy_check_mark: |                    | IMU               |
|                   | [Microsoft 7\-Scenes](https://www.microsoft.com/en-us/research/project/rgb-d-dataset-7-scenes/) | 2013 | RGB\-D          | Indoor          |                    | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | \-                |
|                   | [ICL\-NUIM](https://www.doc.ic.ac.uk/~ahanda/VaFRIC/iclnuim.html) | 2014 | RGB\-D          | Indoor          |                    | :heavy_check_mark: | :heavy_check_mark: |                    | \-                |
| Semantic          | [KITTI Semantic](http://www.cvlibs.net/datasets/kitti/eval_semantics.php) | 2019 | RGB             | Urban           |                    |                    | :heavy_check_mark: | :heavy_check_mark: | GPS, IMU, LiDAR   |
|                   | [Cityscapes](https://www.cityscapes-dataset.com/)            | 2016 | RGB             | Urban           |                    |                    | :heavy_check_mark: | :heavy_check_mark: | GPS               |
|                   | [CSC](https://www.visuallocalization.net/datasets/)          | 2019 | RGB             | Outdoor         | :heavy_check_mark: |                    | :heavy_check_mark: |                    | LiDAR             |
| Train networks    | [Cambridge Landmarks](http://mi.eng.cam.ac.uk/projects/relocalisation/#dataset) | 2015 | RGB             | Outdoor         | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | \-                |
|                   | [Pittsburgh250k](http://www.ok.ctrl.titech.ac.jp/~torii/project/repttile/) | 2013 | RGB             | Urban           | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | GPS               |
|                   | [Tokyo 24/7](http://www.ok.ctrl.titech.ac.jp/~torii/project/247/) | 2015 | RGB             | Urban           | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: |                    | GPS               |
|                   | [SPED](https://goo.gl/OXeL2X)                                | 2017 | RGB             | Outdoor         | :heavy_check_mark: | :heavy_check_mark: |                    |                    | \-                |
| Omni\-directional | [New College Vision and Laser](https://ori.ox.ac.uk/older-projects/new-college-dataset/) | 2009 | Gray\.          | Outdoor         | slight             | :heavy_check_mark: | :heavy_check_mark: |                    | GPS, IMU, LiDAR   |
|                   | [MOLP](http://hcr.mines.edu/code/MOLP.html)                  | 2018 | Gray\./D        | Outdoor         | :heavy_check_mark: |                    | :heavy_check_mark: |                    | GPS               |
|                   | [NCLT](http://robots.engin.umich.edu/nclt/)                  | 2016 | RGB             | Outdoor         | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: |                    | GPS, LiDAR        |
| Aerial/UAV        | [Shopping Street 1/2](http://www.v4rl.ethz.ch/research/datasets-code.htmls) | 2018 | Gray\.          | Urban           | slight             | :heavy_check_mark: | :heavy_check_mark: |                    | \-                |
|                   | [EuRoC](https://projects.asl.ethz.ch/datasets/doku.php?id=kmavvisualinertialdataset) | 2016 | Gray\.          | Indoor          |                    | :heavy_check_mark: | :heavy_check_mark: |                    | IMU               |
| Underwater        | [UWSim](https://goo.gl/GtMQkv)                               | 2016 | RGB             | Under\-water    |                    |                    | :heavy_check_mark: |                    | GPS               |
| Range sensors     | [MulRan](https://sites.google.com/view/mulran-pr)            | 2020 | 3D Point clouds | Urban           | :heavy_check_mark: |                    | :heavy_check_mark: |                    | LiDAR, RADAR      |



## Reference:

[1]  Cummins, M. & Newman, P. __FAB-MAP: Probabilistic Localization and Mapping in the Space of Appearance.__ The International Journal of Robotics Research, 2008, 27, 647-665 

[2]  M. Smith, I. Baldwin, W. Churchill, R. Paul, P. Newman, The new college vi- sion and laser data set, Int. J. Rob. Res. 28 (5) (2009) 595–599, doi: 10.1177/ 0278364909103911 .

---

Citations to this work:
```
@article{ZHANG2020107760,
title = "Visual place recognition: A survey from deep learning perspective",
journal = "Pattern Recognition",
pages = "107760",
year = "2020",
issn = "0031-3203",
doi = "https://doi.org/10.1016/j.patcog.2020.107760",
url = "http://www.sciencedirect.com/science/article/pii/S003132032030563X",
author = "Xiwu Zhang and Lei Wang and Yan Su",
}
```




