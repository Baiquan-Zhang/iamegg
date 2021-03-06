# iamegg

Game Jam 2019, Bristol.

Unity 3D project called iamegg. 

# How to install

[build.zip](https://github.com/Merle-Zhang/iamegg/releases/download/0.1.0/build.zip)

Unzip the build.zip, run `iamegg.exe`, then enjoy the game!

# Demo

![Menu](Demo/Menu.jpg)

![Options](Demo/Options.jpg)

![Egg](Demo/Egg.jpg)

![Fried Egg](Demo/FriedEgg.jpg)

![Congratulation](Demo/congratulation.jpg)

[Video Demo](https://github.com/Merle-Zhang/iamegg/blob/master/Demo/Demo.flv)

# Design

Control an egg or/and a fried egg to complete missions in the kitchen!

# Control

Hold the right mouse button to rotate around the egg!

For egg, use WASD to move!

For fried egg, use 2/3/4 to hold a joint, and hold left mouse button to give a force to the fried egg!

# Levels

#### 1. Tutorial Level

Get the egg fried by falling into the pan, then move the fried egg into the plate!

#### 2... Coming soon!

# To-dos

- [ ] Multiple levels
- [ ] BGM
- [ ] Lose the game if fried egg get flipped
- [ ] Get lower score if stay in fried pan too long or too short
- [ ] Better model, UI, Texture, Material


# Developer

* Merle - Control
* Alfred - Physics
* Anna - Camera
* Baiquan - Modeling
* RainZ - Music, Camera, Modeling
















































































=========================================

Dev doc



分工

模型 Baiquan

场景/地图 Baiquan

Camera Anna

物理 Alfred

控制 Merle

sound RainZ








i am egg

* 不能掉地上
* 熟之前是鸡蛋
* 熟了之后不能反面
* 不能烤焦
* 障碍
* 躲老鼠 捕鼠板 陷阱



1. 场景
   1. 厨房
2. character
   1. egg
   2. 蛋壳
      1. 蛋液
   3. 荷包蛋 固定形状
3. movement
   1. 蛋壳
      1. 滚动
      2. wasd
   2. 荷包蛋
      1. imbread
      2. 四个支点 一个在蛋黄 零三个在边上
      3. 鼠标方向
4. 煎蛋时间
   1. 闹钟提示
      1. 10s开始爬
      2. 10s-20s爬出来
      3. 20s之后评分低
5. challenge
   1. 不能掉地上
   2. 熟之前是鸡蛋
   3. 熟了之后不能反面
   4. 不能烤焦
   5. 障碍
   6. 躲老鼠 捕鼠板 陷阱
6. 关卡
   1. 高处掉落 摔进锅里 爬出来 进盘子
      1. 开场在高处
      2. 鸡蛋滚到边缘摔进锅里
      3. 锅里蛋碎 开始煎蛋 旁边闹钟开始计时
      4. 10s开始爬
      5. 10s-20s爬出来
      6. 20s之后评分低
      7. 爬出锅进入旁边的盘子
      8. 结束
   2. 













### Fun Ideas

* egg
* 推箱子
* 2d shooting
* 吃豆人
* 视觉错觉
* 横版闯关







1. 物理引擎沙雕游戏, e.g. iambread iamfish
   1. 物理引擎
   2. 操作难度大
2. i am egg
   * 不能掉地上
   * 熟之前是鸡蛋
   * 熟了之后不能反面
   * 不能烤焦
   * 障碍
   * 躲老鼠 捕鼠板 陷阱
3. 推箱子
   1. 摩擦力0
   2. 推箱子 无摩擦 动量守恒
   3. 视觉错觉
4. ~~动作游戏, e.g. dark soul~~
   1. 2d or 3d
   2. 无敌帧
5. ~~**潜行**~~
   1. 2d or 3d
   2. 
6. 2d shooting
   1. 2d cod
   2. 迷宫
   3. 关门时不知道门后敌人情况
   4. 
   5. 横板or俯视
7. ~~养成游戏~~
   1. 
8. 吃豆人 3d
   1. 《黑暗欺骗》第一关， 恐怖游戏chi
   2. 吃豆子
   3. 迷宫
   4. 敌人
9. ~~神奇宝贝~~
   1. 
10. ~~底特律变人~~
    1. QTE
    2. RPG
11. 视错觉
    1. non Euclidean game engine
12. 横版闯关 iwana 马里奥
13. 打砖块

11. flappy bird
    1. 2 d 3d

12. ~~即时战略~~



### Fun Features

1. falling only when he knows
2. nonlinear blood bar
