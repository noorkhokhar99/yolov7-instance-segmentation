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
- Download weights from [link]() and store in "yolov7-segmentation" directory.

- Run the code with mentioned command below.
```
#for segmentation with detection
python3 segment/predict.py --weights yolov7-seg.pt --source "videopath.mp4"

#for segmentation with detection + Tracking
python3 segment/predict.py --weights yolov7-seg.pt --source "videopath.mp4" --trk
```

- Output file will be created in the working directory with name <b>yolov7-segmentation/runs/predict-seg/exp/"original-video-name.mp4"</b>

### RESULTS
<table>
  <tr>
    <td>Car Semantic Segmentation</td>
     <td>Car Semantic Segmentation</td>
     <td>Person Segmentation + Tracking</td>
     </tr>
  <tr>
    <td><img src="https://user-images.githubusercontent.com/62513924/190402435-931f0ee3-9af1-4399-8222-1028d5afbd1a.png" width=640 height=180></td>
    <td><img src="https://user-images.githubusercontent.com/62513924/190402752-521b7815-bea8-4cef-8b36-54fb7a962244.png" width=640 height=180></td>
    <td><img src="https://user-images.githubusercontent.com/62513924/191729411-a8d8b5e2-bdbf-4c0e-bd1b-a52e23f7c9d3.png" width=640 height=180></td>
  </tr>
  </tr>
 </table>


