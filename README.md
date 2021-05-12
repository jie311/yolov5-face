## yolov5-face

在yolov5的基础上增加landmark预测分支，loss使用wingloss,使用yolov5s取得了相对于retinaface-r50更好的性能。

#### WiderFace测试

* 在wider face val精度（单尺度最大边输入分辨率：**1024**）

| Backbone                             | Easy  | Medium | Hard  | Flops(640*640) | Params |
| ------------------------------------ | ----- | ------ | ----- | -------------- | ------ |
| yolov5s                              | 95.4% | 94.6%  | 88.2% | 8.2G           | 7.1M   |
| yolov5m                              | 95.8% | 95.1%  | 90.5% | 25.3G          | 21.2M  |
| yolov5s6                             | 95.5% | 94.5%  | 90.1% | 8.4G           | 12.4M  |
| RetinaFace-R50(original image scale) | 95.5% | 94.0%  | 84.4% | 44.5G          | 27.3M  |
| mobilenetv3s                         |       |        |       | 3.02G          | 3.57M  |

#### 模型测试下载地址

* yolov5s:链接: https://pan.baidu.com/s/1t51CFeofy1slOw_lgb3UDg  密码: mkh0
* Yolov5m:

#### 模型测试效果

![](data/images/result.jpg)



#### References

https://github.com/ultralytics/yolov5

https://github.com/DayBreak-u/yolo-face-with-landmark

https://github.com/xialuxi/yolov5_face_landmark

https://github.com/biubug6/Pytorch_Retinaface