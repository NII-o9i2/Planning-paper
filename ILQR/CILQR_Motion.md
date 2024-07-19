### 1. Vehicle Model
  车辆模型{x,y}坐标系下
  $$
\dot{x} = v \cdot \cos (\psi+\beta) \\
\dot{y} = v \cdot \sin (\psi+\beta) \\
\dot{v} = a \\
\dot{\psi} = \frac{v \cdot \cos \beta}{L} \cdot \begin{bmatrix} \tan \delta_f - \tan \delta_r \end{bmatrix} 	
  $$

将其近似于（高速下带来的影响未知）：
  $$
\dot{x} = v \cdot \cos (\theta) \\
\dot{y} = v \cdot \sin (\theta) \\
\dot{v} = a \\
\dot{\psi} = \frac{v}{L} \cdot \tan \theta 	
  $$