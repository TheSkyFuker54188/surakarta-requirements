# **Surakarta第二阶段报告**
## **一、代码实现**
### **A.初步实现游戏界面**
>#### 1.绘制棋盘棋子：导入图片资源进行绘制paintEvent及Drawchess，同时设置行列以方便绘制及后续棋子位置判断。
>#### 2.计时器：timerEvent函数中通过ui界面的label显示倒计时。
>#### 3.选子落子：在mousePressEvent函数中判断上一次点击是否选中过棋子，并分别实现落子或选子。在每次落子操作时判断能否移动到鼠标点击位置，完成落子操作同时重绘和重新倒计时。
>#### 4.游戏结束弹窗：在IsDead函数中，通过ui界面label实现，关闭弹窗同时开启下一局游戏，初始化棋盘。我们还设置了认输键（ui中的pushBotton），点击即实现IsDead函数，判断胜负。
### **B.逻辑判断**
#### 判断canMove：在chessmovelaw中加入了上一阶段写的规则判断。
### C.问题
#### 在构建显示界面时棋子和棋盘的位置存在一定偏差，且棋子大小不能随鼠标拖拽改变界面大小而改变。
## **二、任务分工**
#### 思路分析：项晓清 李玉玺 刘雪琦
#### 代码实现：刘雪琦 项晓清
#### 报告完成：刘雪琦
