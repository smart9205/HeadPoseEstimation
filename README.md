# Head Pose Estimation - OpenCV

In computer vision pose estimation specifically refers to the relative orientation of the object with respect to a camera. Pose estimation often referred to as a Perspective-n-Point problem or PNP problem in computer vision.

![result](https://user-images.githubusercontent.com/114035408/235356169-2558ac5b-d088-4c29-8fa4-1b61d4e21a67.png)

## Installation

Using the package manager [pip](https://pip.pypa.io/en/stable/).

```bash
pip install -r requirements.txt
```
```bash
cd models
bash downloader.sh
cd ..
```
## Usage
#### Get Pose From Image
```
python sample.py

#### For source 0 and focal length 1
python head_pose_from_webcam.py -f 1 -s 0
```
#### 3D model visualization
```
python Visualize3DModel.py
```
