### compass.calibrate()
- 执行此函数开始校准过程，会收到一条有指导意义的信息，然后我们需要旋转板子，在空中画一'8'或着转圈，(这个动作可以参考你的手机，手机的指南针功能在使用之前都会有一个校准的步骤)，这个校准的过程会占用大概1分钟的时间，校准期间无法执行其他程序
- 提示信息
 ![prompt](album/prompt.png)

### compass.is_calibrated ()

- 如果罗盘校准成功，返回True，否则返回False。

### compass.get_x ()

- 返回x轴上磁场强度的读数，它是一个正整数或负整数，取决于磁场的方向。

### compass.get_y ()

- 返回y轴上磁场强度的读数，它是一个正整数或负整数，取决于磁场的方向。

### compass.get_z ()

- 返回z轴磁场强度的读数，它是一个正整数或负整数，取决于磁场的方向。

### compass.heading()

- 给出从上述读数计算出的罗盘航向，为0到360范围内的整数，表示按顺时针方向的角度，12点钟方向为0

### compass.get_field_strength()

- 返回设备周围磁场大小，它是一个整数。