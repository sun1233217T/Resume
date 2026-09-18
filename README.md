# 孙浩辰（Haochen Sun）· 个人简历

> 山东大学 · 三维点云语义分割 / 弱监督学习 / 3D 高斯泼溅与三维重建
>
> 📍 青岛 | 📞 15634103257 | 📧 1710582287@qq.com | 💻 [GitHub](https://github.com/sun1233217T) | 🎓 [ORCID](https://orcid.org/0009-0004-3777-8729)

---

## 👤 个人简介

山东大学计算机科学与技术学院博士研究生（预计 2027 年 6 月毕业），本科毕业于山东大学泰山学堂（化学取向，教育部拔尖计划基地），兼具科学计算与三维视觉交叉背景。研究方向为三维点云语义分割、弱监督学习与 3D 高斯泼溅（3D Gaussian Splatting）。在 TVCG、TPAMI、TMM 等国际期刊发表学术论文 5 篇，其中以第一作者 / 学生一作发表 3 篇（含 TVCG 已录用 1 篇），另有 2 篇共同一作论文在投（TVCG、NeurIPS）；获授权 / 受理国家发明专利 2 项、软件著作权 1 项。

## 🎓 教育经历

**山东大学 · 计算机科学与技术学院（博士）** — 2022.09 – 2027.06（预计毕业）

- 导师：辛士庆
- 研究方向：点云语义分割、弱监督学习、3D 高斯泼溅与三维重建

**山东大学 · 泰山学堂（化学取向，本科）** — 2018.09 – 2022.06

- 教育部「基础学科拔尖学生培养试验计划」基地
- 导师：徐政虎

## 📄 学术论文

1. **ECGS: Extinction Coordination for Enhanced Gaussian Splatting**（第一作者 · 已录用 · 出版中）
   **Haochen Sun**, Rui Xu, Zhiyang Dou, Tianyang Xue, Changhe Tu, Taku Komura, Lin Lu, Shiqing Xin
   *IEEE Transactions on Visualization and Computer Graphics (TVCG)* · 中科院一区 Top
   代码开源：[github.com/sun1233217T/ECGS](https://github.com/sun1233217T/ECGS.git)

2. **DEM-GS: Towards Relightable 3D Gaussian Splatting with Distilled Environment & Material**（共同一作 · 在投）
   Zichang Wang†, **Haochen Sun**†, Qiong Zeng, Shiqing Xin, Shuangming Chen, Changhe Tu, Wenping Wang（† 共同第一作者）
   *IEEE Transactions on Visualization and Computer Graphics (TVCG)*

3. **3D Fresnel Volumizing for Efficient Implicit Velocity Field Reconstruction**（共同一作 · 在投）
   Sihan Chen†, **Haochen Sun**†, Peng Jiang, Anthony G. Cohn（† 共同第一作者）
   *Conference on Neural Information Processing Systems (NeurIPS)*

4. **Improving Back-Projection Accuracy for the Semantic Segmentation of Indoor Point Clouds With Fewer & Sparse Image Annotations**（学生一作）
   Peng Jiang, **Haochen Sun**, Zhiyi Pan, Jinming Cao, Roger Zimmermann, Changhe Tu
   *IEEE Transactions on Multimedia (TMM)*, 2025 · 中科院一区 Top
   DOI: [10.1109/TMM.2025.3599085](https://doi.org/10.1109/TMM.2025.3599085)

5. **CC4S: Encouraging Certainty and Consistency in Scribble-Supervised Semantic Segmentation**
   Zhiyi Pan, **Haochen Sun**, Peng Jiang, Ge Li, Changhe Tu, Haibin Ling
   *IEEE Transactions on Pattern Analysis and Machine Intelligence (TPAMI)*, 2024.12 · 中科院一区 Top
   DOI: [10.1109/TPAMI.2024.3415387](https://doi.org/10.1109/TPAMI.2024.3415387)

6. **Leverage Automatic Differentiation Routines for Seismic Traveltime Tomography in Tunnels**（第一作者 · 专著章节）
   **Haochen Sun**, Shiyang Wei, Shuai Cao, Peng Jiang
   Springer, 2025 · DOI: [10.1007/978-981-96-9805-9_26](https://doi.org/10.1007/978-981-96-9805-9_26)

7. **Calculating Rock Joint Frequency in TBM Excavation Through Binocular Vision and Segmentation Techniques**
   Jingwei Xu, **Haochen Sun**, Hongmei Wang, Yaxu Wang, Yan Zhu, Peng Jiang, Yi Shan
   *Advances in Civil Engineering*, 2025.01
   DOI: [10.1155/adce/4515005](https://doi.org/10.1155/adce/4515005)

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

### 面向 3D 高斯泼溅 / 神经辐射场的几何重建与表征优化
*对应 TVCG 已录用（第一作者，代码开源）· TVCG 在投（共同一作）*

- 提出消光协调器（Extinction Coordinator），约束高斯基元的本征不透明度与其跨视角最大 alpha 混合权重一致，解决 3DGS 参数化非唯一 / 异质的问题，使基元沿薄壳状表面分布，显著提升表示能力（ECGS）
- 设计各向异性形态正则化，促进平面状高斯、抑制针状伪影；在多个基准上高斯数量最多减少 75%，同时提升几何精度与渲染速度；轻量模块化设计，可无缝集成进现有 Gaussian Splatting 管线，代码已开源
- 提出 DEM-GS：针对球谐（SH）外观将高光、漫反射与自发光混合、导致模型难以编辑与重光照的问题，将光照的神经表示与基于高斯的材质属性分离学习；通过纹理聚类从多视图图像中提取真实物体材质、表面纹理与环境光照，基于 Phong 模型实现任意光照下物理合理的高保真重光照
- 技术栈：Python / PyTorch / CUDA 可微光栅化管线 / 3D Gaussian Splatting / NeRF

### 涂鸦监督的三维 / 二维语义分割框架与点云标注工具
*对应 TPAMI 2024 · TMM 2025 · 专利 CN117058384B · 软著 2025SR1884614*

- 提出同时约束「确定性」与「一致性」的涂鸦监督分割框架 CC4S，仅用稀疏涂鸦标注即可达到接近全监督的分割精度
- 针对室内点云提出反投影精度优化方法，将少量二维图像标注高精度传播到三维点云，显著降低标注成本
- 基于该框架设计并实现点云标注软件：将三维点云投影至二维视图进行高效标注，再反投影回三维空间，大幅提升标注效率
- 技术栈：Python / PyTorch / Open3D / 深度学习 / 计算机视觉

### AI for Science：智能计算方法在隧道工程中的应用
*对应专著章节（一作）· Adv. Civ. Eng. 2025 · 专利 CN119758448A · NeurIPS 在投（共同一作）*

- 提出 3D Fresnel Volumizing 框架：以坐标神经网络将速度场隐式参数化为连续函数，并提出可微菲涅尔体化方法将 1D 射线路径扩展为 3D 体区域，结合多级并行正演实现高效三维速度场重建；计算时间较 FWI 方法最多降低 10 倍，重建质量 SSIM 最高 0.96、PSNR 最高 26 dB
- 将自动微分引入隧道地震波走时层析成像，避免手工推导梯度；反演误差（MAE）较传统方法降低 50%–83%，单次反演由 16–23 小时缩短至 2–3 分钟，实测数据仅需 96 组走时观测即可准确拟合界面位置
- 结合双目立体视觉与图像分割技术，实现 TBM 掘进过程中岩体节理频率的自动化测量；在 30 组 TBM 隧道实测数据上识别准确率达 79%（IoU 0.65），在渗水、遮挡等复杂工况下仍保持鲁棒
- 技术栈：Python / PyTorch / 自动微分 / 隐式神经表示 / 双目立体视觉 / 图像分割

## 🛠 技能

| 类别 | 内容 |
| --- | --- |
| 语言 | Python、C/C++、CUDA |
| 深度学习 | PyTorch、图像/点云神经网络（SAM、DINO、PointNet++ 等） |
| 三维视觉 | 3D Gaussian Splatting、NeRF、三维重建、可重光照渲染、逆向渲染、Open3D、点云处理、双目立体视觉、相机标定 |
| 渲染管线 | CUDA 可微光栅化管线（3DGS 光栅化与 alpha 混合）、可微渲染 |
| 图像 | OpenCV、语义分割、弱监督学习 |
| 科学计算 | 自动微分、地震层析成像、隐式神经表示 |
| 工具 | Git、Linux、LaTeX |

## 🏆 荣誉与奖项

- **GDC 2025 面向建筑场景的高精度三维重建挑战赛** · 三等奖
- **2025 华为软件精英挑战赛** · 校内赛二等奖（山东大学）
- **2025 华为软件精英挑战赛** · 江山赛区二等奖
- **2024 华为软件精英挑战赛** · 江山赛区二等奖
- **ChinaGraph 2024「先临精鹰杯」高精度三维重建大赛** · 三等奖
- **山东大学** · 学业奖学金：2025 博士研究生一等 / 2024 博士新生二等 / 2022–2023 三等
- **山东大学** · 优秀研究生（2023、2025 年度）

---

*本简历使用 Markdown 编写，网页版见 [resume.sunnytom.cc](https://github.com/sun1233217T/Resume)*
