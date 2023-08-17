# TUM MA - Literature Research  
###### tags: `TUM`,  `MA`, `Literature Research`

## Task Description
Given an rgb video of 2 hands interacting with an object we should train a deep learning model to **predict the hands-object pose**. This could be summarized in this challenge  https://sites.google.com/view/hands2023/challenges/task2. Basically we will start with a single image model like https://github.com/namepllet/HandOccNet and we extend it for 2 hands and object. Furthermore, the predictions should be temporally smooth, so the model could consider multiple predictions over time instead of one.
![](https://hackmd.io/_uploads/Byfov5o22.png)

Some other source code projects that could be extended to fit the task:
[1] - https://github.com/hassony2/homan
[2] - https://eldentse.github.io/s2contact/
[3] - https://zerchen.github.io/projects/alignsdf.html


## Related Work
* Latest papers about Hand Pose Estimation (HPE)/Hand Object Pose Estimation (HOPE) could be found here[](https://github.com/xinghaochen/awesome-hand-pose-estimation)
* Some interesting models with GitHub code are available (Please also check the papers): 
    * HPE  https://github.com/namepllet/HandOccNet
    * HPE https://github.com/microsoft/MeshTransformer
    * HOPE https://zerchen.github.io/projects/alignsdf.html
    * HOPE (from video) https://hassony2.github.io/homan.html
* The dataset we want to focus on is arctic https://arctic.is.tue.mpg.de/
    * You can register in the iccv workshop so that we can submit evaluation after the contest is over https://sites.google.com/view/hands2023/challenges/arctic.
* Other similar datasets we can use
    * H2o https://github.com/taeinkwon/h2odataset
    * HOI4D https://hoi4d.github.io/
    * DexYCB https://dex-ycb.github.io/

## HandOccNet 
![](https://hackmd.io/_uploads/rk3cd5ihn.png)
