# 孙浩辰（Haochen Sun）· 个人简历

> 山东大学 · 三维点云语义分割 / 弱监督学习 / 3D 高斯泼溅与三维重建
>
> 📍 济南 | 📧 you@example.com | 💻 [GitHub](https://github.com/yourname) | 🎓 [ORCID](https://orcid.org/0009-0004-3777-8729)

---

## 👤 个人简介

山东大学计算机科学与技术学院研究生，本科毕业于山东大学泰山学堂（化学取向）。研究方向为三维点云语义分割、弱监督学习与 3D 高斯泼溅（3D Gaussian Splatting）。以第一作者 / 学生一作在 TPAMI、TMM 等国际期刊发表学术论文 4 篇，另有 1 篇第一作者论文在投；获授权 / 受理国家发明专利 2 项、软件著作权 1 项。

## 🎓 教育经历

**山东大学 · 计算机科学与技术学院（博士）** — 2022.09 – 至今

- 导师：辛士庆
- 研究方向：点云语义分割、弱监督学习、3D 高斯泼溅与三维重建

**山东大学 · 泰山学堂（化学取向，本科）** — 2018.09 – 2022.06

- 教育部「基础学科拔尖学生培养试验计划」基地
- 导师：徐政虎

## 📄 学术论文

1. **CC4S: Encouraging Certainty and Consistency in Scribble-Supervised Semantic Segmentation**
   Zhiyi Pan, **Haochen Sun**, Peng Jiang, Ge Li, Changhe Tu, Haibin Ling
   *IEEE Transactions on Pattern Analysis and Machine Intelligence (TPAMI)*, 2024.12
   DOI: [10.1109/TPAMI.2024.3415387](https://doi.org/10.1109/TPAMI.2024.3415387)

2. **Improving Back-Projection Accuracy for the Semantic Segmentation of Indoor Point Clouds With Fewer & Sparse Image Annotations**
   Peng Jiang, **Haochen Sun**, Zhiyi Pan, Jinming Cao, Roger Zimmermann, Changhe Tu
   *IEEE Transactions on Multimedia (TMM)*, 2025
   DOI: [10.1109/TMM.2025.3599085](https://doi.org/10.1109/TMM.2025.3599085)

3. **Calculating Rock Joint Frequency in TBM Excavation Through Binocular Vision and Segmentation Techniques**
   Jingwei Xu, **Haochen Sun**, Hongmei Wang, Yaxu Wang, Yan Zhu, Peng Jiang, Yi Shan
   *Advances in Civil Engineering*, 2025.01
   DOI: [10.1155/adce/4515005](https://doi.org/10.1155/adce/4515005)

4. **Leverage Automatic Differentiation Routines for Seismic Traveltime Tomography in Tunnels**（专著章节 · 第一作者）
   **Haochen Sun**, Shiyang Wei, Shuai Cao, Peng Jiang
   2025 · DOI: [10.1007/978-981-96-9805-9_26](https://doi.org/10.1007/978-981-96-9805-9_26)

5. **ECGS: Extinction Coordination for Enhanced Gaussian Splatting**（第一作者 · 已接受）
   **Haochen Sun**, Rui Xu, Zhiyang Dou, Tianyang Xue, Changhe Tu, Taku Komura, Lin Lu, Shiqing Xin
   *IEEE Transactions on Visualization and Computer Graphics (TVCG)*

## 💡 发明专利

1. **一种三维点云语义分割的方法及系统**（发明专利 · 已授权，有效）
   蒋鹏、**孙浩辰**、曾琼、屠长河
   公告号 CN117058384B · 公告日 2024.02.09 · 申请人：山东大学

2. **一种隧道地震波走时层析成像方法及系统**（发明专利 · 实质审查中）
   蒋鹏、**孙浩辰**、齐圣杰、王琨、杨森林
   公开号 CN119758448A · 公开日 2025.04.04 · 申请人：山东大学

## ©️ 软件著作权

- **基于二维投影的三维点云场景标注软件** · 登记号 2025SR1884614 · 山东大学 · 2025

## 🚀 项目 / 科研经历

<!-- > 以下描述为根据成果推断的占位版本，请按实际情况修改。 -->

### ECGS：面向 3D 高斯泼溅的消光协调优化
*对应在投论文（第一作者）*

- 提出消光协调器（Extinction Coordinator），约束高斯基元的本征不透明度与其跨视角最大 alpha 混合权重一致，使基元沿薄壳状表面分布，显著提升表示能力
- 设计各向异性形态正则化，促进平面状高斯、抑制针状伪影；在多个基准上高斯数量最多减少 75%，同时提升几何精度与渲染速度
- 轻量模块化设计，可无缝集成进现有 Gaussian Splatting 管线

### CC4S：涂鸦监督的三维 / 二维语义分割框架
*对应 TPAMI 2024、TMM 2025 论文及发明专利 CN117058384B*

- 提出同时约束「确定性」与「一致性」的涂鸦监督分割框架 CC4S，仅用稀疏涂鸦标注即可达到接近全监督的分割精度
- 针对室内点云提出反投影精度优化方法，将少量二维图像标注高精度地传播到三维点云，显著降低标注成本
- 技术栈：Python / PyTorch / Open3D / 点云深度学习

### 基于二维投影的三维点云场景标注软件
*对应软件著作权 2025SR1884614*

- 设计并实现点云标注工具：将三维点云投影至二维视图进行高效标注，再反投影回三维空间，大幅提升标注效率
- 待补充：使用人数 / 标注效率提升等量化数据

### 隧道地震波走时层析成像方法
*对应专著章节（第一作者）及发明专利 CN119758448A*

- 将自动微分（Automatic Differentiation）引入隧道地震波走时层析成像，避免手工推导梯度，提高反演效率与精度
- 待补充：实验规模、精度提升等量化数据

### 基于双目视觉与分割技术的 TBM 岩体节理频率计算
*对应 Advances in Civil Engineering 2025 论文*

- 结合双目立体视觉与图像分割技术，实现 TBM 掘进过程中岩体节理频率的自动化测量，替代低效的人工统计
- 待补充：测量误差、部署场景等量化数据

## 🛠 技能

| 类别 | 内容 |
| --- | --- |
| 语言 | Python、C/C++ |
| 深度学习 | PyTorch、点云网络（PointNet++ / Point Transformer 等） |
| 三维视觉 | 3D Gaussian Splatting、三维重建、Open3D、点云处理、双目立体视觉、相机标定 |
| 图像 | OpenCV、语义分割、弱监督学习 |
| 科学计算 | 自动微分、地震层析成像 |
| 工具 | Git、Linux、LaTeX |

## 🏆 荣誉与奖项

- 待补充：奖学金 / 竞赛 / 荣誉称号等

---

*本简历使用 Markdown 编写，网页版见 [yourname.github.io/resume](https://yourname.github.io/resume)*
