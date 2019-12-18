# Nuclear image synthesis and segmentation code

This repository contains source code for the following paper:  
Robust Histopathology Image Analysis: to Label or to Synthesize? Hou, Le and Agarwal, Ayush and Samaras, Dimitris and Kurc, Tahsin M and Gupta, Rajarsi R and Saltz, Joel H. Computer Vision and Pattern Recognition (CVPR), 2019  

You need the following python2 libraries to run this software:  
```
tensorflow  
scipy  
numpy  
json  
pickle
cv2 
```

If you want to obtain initial synthetic images with nuclear masks, please read training-data-synthesis/README.md  
If you want to train your nuclei segmentation model, or use our trained nuclei segmentation model, please read segmentation-of-nuclei/README.md 

This software uses several open source repositories, especially [this one](https://github.com/carpedm20/simulated-unsupervised-tensorflow)

## Trained model and released segmentation results

We also include:  
1. A Dockerfile with trained model [here](Dockerfile)  
2. Segmentation results we've already generated [here](https://stonybrookmedicine.app.box.com/s/7n9gdy3i6qmm638or7lbxrzzydb1iv9b) with [readme](https://stonybrookmedicine.app.box.com/notes/461635773066?s=7n9gdy3i6qmm638or7lbxrzzydb1iv9b).
