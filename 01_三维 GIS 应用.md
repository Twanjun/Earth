Esri 开发大赛三维 GIS 应用的技术设计路线：三维建模 - 创建 WebScene - 应用制定

**1.三维数据源：**

三维数据生产可以通过以下几种方式生产：

* 传统建模：使用 CityEngine 基于二维矢量数据快速批量建模或使用第三方建模软件如 2ds Max、SketchUP等构建的三维模型
* 倾斜摄影测量建模：使用无人机获取建模区影响，通过 Drone2Map for ArcGIS 或第三方倾斜摄影建模软件如 Smart 3D 等生成倾斜摄影测量建模成果
* BIM 模型：使用第三方 BIM 建模软件如 Revit、Bentley 等构建的 BIM 模型

**2.WebScene的创建：**

可通过Esri提供的ArcGIS桌面软件（ArcGIS Pro/Desktop）发布自己生产的三维数据以及可能使用到的影像、地形、二维要素等数据到Portal上，并在Portal上构建三维场景（Web Scene）

**3.应用定制：**

可使用Esri的产品结合开源的产品定制桌面、Web或移动端的应用程序。选可以使用以下几种方式但可不局限于这些方式定制自己的三维应用：
* Web类应用： JS API 4.X+开源JS
* 移动或桌面类应用： ArcGIS Runtime SDKs
