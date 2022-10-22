# yolov7-instance-segmentation



## Steps to run Code

- Clone the repository
```
git clone https://github.com/noorkhokhar99/yolov7-instance-segmentation.git
```
- Goto the cloned folder.
```
cd yolov7-segmentation
```


- Upgrade pip with mentioned command below.
```
pip install --upgrade pip
```
- Install requirements with mentioned command below.
```
pip install -r requirements.txt
```
- Download weights from [link](https://github.com/noorkhokhar99/yolov7/blob/main/yolov7-seg.pt) and store in "yolov7-segmentation" directory.

- Run the code with mentioned command below.
```
#for segmentation with detection
python segment/predict.py --weights yolov7-seg.pt --source "videopath.mp4"

#for segmentation with detection + Tracking
python segment/predict.py --weights yolov7-seg.pt --source "videopath.mp4" --trk
```

- Output file will be created in the working directory with name <b>yolov7-segmentation/runs/predict-seg/exp/"original-video-name.mp4"</b>

### RESULTS

<img src="https://github.com/noorkhokhar99/yolov7-instance-segmentation/blob/main/Screen%20Shot%201444-03-26%20at%207.04.59%20PM.png">



