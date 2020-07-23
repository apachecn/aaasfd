# yolov3_rotate_demo
yolov3旋转矩形，倾斜框检测；

基于ultralytics pytorch版本yolov3改进而成，在hrsc2016舰船数据集上测试，608x608单尺度下，mAP 可以达到0.8+，在nms=0.3, conf=0.01下可以达到mAP 0.84。另代做目标检测毕设项目及代打比赛，本人多次获得天池视觉类比赛前十；

源码有偿，如有需要请加v：clwclw_

![这里随便写文字](https://github.com/clw5180/yolov3_rotate_demo/blob/master/1.jpg)  

![这里随便写文字](https://github.com/clw5180/yolov3_rotate_demo/blob/master/100000658.jpg)  

![这里随便写文字](https://github.com/clw5180/yolov3_rotate_demo/blob/master/100000679.jpg)  

![这里随便写文字](https://github.com/clw5180/yolov3_rotate_demo/blob/master/100000984.jpg)  



目前实现了几种针对倾斜框的数据增强方式（如典型的randomcrop, translate, rotate，resize等），在训练时加入能够大幅提升识别效果；

![这里随便写文字](https://github.com/clw5180/yolov3_rotate_demo/blob/master/RandomRotateAngle2.jpg)  

![这里随便写文字](https://github.com/clw5180/yolov3_rotate_demo/blob/master/RandomRotateAngle.jpg)  

