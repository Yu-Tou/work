# work
从代码到实物期末项目
# 1 三维设计
通过fusion 360软件制作手指夹板的三维模型，并保存为3D文件1.stl和2.stl。
# 2 3D打印
利用学校工训基地408和510所提供的3D打印机将1.stl和2.stl文件里的3D模型进行打印。
# 3 程序编写
## 3.1 驱动下载与编写
通过链接https://doc.itprojects.cn/0006.zhishi.esp32/01.download/dirver/max30102.zip 将驱动下载，得到两个文件_init_.py和circular_buffer.py。  
然后编写OLED驱动代码ssd1306.py。  
并使用thonny将上述所有代码文件上传到ESP32
## 3.2 编写代码
在Micorpython端，编写代码文件hrcalc.py，来可以计算出血氧值。  
编写简易检测心率、血氧、温度代码以及OLED显示代码————代码.py。
# 4 电路连接
连接max30102模块以及OLED屏幕。
