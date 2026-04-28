# 海洋科学数据与工具资源中心

本页面汇总了全球主流的海洋科学数据获取门户、在线分析工具及常用编程资源。

## 1. 全球实时观测数据 (Observational Data)

| 平台名称 | 核心内容 | 访问链接 |
| :--- | :--- | :--- |
| **Argo Floats** | 全球 3000+ 浮标提供的海水温盐剖面数据 | [访问 Argo](http://www.argo.ucsd.edu/) |
| **NOAA NCEI** | 美国国家海洋局，涵盖气象、物理、化学全维度数据 | [访问 NOAA](https://www.ncei.noaa.gov/) |
| **Copernicus Marine** | 欧洲哥白尼计划，提供高精度卫星遥感与再分析数据 | [访问 CMEMS](https://marine.copernicus.eu/) |
| **Ocean Observatories (OOI)** | 实时海底电缆观测阵列数据 | [访问 OOI](https://oceanobservatories.org/) |

## 2. 物理与动力学模拟 (Modeling & Reanalysis)

* **HYCOM (Hybrid Coordinate Ocean Model)**：全球高分辨率海洋环流模拟数据，常用于边界条件设置。
    * [链接：HYCOM Data Server](https://www.hycom.org/dataserver)
* **ECMWF / ERA5**：全球最权威的气象再分析数据，用于获取海表风场、气压等驱动力。
    * [链接：Copernicus Climate Data Store](https://cds.climate.copernicus.eu/)
* **GEBCO**：全球海底地形图，提供 15 弧秒分辨率的地形格点数据。
    * [链接：GEBCO Portal](https://www.gebco.net/)

## 3. 海洋化学与生物数据

* **WOD (World Ocean Database)**：全球最大的经质量控制的海洋剖面资料库。
    * [链接：WOD Search](https://www.ncei.noaa.gov/products/world-ocean-database)
* **GLODAP**：全球海洋数据分析项目，专注于碳循环和营养盐数据。
    * [链接：GLODAP Dashboard](https://www.glodap.info/)
* **OBIS**：海洋生物地理信息系统。
    * [链接：OBIS.org](https://obis.org/)

## 4. 推荐学习与开发工具

### 编程库 (Python/MATLAB)
* **xarray (Python)**：处理 NetCDF (nc) 格式数据的利器，海洋学必备。
* **Cartopy (Python)**：绘制高质量地图和投影。
* **Gibbs SeaWater (GSW)**：根据 TEOS-10 标准计算海水热力学性质的库。
* **M_Map (MATLAB)**：经典的海洋学绘图工具包。

### 在线计算器
* **SeaWater Equation of State**：在线计算海水密度、声速。
* **Tide Predictor**：全球主要港口的潮汐预报查询。
