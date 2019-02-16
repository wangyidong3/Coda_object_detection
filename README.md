# Coda Digital Eye
Detect the forklifts and persons in the warehouse and give the warnings when the violations of the rules are detected.
[Download trained model](https://drive.google.com/open?id=1V9bSbqPMimM9cHK8euQqn6nQRzKwzSfi)

![alt text](https://github.com/wangyidong3/Coda_object_detection/blob/master/out/forklift%20detection.gif)


The object detection for forklifts and person is based on ```ssd_mobilenet``` and ```tiny-yolo(coco)```

Add: ```YOLOV3```


## Usage

### 1. tiny-yolo

* download the [tiny-yolo](https://drive.google.com/file/d/14-5ZojD1HSgMKnv6_E3WUcBPxaVm52X2/view?usp=sharing) file and put it to model_data file

```baash 
$ python3 test_tiny_yolo.py 
```

### 2. ssd-mobilenet

```baash 
$ python3 test_ssd_mobilenet.py 
```

### 3. YOLOV3

* download the [yolov3](https://drive.google.com/open?id=1vdD9TPiTWqvPxtCXdbVSKKksSdu0j_Hn) file and put it to model_data file

```baash 
$ python3 test_yolov3.py 
```

## YOLOV2 vs YOLOV3

* YOLOV2
![YOLOV2](/out/dog2.jpg)


* YOLOV3
![YOLOV2](/out/dog.jpg)

## Acknowledgments

* Thanks to [keras-yolo3](https://github.com/qqwweee/keras-yolo3) for yolov3-keras part# Coda_object_detection

