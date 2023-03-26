# 御坂妹妹的护目镜  
一个基于树莓派的ACG周边项目。原型是《魔法禁书目录》中**御坂美琴**的克隆体**御坂妹妹**所佩戴的护目镜  
  
TODO：  
- 通透模式（通过摄像头捕捉外部画面）  
- 红外线夜视  
- 红外线热成像  
- 多通道混合  
- 录制视频  
- 画面放大  
- 边缘捕捉  
- 对比两帧的区别  
- 实时串流（外部处理图像）  
- 正面发光  

## 硬件组成  
### 树莓派（CM4）
- 捕捉摄像头图像  
- 处理视频流  
- 屏幕显示  
- 实时串流  
- 录制视频  
---
### ESP8266
- 通过串口与树莓派连接，处理设备io  
- 控制灯光  
- 检测电压  
- 控制夜视  
