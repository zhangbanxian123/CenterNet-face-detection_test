# CenterNet-face-detection
Face detect and expression recognition in videos use CenterNet

## Requirement
- OpenCV
- Python 3.6
- Pytorch 0.4.1
- torchvision 0.2.1
## train and test
If you need to retrain your dataset，make sure put the dateset into the right path data/meetingpic/images,then run：
python src/main.py 
If you want to test the demo, please download the pre-trained model from [Baiduyun](https://pan.baidu.com/s/1OT8qffrzAhxn3VFHMR6y3w) first， then
put it in ./models/,and then run：
python src/demo.py --demo /path/to/image/or/folder/or/video --load_model ../models/model_last.pth
## Results

![output/test1.png](output/6ctdet.png)
![output/test2.png](output/18ctdet.png)

## Reference
https://github.com/xingyizhou/CenterNet


