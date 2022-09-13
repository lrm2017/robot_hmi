# 多场景ROS人机交互界面



## 安装依赖

```bash
sudo apt-get install libqt5location5 libqt5multimedia5 libqt5quickcontrols2-5
```

## 运行

```bash
rosrun cyrobot_monitor cyrobot_monitor 
```

## 开机主界面

![](%E5%9B%BE%E7%89%871-166305957824519.png)对于阿克曼消息类型，自动切换到摇杆控制，对应差速消息类型，切换到全向控制

<img src="%E5%9B%BE%E7%89%876.png" style="zoom: 80%;" />

### 图像窗口

图像显示窗口，可以右键选择显示的图像数量

![](%E5%9B%BE%E5%83%8F%E6%98%BE%E7%A4%BA%E7%AA%97%E5%8F%A3-166305971616545.png)

在此设置图像话题

![](%E5%9B%BE%E5%83%8F%E8%AF%9D%E9%A2%98-166305972857647.png)

### rviz

集成了rviz模块

![](rviz-166305975046149.png)

###  数据显示模块

需要设置对应的话题与参考坐标系

![](%E5%9B%BE%E7%89%878-166305977254451.png)

![](%E5%9B%BE%E7%89%877-166305977772353.png)

### 地图

采用qml写的地图，地图来源与openstreetmap

![](%E5%9B%BE%E7%89%879-166305980265555.png)
