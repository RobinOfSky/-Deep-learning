#### Seaborn

Seaborn其实是在matplotlib的基础上进行了更高级的API封装，从而使得**作图更加容易**，在大多数情况下使用seaborn就能做出很具有吸引力的图，而使用matplotlib就能制作具有更多特色的图。应该把Seaborn视为matplotlib的补充，而不是替代物。同时它能高度兼容**numpy**与**pandas**数据结构以及**scipy**与**statsmodels**等统计模式。掌握seaborn能很大程度帮助我们更高效的观察数据与图表，并且更加深入了解它们。

- 特点
  - 基于matplotlib aesthetics绘图风格，增加了一些绘图模式
  - 增加调色板功能，利用色彩丰富的图像揭示您数据中的模式
  - 运用数据子集绘制与比较单变量和双变量分布的功能
  - 运用聚类算法可视化矩阵数据
  - 灵活运用处理时间序列数据
  - 利用网格建立复杂图像集

- 箱图：箱形图（Box-plot）又称为盒须图、盒式图或箱线图，是一种用作显示一组数据分散情况资料的统计图。因形状如箱子而得名。在各种领域也经常被使用，常见于品质管理。它主要用于反映原始数据分布的特征，还可以进行多组数据分布特征的比 较。箱线图的绘制方法是：先找出一组数据的上边缘、下边缘、中位数和两个四分位数；然后， 连接两个四分位数画出箱体；再将上边缘和下边缘与箱体相连接，中位数在箱体中间。

  - 最大值，最小值，上四分位数，下四分位数，中位数

    ```python
    boxplot(x=None, y=None, hue=None, data=None, order=None, hue_order=None,
                orient=None, color=None, palette=None, saturation=.75,
                width=.8, dodge=True, fliersize=5, linewidth=None,
                whis=1.5, notch=False, ax=None, **kwargs)
    # orient=v/h  v表示绘制方向是竖直，h表示水平绘制
    # 
    ```

    

