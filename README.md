 
 ## Detecting feautures - Corners
 
 **[NOTE]:** There are some attributes of OpenCV work only when you have OpenCV version **3.4.2.16** 
    to install the version just run these commands 
   
   ```
    pip install opencv-python==3.4.2.16
    pip install opencv-contrib-python==3.4.2.16 
   ```
 
 
 **Algorithm used** - cornerHarris
 
 run the following command in the shell 
 
 ```
 python cornerHarris.py
 ```
 
 **RESULTS**
 
![](https://github.com/noorkhokhar99/SIFT-surf/blob/main/images/cornerHarris.jpg)


## Feature extraction and description using DOG and SIFT

run the following command 
```
python SIFT.py --input images/ 
```

**RESULTS**

![](https://github.com/noorkhokhar99/SIFT-surf/blob/main/images/SIFT.jpg)


## Feature extraction and description using Fast Hessian and SURF

run the following command
```
python SURF.py --input images/ --algorithm SIFT
or

python SURF.py --input images/ --algorithm SURF
```

**RESULTS**

Original | SURF | SIFT 
---------|-------|------
![](https://github.com/noorkhokhar99/SIFT-surf/blob/main/images/city2.jpg) | ![](https://github.com/noorkhokhar99/SIFT-surf/blob/main/images/detected-SURF.jpg) | ![](https://github.com/noorkhokhar99/SIFT-surf/blob/main/images/detected-SIFT.jpg)


## Feature matching using ORB (Oriented FAST and Rotated BRIEF)

run the following command 
```
python ORB.py --input images/
```

**RESULTS**

Image-1 | Image-2 | Feature Match
--------|---------|--------------
![](https://github.com/noorkhokhar99/SIFT-surf/blob/main/images/Breaking%20Bad.jpg) | ![](https://github.com/noorkhokhar99/SIFT-surf/blob/main/images/Breaking%20Bad-2.jpg) | ![](https://github.com/noorkhokhar99/SIFT-surf/blob/main/images/ORB.jpg)


## Feature matching using KNN

run the following command 

```
python KNNmatching.py --input images/
```

**RESULS**

![]()
