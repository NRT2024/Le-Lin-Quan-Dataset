乐林泉数据集
简介 (Introduction)
乐林泉数据集 (Le Lin Quan Dataset) 是一个专注于中国古典园林和风景园林图像识别与分析的大规模、高质量数据集。该数据集旨在为计算机视觉、文化遗产数字化、园林艺术研究等领域提供一个标准化的图像资源库，特别是针对中国园林独特的地域文化特征和建筑风格进行细致的分类和标注。

本数据集的分类体系基于 YAIG (Yuanlin AI Group) 的研究成果，将中国园林划分为多个一级和二级类别，以支持细粒度的图像识别任务。

数据集概览 (Dataset Overview)
特性 (Feature)	描述 (Description)
数据集名称	乐林泉数据集 (Le Lin Quan Dataset) V1.0
主要内容	中国古典园林和风景园林的图像集合
数据格式	JPEG/JPG 图像文件
数据总量	15,463 张图像
核心价值	专注于中国园林地域文化与风格的细粒度分类
适用领域	计算机视觉、图像识别、文化遗产数字化、园林艺术研究
核心分类体系 (Core Classification System)
乐林泉数据集采用的分类体系是其核心特色，它将园林图像划分为七大一级分类，并进一步细化到具体的园林案例（二级案例）。这种结构有助于模型学习和区分中国园林在不同地域和文化背景下形成的独特风格。

以下为数据集的主要一级分类及其文化与地域特征：

一级分类 (Primary Category)	代表案例 (Representative Cases)	文化与地域特征 (Cultural and Regional Characteristics)
北方私家园林	北京醇王府园、北京恭王府园等	空间宽敞直爽，色彩厚重，手法简洁，气质端庄大度。
江南私家园林	苏州拙政园、苏州留园、扬州个园等	空间曲折幽深，色彩素雅，手法精致，气质灵秀婉约。
岭南私家园林	番禺余荫山房、顺德清晖园等	建筑繁密有序，色彩鲜丽明快，商贸文化基因与中西美学交融。
皇家园林	颐和园、避暑山庄、圆明园（遗址）等	规模宏大，繁复富丽，将天下胜景微缩再现，体现帝王气魄。
汉地佛寺园林	北京潭柘寺、杭州灵隐寺等	拥有朝拜空间、造型独特的宗教建筑，反映宗教思想。
藏地佛寺园林	西藏拉萨罗布卡林、青海塔尔寺等	空间依山就势，色彩浓烈纯粹，手法粗犷厚重，气质神圣崇高。
公共风景区园林	杭州西湖、北京什刹海、嘉兴南湖等	利用优美山川条件营造，点缀适当建筑物，融合人文历史与大众游憩需求。

数据集结构 (Dataset Structure)
数据集的目录结构清晰，采用一级分类/二级案例/图像文件的命名方式，方便用户进行分类任务的训练和测试。

乐林泉数据集V1.0/
├── beifangsijiayuanlin/             # 北方私家园林
│   ├── beijingchunwangfuyuan/
│   ├── beijinggongwangfuyuan/
│   └── ...
├── gonggongfengjingquyuanlin/       # 公共风景区园林
│   ├── hangzhouxiu/
│   ├── jiaxingnanhu“jiahebajing”/
│   └── ...
├── huangjiayuanlin/                 # 皇家园林
│   ├── beihai/
│   ├── yiheyuan/
│   └── ...
├── jiangnansijiayuanlin/            # 江南私家园林
│   ├── suzhouzhuozhengyuan/
│   ├── yangzhougeyuan/
│   └── ...
├── lingnansijiayuanlin/             # 岭南私家园林
├── hanchansiyuanlin/                # 汉地佛寺园林
└── zangchansiyuanlin/               # 藏地佛寺园林

使用场景 (Use Cases)
1	细粒度图像识别 (Fine-Grained Image Recognition): 训练模型以区分不同地域和文化背景下的园林风格，例如区分“北方私家园林”和“江南私家园林”。
2	文化遗产数字化 (Digitalization of Cultural Heritage): 为园林建筑、景观元素的自动化识别和归档提供基础数据。
3	风格迁移与生成 (Style Transfer and Generation): 研究和学习不同园林风格的视觉特征，用于艺术创作或虚拟场景生成。
4	教育与科普 (Education and Popular Science): 作为园林艺术和建筑历史教学的视觉素材库。

引用 (Citation)
如果您在研究中使用了本数据集，请引用以下信息（请根据实际发布情况补充完整的引用格式）：

@misc{lelinquan_dataset_v1,
  author = {Yuanlin AI Group (YAIG)},
  title = {乐林泉数据集 (Le Lin Quan Dataset) V1.0: 中国古典园林图像资源库},
  year = {2025},
  publisher = {GitHub Repository},
  url = {https://github.com/YourOrganization/LeLinQuan-Dataset}
}

贡献与致谢 (Contribution and Acknowledgements)
本数据集由东话优选团队、清华建筑学院等共同组织发起收集、整理与标注。我们感谢所有参与数据采集、整理和审核的成员，以及为中国园林文化研究做出贡献的学者和机构。

欢迎社区成员通过提交 Issue 或 Pull Request 来报告数据错误或提出改进建议。
