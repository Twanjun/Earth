**CityEngine 简介**
> Esri CityEngine是由苏黎世Esri研发中心（前身为Procedural Inc.）开发的三维（3D）建模软件应用程序，专门用于生成3D城市环境。通过程序建模方法，CityEngine支持创建详细的大型3D城市模型。 CityEngine以与VUE管理地形，生态系统和大气测绘相同的方式与建筑物体的放置和布置一起工作。与使用计算机辅助设计（CAD）工具的传统3D建模方法不同，CityEngine通过基于规则的系统和数据集改进形状生成 - 类似于地理信息系统（GIS）。由于这一主要特征，CityEngine已广泛用于学术研究或构建虚拟环境，例如城市规划，建筑，可视化，游戏开发，娱乐，GIS，考古学和文化遗产。在与建筑信息模型（BIM）相结合后，CityEngine可以在更大的城市环境中可视化建筑物的数据，从而将其工作场景提升到真正的建筑项目。
>
> 来源维基百科

**产品特点**

* 基于规则批量建模

  * CGA 规则编写，快速批量生成三维模型
  * 道路、建筑、绿化

* 动态的城市规划设计

  * CGA 规则中将对象参数化，如建筑高度、屋顶类型、道路宽度等
  * 智能编辑：道路地块联动编辑

* 与 ArcGIS 深入集成

  * 支持 ArcGIS 投影
  * 支持 Multipatch 模型和属性的编辑，并更新到File Geodatabase
  * 发布 3D Web Scene 到 ArcGIS online
  
**建模与设计流程**

1. GIS 数据准备（Shape/FileGDB）
2. 创建场景，导入 GIS 数据，将二维数据转化为三维数据
3. 规则建模，创建建筑/道路/绿化
4. 规则设计，调整布局/模型风格细化
5. 成果共享，导出模型/发布 3D web scene

![](https://github.com/Twanjun/Earth/blob/master/pics/2018122701.png)
