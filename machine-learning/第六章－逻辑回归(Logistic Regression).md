## 第六章－逻辑回归（Logistic Regression）

### 6.1 逻辑回归表达式
![](resource/6-1.jpg)

### 6.2 代价函数（cost function）
![](resource/6-2.jpg)
对于线性回归模型，我们定义的代价函数式所有模型误差的平方和。但对于逻辑回归，若使用该代价函数，我们得到的将是一个非凸函数（non-convex function）
![](resource/6-3.jpg)
逻辑回归代价函数

![](resource/6-4.jpg)
逻辑回归的梯度推导：
![](resource/6-５.jpg)
![](resource/6-6.jpg)
![](resource/6-7.jpg)
得到梯度下降算法：
![](resource/6-8.jpg)
该公式与线性回归的跟新公式式一致的，但ｈ的表达式式不同的。
![](resource/6-9.jpg)



