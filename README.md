# 交互式旋转矩阵演示

本项目提供了一个直观、可交互的3D旋转矩阵演示工具，帮助学习和理解3D空间中的旋转变换原理。

!<img width="1422" alt="Screenshot 2025-04-21 at 12 18 14" src="https://github.com/user-attachments/assets/b588e0e5-5507-4037-8046-28c1ec8416de" />

## 项目描述

本项目包含多种旋转矩阵的可视化演示：

1. **交互式网页演示** - 使用Three.js实现的3D交互演示，可实时拖动调整旋转角度
2. **Python ASCII艺术演示** - 使用Python实现的命令行旋转立方体
3. **教学动画** - 使用Manim制作的旋转矩阵教学视频

## 文件结构

- `index.html` - 交互式旋转矩阵网页演示
- `rotation_cube.py` - Python版ASCII艺术旋转立方体
- `rotation_matrix_animation.py` - Manim教学动画脚本 (TODO)
- `interactive_rotation_demo.py` - Manim交互概念演示 (TODO)

## 功能特点

### 交互式网页演示 (index.html)

这是一个基于Three.js的交互式3D演示，功能包括：

- 实时调整X、Y、Z三个轴的旋转角度
- 动态显示各轴的旋转矩阵及组合旋转矩阵
- 多角度视图切换（正视图、俯视图、侧视图、等轴测视图）
- 彩色坐标轴和标签，便于识别


## 如何使用

### 网页演示

1. 启动本地服务器：
   ```
   python -m http.server 8080
   ```

2. 在浏览器中访问：
   ```
   http://localhost:8080
   ```

3. 使用滑块调整X、Y、Z轴的旋转角度，观察立方体的旋转和矩阵的变化。

4. 点击视角按钮切换不同的观察角度。



### Python旋转立方体

运行ASCII艺术旋转立方体：

```bash
python rotation_cube.py
```

## 技术栈

- **Web**: HTML, CSS, JavaScript, Three.js, Math.js
- **Python动画**: Manim (Mathematical Animation Engine)
- **Python 3D**: NumPy

## 教学应用

本项目适用于：

- 线性代数教学
- 计算机图形学入门
- 3D游戏开发基础
- 机器人学旋转表示介绍

## 延伸阅读

若要深入了解旋转矩阵和3D变换，推荐探索：

- 四元数(Quaternions)
- 欧拉角(Euler Angles)
- 罗德里格斯旋转公式(Rodrigues' Rotation Formula)
