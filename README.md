# 3d reconstruction

WIP: 3d reconstruction from 2d images pipeline

Steps:
* Projection
* Detection
* Triangulation
* Bundle adjustment

## Prerequisites
* Python 3.3+
* Install [opencv](http://opencv.org/)
* pip install -r requirements.txt

## 3D to 2D Projection
3D points of model house from Oxford University VGG datasets.
![](testsets/house_3d.png?raw=true)

Projected points

![](testsets/3d_to_2d_projection.png?raw=true)
## Datasets
* Oxford University, Visual Geometry Group: http://www.robots.ox.ac.uk/~vgg/data/data-mview.html
