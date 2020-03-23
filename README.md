# FGH_Track_Editor
  开始是个很糟糕的程序，但经过XavierG-Cons同志的修改后好起来了  
## 功能：  
  简单的赛道编辑导入导出，要求输入excel格式xlsx  
  data1：x坐标  
  data2：y坐标  
  data3：左右锥桶（1、2代表锥桶颜色）</br></br>
## How to use?
  将需要描点的锥桶数据放置在Map.xlsx中  
    要求格式：  
    第一列：x坐标；第二列：y坐标；第三列：锥桶颜色</br></br>
## Windows：   
    Python3就能跑啦   
    pip install openpyxl -i https://pypi.tuna.tsinghua.edu.cn/simple  
    pip install matplotlib -i https://pypi.tuna.tsinghua.edu.cn/simple  
  
## Linux：  
    除了上面两条指令之外呢，还要附加一条  
    sudo apt-get install python3-tk
    </br>
## 关于Tkinter:  
  在命令行中运行 python -m tkinter，应该会弹出一个Tk界面的窗口，  
  表明 tkinter 包已经正确安装，而且告诉你 Tcl/Tk 的版本号，  
  通过这个版本号，你就可以参考对应的 Tcl/Tk 文档了。  
