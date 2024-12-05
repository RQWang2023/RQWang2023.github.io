## 薄壁件高速铣削数据集（HMoTP）

### 说明

所公开的薄壁件高速铣削（High-speed milling of thin-walled parts, HMoTP）数据集包含钛合金薄壁件高速铣削力信号、工件振动信号以及刀具磨损数据，可用于开展航空类难加工材料切削刀具磨损监测、加工颤振检测研究。如果该数据集对您的研究有用，请引用论文：Wang R, Song Q, Peng Y, et al. Toward digital twins for high-performance manufacturing: Tool wear monitoring in high-speed milling of thin-walled parts using domain knowledge, Robot Comput-Integr Manuf 2024;88:102723 <https://doi.org/10.1016/j.rcim.2024.102723>

### 数据集构成

数据集中的每组加工数据都存储为独立的 CSV 文件。三把加工刀具的切削数据分别存储在名为 CuttingsignalsT01/CuttingsignalsT02/CuttingsignalsT03 的文件夹中。

每把刀具有 100 组切削数据。以 T1 刀具为例，其切削数据保存在 100 个 CSV 文件中，文件名分别为 T01_001.CSV 至 T01_100.CSV。每个切削数据 CSV 文件包含 7 个通道的数据： Fx、Fy、Fz、Mz、Ax、Ay 和 Az。每个切削数据对应一个刀具磨损值，所有测量得到的刀具磨损值都保存在名为 ToolWeaT01.csv/ToolWeaT02.csv/ToolWeaT03.csv 的文件中。

详细的实验设计、采样频率与工艺参数请参考论文第 2.3 节和附录 1。

### 数据集下载地址

1.  百度云盘：[HMoTP 2024](https://pan.baidu.com/s/1PFtNowJL_QUmHMtoHvRHJA)   提取码：sdum

2.  谷歌云盘：[HMoTP 2024 - Google 云端硬盘](https://drive.google.com/drive/folders/1eBhTSXMd8jVITfQoJifC50fE_NIFqb89?usp=sharing)

### GitHub 项目地址

[GitHub - dataforresearch/HMoTP: Thin-walled parts 2024 dataset released from Shandong University](https://github.com/dataforresearch/HMoTP)

##
