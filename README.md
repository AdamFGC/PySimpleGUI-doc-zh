# PySimpleGUI-doc-zh
## PySimpleGUI 中文文档 &amp; 教程

![header](https://github.com/AdamFGC/PySimpleGUI-doc-zh/assets/156168492/8923ad04-8588-4d23-9ee1-3e4ebf6a752d)

官网链接：[www.pysimplegui.com](https://www.pysimplegui.com/)

## PySimpleGUI 使用 Python 简单、快速地创建图形用户界面 (GUI)！

### 快速开始！

#### 1、确保安装好Python

#### 2、安装 PySimpleGUI:

```
python -m pip 安装 pysimplegui
```

#### 3、创建main.py , 包含以下代码：
```
# 导入PySimpleGUI模块
import PySimpleGUI as sg 

# 创建窗口的所有内容
layout = [
  [sg.Text("What's your name?")], 
  [sg.InputText()], 
  [sg.Button('Ok'), sg.Button('Cancel')]
] 

# 创建窗口 Window
window = sg.Window('Hello Example', layout) 

# 创建事件循环，获取处理的“事件”<event>，和输入的“值”<values> 
while True: 
    event, values = window.read() 

    # 如果用户关闭窗口或单击取消，取消循环
    if event == sg.WIN_CLOSED 或 event == 'Cancel': 
        break 

    print('Hello', value[0], '!')

# 取消循环，窗口关闭
window.close()
```
#### 4、开始运行！
```
python main.py
```
您将会看到此窗口：

![new-sample-app](https://github.com/AdamFGC/PySimpleGUI-doc-zh/assets/156168492/d4c8c64e-8b49-422b-8b06-02c5260c911d)

尝试一下，您可以与这个PySimpleGUI创建的窗口示例进行交互。

接下来就开始吧！轻松愉快地使用PySimpleGUI创建的属于你的GUI！该文档告诉您需要了解的一切

您有 30 天的时间来尝试 PySimpleGUI。在试用结束之前，您需要订阅：

* 爱好者免费

* 商业订阅起价为 99 美元/年

如果您愿意，现在就可以[注册](https://www.pysimplegui.com/pricing)！



