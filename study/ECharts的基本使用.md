# Echarts的介绍

Echarts是一个使用JavaScript实现的开源可视化库，兼容性强，底层依赖矢量图形库ZRender，提供直观，交互丰富，可高度个性化定制的数据可视化图表。

## ECharts的特点

- 丰富的可视化类型
  - 折线图、柱状图、饼图、K线图……
  - 只有你想不到，没有它做不到
  - [https://echarts.apache.org/examples/zh/index.html](https://echarts.apache.org/examples/zh/index.html)
- 多种数据格式支持
  - key-value数据格式
  - 二维表
  - TypedArray格式

- 流数据的支持
  - 流数据的动态渲染
  - 增量渲染技术


# Echarts的快速入门

## ECharts的基本使用

- 5分钟上手ECharts

  - 步骤1：引入echarts.js文件
  - 步骤2：准备一个呈现图表的盒子
  - 步骤3：初始化echarts实例对象
  - 步骤4：准备配置项
  - 步骤5：将配置项设置给echarts实例对象

- 效果：

  ![image-20250108154004909](G:\echarts-online\study\assets\效果图)

- 配置项的使用
  - 除了配置项会变化之外，其他的代码都是固定的
  - 配置项的学习和使用应参照官方文档和示例

## 相关配置项的讲解

- xAxis：直角坐标系中的x轴
- yAxis：直角坐标系中的y轴
- series：系列列表。每个系列通过type决定自己的图表类型

![image-20250108195048769](G:\echarts-online\study\assets\image-20250108195048769.png)

- 官方文档的查阅
- 配置项太多，无需去刻意记忆





# Echarts的常用图表

- 7大图表
  - 图表1：柱状图
  - 图表2：折线图
  - 图表3：散点图
  - 图表4：饼图
  - 图表5：地图
  - 图表6：雷达图
  - 图表7：仪表盘图

## 图表1：柱状图

- 实现步骤
  - ECharts最基本的代码结构：引入js文件，DOM容器，初始化对象，设置option
  - x轴数据：数组1：['张三','李四','王五','闰土','小明','茅台','二妞','大强']
  - y轴数据：数组2：[88,92,63,77,94,80,72,86]
  - 图表类型：在series下设置type：bar

- 常见效果
  - 标记：最大值  最小值  平均值
  - 显示：数值显示  柱宽度  横向柱状图

