# BARN_homework
run不起来的话，先:

```
 sudo apt-get install ros-noetic-diff-drive-controller
 sudo apt-get install ros-noetic-joint-state-controller
 sudo apt-get install ros-noetic-move-base
```

几个地方需要改：
1. 目标点改成自动设置的

几个地方可以改进：
2. 可调节下控制器参数使得控制性能更好
3. 如果把轨迹转成Polynome格式，可以启用里面的mpc控制器
