# Face-Mask-Detection-internship-iNeuron
## :running: :walking: :dancer: Pose-With-Action
![pose_with_action](https://user-images.githubusercontent.com/62059604/99776776-5db0de00-2b37-11eb-97e7-b39f53f2d703.gif)

![Untitled design (4)](https://user-images.githubusercontent.com/62059604/99800421-5818bf80-2b5a-11eb-83ad-c0fe6a2d48be.png)

![Untitled design (5)](https://user-images.githubusercontent.com/62059604/99800592-9e6e1e80-2b5a-11eb-8f70-4796dd0ee36a.png)

- This repository represents **" Face mask detection using MobileNetV2 "**.
- With the help of this project we can detect if a person is wearing a mask or not based on the **Face Detection**.
  
## 📝 Description
- In this project we have used **MobileNetV2** and **Face Detection model** for mask detection .

## ⏳ Dataset
- Download the dataset for custom training and place those two folders  in a folder named **"dataset"**
- https://drive.google.com/drive/folders/1WCxe1EuxLo6qyGVpupcEMTgN83xpgHM_ 

## :desktop_computer:	Installation

### :Requirements
* Python 3.6+
* tensorflow>=1.15.2
* keras==2.3.1
* imutils==0.5.3
* numpy==1.18.2
* opencv-python==4.2.0.*
* matplotlib==3.2.1
* scipy==1.4.1

## :gear: Setup
1. Install PyTorch :-
```bash
$ pip3 install torch==1.1.0 torchvision==0.3.0

```
2. Install :-
```bash
$ export PATH=/usr/local/cuda/bin/:$PATH

```
```bash
$ export LD_LIBRARY_PATH=/usr/local/cuda/lib64/:$LD_LIBRARY_PATH

```
```bash
$ pip install cython

```
```bash
$ sudo apt-get install libyaml-dev

```
```bash
$ python setup.py build develop --user

```
```bash
$ python -m pip install Pillow==6.2.1

```
```bash
$ pip install -U PyYAML

```
## 🎯 Inference demo
1. Testing with **Images** ( Put test images in **AlphaPose/examples/demo/** )  :-
```bash
$ python scripts/demo_inference.py --cfg configs/coco/resnet/256x192_res50_lr1e-3_1x.yaml --checkpoint pretrained_models/fast_res50_256x192.pth --indir examples/demo/ --save_img

```
2. Testing with **Video** ( Put test video in **AlphaPose/examples/demo/** )  :-
```bash
$ python scripts/demo_inference.py --cfg configs/coco/resnet/256x192_res50_lr1e-3_1x.yaml --checkpoint pretrained_models/fast_res50_256x192.pth --video examples/demo/3.mp4 --outdir examples/res1 --save_video --gpus 0

```


### :book: Please Go through [Pose_With_Action_HLD2.docx](https://github.com/iNeuron-ai/Pose-with-Action/blob/main/doc/Pose_With_Action_HLD2.docx) for more info.


## Contributors <img src="https://raw.githubusercontent.com/TheDudeThatCode/TheDudeThatCode/master/Assets/Developer.gif" width=35 height=25> 
- Akshay Kumar Prasad	
- Akshay Namdev Kadam	
- Arjun K	
- ATUL KUMAR	
- Deepak Kumar Behera	
- Jerryl Davis	
- Kancharla Bharath Kumar	
- Karthik P	
- Madhavi Patel	
- Mukesh	
- Oinam Bhobendra	
- pamita singh kandari	
- Sameer sudhir Deshmukh	
- Sasidharan M	
- shrinivas kandlikar

