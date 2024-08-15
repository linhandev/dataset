This repo is forked from [https://github.com/linhandev/dataset](https://github.com/linhandev/dataset). It has not been updated for two years. Here I add some more datasets.
# Public Medical imaging dataset collection
# Preface

Medical imaging datasets are numerous and professional, and everyone can contribute! If you have used a dataset that is not on the list or found any omissions in the list, we very much hope that you can contribute to the project.

# Table of Content
* [Abdomen](#abdomen)
   * [BTCV](BTCV)
* [Liver](#liver)
   * [LiTS](#lits)
   * [Sliver07](#sliver07)
   * [3D-IRCADB](#3d-ircadb)
   * [CHAOS](#chaos)
   * [TCGA-LIHC](#tcga-lihc)
   * [MSD肝脏血管分割](#msd肝脏血管分割)
* [肺](#肺)
   * [MSD肺癌分割](#msd肺癌分割)
   * [LoLa11肺叶分割](#lola11肺叶分割)
   * [StructSeg2019](#structseg2019)
   * [肺部多病智能诊断](#肺部多病智能诊断)
   * [CheXpert](#chexpert)
   * [NIHChest Xray](#nihchest-xray)
   * [QIN Lung CT](#qin-lung-ct)
   * [4D-Lung](#4d-lung)
   * [NSCLC-Radiomics](#nsclc-radiomics)
   * [vessel12 肺部血管分割](#vessel12-肺部血管分割)
   * [肺结核](#肺结核)
      * [Shenzhen Hospital X-ray Set](#shenzhen-hospital-x-ray-set)
      * [Montgomery County X-ray Set](#montgomery-county-x-ray-set)
   * [肺炎](#肺炎)
      * [Ieee8023](#ieee8023)
      * [covid19-ct-scans](#covid19-ct-scans)
      * [COVID-CT](#covid-ct)
      * [Figure1-COVID-chestxray-dataset](#figure1-covid-chestxray-dataset)
      * [RSNA肺炎检测](#rsna肺炎检测)
      * [CovidX](#covidx)
      * [Flyai Covid](#flyai-covid)
      * [covid19-radiography-database](#covid19-radiography-database)
      * [COVID-19-AR](#covid-19-ar)
      * [CT Images in COVID-19](#ct-images-in-covid-19)
   * [肺结节](#肺结节)
      * [LIDC-IDRI](#lidc-idri)
      * [LUNA16](#luna16)
      * [天池肺部结节](#天池肺部结节)
      * [LNDB](#lndb)
      * [Lung Nodule Malignancy](#lung-nodule-malignancy)
      * [Data Science Bowl 17](#data-science-bowl-17)
      * [Lung-PET-CT-Dx](#lung-pet-ct-dx)
   * [气胸](#气胸)
      * [SIIM-ACR Pneumothorax Segmentation](#siim-acr-pneumothorax-segmentation)
* [胸](#胸)
   * [CBIS-DDSM](#cbis-ddsm)
   * [QIN Breast](#qin-breast)
   * [Rider Breast MRI](#rider-breast-mri)
   * [ACRIN 6688](#acrin-6688)
   * [BraTS2013](#brats2013)
   * [BraTS2015](#brats2015)
   * [BraTS2021](#brats2021)
* [脑](#脑)
   * [MSD脑瘤分割](#msd脑瘤分割)
   * [MSD海马体分割](#msd海马体分割)
   * [Iseg2019](#iseg2019)
   * [ABIDE](#abide)
   * [ADNI](#adni)
   * [CQ500](#cq500)
   * [脑出血](#脑出血)
      * [RSNA Intracranial Hemorrhage Detection](#rsna-intracranial-hemorrhage-detection)
* [肾脏](#肾脏)
   * [Kits19](#kits19)
* [肠](#肠)
   * [CT COLONOGRAPHY](#ct-colonography)
   * [MSD肠道分割数据集](#msd肠道分割数据集)
* [心脏](#心脏)
   * [EchoNet](#echonet)
   * [MMWHS](#mmwhs)
   * [MSD心脏分割](#msd心脏分割)
   * [主动脉](#主动脉)
      * [冠状动脉分割](#冠状动脉分割)
* [眼睛](#眼睛)
   * [DRIVE](#drive)
   * [ODIR-5k](#odir-5k)
   * [FIRE 视网膜图像数据](#fire-视网膜图像数据)
   * [STARE](#stare)
   * [CHASE_DB1](#chase_db1)
   * [IDRiD](#idrid)
* [前列腺](#前列腺)
   * [PANDA](#panda)
   * [MSD前列腺分割](#msd前列腺分割)
   * [QIN-PROSTATE-Repeatability](#qin-prostate-repeatability)
* [胰腺](#胰腺)
   * [MSD胰腺分割](#msd胰腺分割)
   * [PDMR-833975-119-R](#pdmr-833975-119-r)
* [皮肤](#皮肤)
   * [SIIM-ISIC Melanoma Classification](#siim-isic-melanoma-classification)
* [镜检](#镜检)
   * [细胞](#细胞)
      * [Data Science Bowl 18](#data-science-bowl-18)
      * [血细胞涂片分类](#血细胞涂片分类)
      * [ISBI细胞跟踪](#isbi细胞跟踪)
   * [穿刺](#穿刺)
      * [BCNB乳腺癌穿刺活检](#bcnb乳腺癌穿刺活检)
* [骨骼](#骨骼)
   * [MURA-1.1](#mura-11)
   * [RSNA Bone Age](#rsna-bone-age)
   * [磁共振图像脊柱结构多类别三维自动分割](#磁共振图像脊柱结构多类别三维自动分割)
   * [膝盖](#膝盖)
      * [MRNet](#mrnet)
   * [脊椎](#脊椎)
      * [Verse大规模脊椎分割数据集](#verse大规模脊椎分割数据集)
* [VQA](#vqa)
   * [PathVQA](#pathvqa)
* [内窥镜](#内窥镜)
   * [SARAS-MESAD](#saras-mesad)
   * [SARAS-MESAD](#saras-mesad-1)
* [数字病理](#数字病理)
   * [CAMELYON](#camelyon)
* [心电图](#心电图)
   * [CAMELYON](#camelyon-1)
* [Ultrasound](#ultrasound-imaging)
   * [HC18 Fetal head](#fetal-head)
* [医学影像数据库](#医学影像数据库)
* [参考项目/列表](#参考项目列表)


# Abdomen

## BTCV
todo

# Liver

## LiTS
[//]: # (FIN)

| 名称 | 标注内容 | 类型 | 模态 | 数量 | 标签格式 | 文件格式 | License |
| - | - | - | - | - | - | - | - |
| [LiTS](https://competitions.codalab.org/competitions/17094) | 肝脏/肝脏肿瘤 | 分割 | CT   | 131+70 | 0/1标签  | nii | [CC BY-NC-ND 4.0](https://competitions.codalab.org/competitions/17094#learn_the_details-terms_and_conditions) |

<img src="https://raw.githubusercontent.com/linhandev/dataset/main/static/lits.jpg" width="50%"/>

LiTS数据集包含131组训练扫描和70组测试扫描，其中70组测试数据标签不公开。LiTS训练集中包含[3DIRCADB](#3d-ircadb)中的所有数据，所以不要合并这两个数据集。Medical Segmentation Decathlon中肝脏分割的数据集就是LiTS。

分割结果可以在线提交进行评估，[在线提交方法参考](https://github.com/PatrickChrist/LITS-CHALLENGE)。 [在线提交地址](https://competitions.codalab.org/competitions/17094)

数据集论文：[The Liver Tumor Segmentation Benchmark (LiTS)](https://arxiv.org/abs/1901.04056)

相关项目： [基于Paddle的肝脏CT影像分割](https://aistudio.baidu.com/aistudio/projectdetail/250994)

[Aistudio下载](https://aistudio.baidu.com/aistudio/datasetdetail/10273)

## Sliver07
[//]: # (FIN)

| 名称 | 标注内容 | 类型 | 模态 | 数量  | 标签格式 | 文件格式  | License |
| - | - | - | - | - | - | - | - |
| [Sliver07](https://sliver07.grand-challenge.org/) | 肝脏     | 分割 | CT   | 20+10 | 0/1标签  | MetaImage | [Other](https://zenodo.org/record/2597908) |

<img src="https://i.loli.net/2020/11/21/iuOqFTteKUlnNVZ.png" width="50%"/>


这个数据集比较老了，现在用的也比较少，一些研究会将sliver和lits合起来，这样基本上就是所有常用的关于肝脏分割的公开数据了。mhd格式可以用 SimpleITK 读，在medseg项目中有[转换成nii的脚本](https://github.com/linhandev/medSeg/blob/main/tool/train/mhd2nii.py)

[Aistudio下载](https://aistudio.baidu.com/aistudio/datasetdetail/19906)

## 3D-IRCADB
[//]: # (FIN)

| 名称 | 标注内容 | 类型 | 模态 | 数量 | 标签格式 | 文件格式 | License |
| - | - | - | - | - | - | - | - |
| 3D-IRCADb [01](https://www.ircad.fr/research/data-sets/liver-segmentation-3d-ircadb-01/) [02](https://www.ircad.fr/research/data-sets/respiratory-cycle-3d-ircadb-02/) | 肝脏/肝肿瘤 | 分割 | CT   | 20+2 | surface mesh | dcm | CC |

<img src="https://raw.githubusercontent.com/linhandev/dataset/main/static/3Dircadb.jpg" width="80%"/>


3D-IRCADb是比较早的一个数据集，有两个子集，分别包含20组和2组CT片子。

[Aistudio下载](https://aistudio.baidu.com/aistudio/datasetdetail/10293)

## CHAOS
[//]: # (FIN)

| 名称 | 标注内容 | 类型 | 模态 | 数量 | 标签格式 | 文件格式 | License |
| - | - | - | - | - | - | - | - |
| [CHAOS](https://chaos.grand-challenge.org/) | 肝/肾/脾 | 分割 | CT+MRI | 40CT+120MRI | 0/1标签  | dcm | [CC 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/legalcode) |

CHAOS是一个多脏器，多模态分割数据集。

![CHAOS](https://raw.githubusercontent.com/linhandev/dataset/main/static/chaos.png)

[Aistudio下载](https://aistudio.baidu.com/aistudio/datasetdetail/23864)

## TCGA-LIHC
[//]: # (FIN)

| 名称 | 标注内容 | 类型 | 模态 | 数量 | 标签格式 | 文件格式 | License |
| - | - | - | - | - | - | - | - |
| [TCGA-LIHC](https://wiki.cancerimagingarchive.net/display/Public/TCGA-LIHC) | 肝 |  | CT/MR/PT | 97患者/237套 | 无标签   | dcm | [Other](https://wiki.cancerimagingarchive.net/display/Public/Data+Usage+Policies+and+Restrictions) |

![tcga-lihc](https://raw.githubusercontent.com/linhandev/dataset/main/static/tcga-lihc.jpg)

[Aistudio下载](https://aistudio.baidu.com/aistudio/datasetdetail/37439)

## MSD肝脏血管分割

| 名称 | 标注内容 | 类型 | 模态 | 数量 | 标签格式 | 文件格式 | License |
| - | - | - | - | - | - | - | - |
| [MSD肝脏血管分割](http://medicaldecathlon.com/) | 肝脏血管 | 分割 | CT | 443 | 0/1 | nii | [CC-BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/) |

![hepatic-Vessels](https://raw.githubusercontent.com/linhandev/dataset/main/static/Hepatic-Vessels.png)

[Aistudio下载](https://aistudio.baidu.com/aistudio/datasetdetail/10333)

# 肺
## MSD肺癌分割

| 名称 | 标注内容 | 类型 | 模态 | 数量 | 标签格式 | 文件格式  | License |
| - | - | - | - | - | - | - | - |
| [MSD肺癌分割](http://medicaldecathlon.com/) | 肺脏 | 分割 | CT | 96 | 0/1 | nii | [CC-BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/) |

![Lung-Tumours](https://raw.githubusercontent.com/linhandev/dataset/main/static/Lung-Tumours.png)

[Aistudio下载](https://aistudio.baidu.com/aistudio/datasetdetail/10334)

## LoLa11肺叶分割

[//]: # (FIN)

| 名称 | 标注内容    | 类型 | 模态 | 数量 | 标签格式 | 文件格式  | License |
| - | - | - | - | - | - | - | - |
| [LoLa11](https://lola11.grand-challenge.org/) | None | 分割 | CT   | 55 | None  | Metaimage | [Other](https://zenodo.org/record/4708800) |

![lola11](https://grand-challenge-public.s3.amazonaws.com/f/challenge/39/c4ab1b11-3338-4b99-a732-174ddc9e3b70/lola11_web.png)

LoLa11 包含55套CT数据，未发现任何公开标注信息

[zenodo下载](https://zenodo.org/record/4708800)

[//]: # (30417)

## StructSeg2019

| 名称 | 标注内容 | 类型 | 模态 | 数量 | 标签格式 | 文件格式 |
| - | - | - | - | - | - | - |
| [StructSeg2019](https://structseg2019.grand-challenge.org/) ||      |||||

![structseg2019](https://grand-challenge-public.s3.amazonaws.com/b/398/banner2_XdYKwmN.jpg)


## 肺部多病智能诊断

| 名称 | 标注内容 | 类型 | 模态 | 数量 | 标签格式 | 文件格式 |
| - | - | - | - | - | - | - |
| [肺部多病智能诊断](https://tianchi.aliyun.com/competition/entrance/231724/) |          |      | CT   |      |          |          |

[//]: # (34323)

## CheXpert

| 名称 | 标注内容 | 类型 | 模态 | 数量 | 标签格式 | 文件格式 | License |
| - | - | - | - | - | - | - | - |
| [CheXpert](https://stanfordmlgroup.github.io/competitions/chexpert/) |  |      |      |      |          |          | [Other](https://stanfordmlgroup.github.io/competitions/chexpert/) |

![chestxpert](https://raw.githubusercontent.com/linhandev/dataset/main/static/chest-x-pert.png)

介绍论文： [CheXpert: A Large Chest Radiograph Dataset with Uncertainty Labels and Expert Comparison](https://arxiv.org/abs/1901.07031)

[相关项目](https://github.com/gaetandi/cheXpert)

## NIHChest Xray

| 名称 | 标注内容 | 类型 | 模态 | 数量 | 标签格式 | 文件格式 | License |
| - | - | - | - | - | - | - | - |
| [NIHChest Xray](https://www.kaggle.com/nih-chest-xrays/data) | 14种肺部疾病/部分病灶位置 | 分类/检测 | CXR | 112,120 | csv | png | [CC0: Public Domain](https://creativecommons.org/publicdomain/zero/1.0/) |

![img](https://raw.githubusercontent.com/linhandev/dataset/main/static/nih-chest-xray.png)
介绍论文： [ChestX-ray8: Hospital-scale Chest X-ray Database and Benchmarks on Weakly-Supervised Classification and Localization of Common Thorax Diseases](http://openaccess.thecvf.com/content_cvpr_2017/papers/Wang_ChestX-ray8_Hospital-Scale_Chest_CVPR_2017_paper.pdf)

[Aistudio下载](https://aistudio.baidu.com/aistudio/datasetdetail/35660)

## QIN Lung CT

| 名称 | 标注内容 | 类型 | 模态 | 数量 | 标签格式 | 文件格式 | License |
| - | - | - | - | - | - | - | - |
| [QIN Lung CT](https://wiki.cancerimagingarchive.net/display/Public/QIN+LUNG+CT) | 非小細胞癌 |  | CT  | 47 |  | dcm | [Other](https://wiki.cancerimagingarchive.net/display/Public/Data+Usage+Policies+and+Restrictions) |

[Aistudio下载](https://aistudio.baidu.com/aistudio/datasetdetail/35205)

## 4D-Lung

| 名称 | 标注内容 | 类型 | 模态 | 数量 | 标签格式 | 文件格式 | License |
| - | - | - | - | - | - | - | - |
| [4D-Lung](https://wiki.cancerimagingarchive.net/display/Public/4D-Lung) | 非小細胞癌 |      | CT |  | 20 | dcm |[Other](https://wiki.cancerimagingarchive.net/display/Public/Data+Usage+Policies+and+Restrictions)|

[Aistudio下载](https://aistudio.baidu.com/aistudio/datasetdetail/37482)

## NSCLC-Radiomics

| 名称 | 标注内容 | 类型 | 模态 | 数量 | 标签格式 | 文件格式 |
| - | - | - | - | - | - | - |
| [NSCLC-Radiomics](https://wiki.cancerimagingarchive.net/display/Public/NSCLC-Radiomics) | 非小细胞癌　| 分割　|　CT | 422 |          | dcm |

![NSCLC-Radiomics](https://raw.githubusercontent.com/linhandev/dataset/main/static/NSCLC-Radiomics.png)

[Aistudio下载](https://aistudio.baidu.com/aistudio/datasetdetail/63958)



## vessel12 肺部血管分割

| 名称 | 标注内容 | 类型 | 模态 | 数量 | 标签格式 | 文件格式 | License |
| - | - | - | - | - | - | - | - |
| [vessel12 肺部血管分割](https://vessel12.grand-challenge.org/) | 肺部血管 | 分割　|　CT | 20 |  | raw | |

![vessel12](https://grand-challenge-public-prod.s3.amazonaws.com/b/1/header.x15.jpeg)

[Aistudio下载](https://aistudio.baidu.com/aistudio/datasetdetail/94923)

## 肺结核

### Shenzhen Hospital X-ray Set

| 名称 | 标注内容 | 类型 | 模态 | 数量 | 标签格式 | 文件格式 |
| - | - | - | - | - | - | - |
| [Shenzhen Hospital X-ray Set](https://lhncbc.nlm.nih.gov/publication/pub9931) | 肺结核/正常 | 分类 | CXR  | 662  | 类别     | 图片     |

深圳第三医院收集的肺结核胸透数据集，包含326张正常扫描和336张不正常的扫描。

[Aistudio下载](https://aistudio.baidu.com/aistudio/datasetdetail/25237)

### Montgomery County X-ray Set

| 名称 | 标注内容 | 类型 | 模态 | 数量 | 标签格式 | 文件格式 |
| - | - | - | - | - | - | - |
| [Montgomery County X-ray Set](https://lhncbc.nlm.nih.gov/publication/pub9931) | 肺结核/正常 | 分类 | CXR  | 138  | 类别     | 图片     |

蒙哥马利市收集的肺结核胸透数据集，包含80张正常的扫描和58张不正常的扫描。

[Aistudio下载](https://aistudio.baidu.com/aistudio/datasetdetail/34229)

## 肺炎
### Ieee8023

| 名称 | 标注内容 | 类型 | 模态 | 数量 | 标签格式 | 文件格式 |
| - | - | - | - | - | - | - |
| [Ieee8023](https://github.com/ieee8023/covid-chestxray-dataset) | 肺脏     | 分类 | CT   | 20   |      | nii      |

持续搜集公开的新冠CT扫描，目前有20个病例。

[Aistudio下载](https://aistudio.baidu.com/aistudio/datasetdetail/34221)

### covid19-ct-scans

| 名称 | 标注内容 | 类型 | 模态 | 数量 | 标签格式 | 文件格式 |
| - | - | - | - | - | - | - |
| [covid19-ct-scans](https://www.kaggle.com/andrewmvd/covid19-ct-scans) | 左右肺/新冠感染 | 分割 | CT   | 20   |          | nii      |

数据来自Ieee8023，对20组扫描进行了左右肺和感染区的标注。基于这个数据集和另外几个数据集，大佬们做了一个新冠分割的 [benchmark](https://gitee.com/junma11/COVID-19-CT-Seg-Benchmark)

[Aistudio下载](https://aistudio.baidu.com/aistudio/datasetdetail/34221)

### COVID-CT

| 名称 | 标注内容 | 类型 | 模态 | 数量 | 标签格式 | 文件格式 |
| - | - | - | - | - | - | - |
| [COVID-CT](https://github.com/UCSD-AI4H/COVID-CT) |          | 分类 | CT   | 349  |          | 图片     |

包含216名新冠患者的349张胸部CT图片，从相关paper中收集。

[Aistudio下载](https://aistudio.baidu.com/aistudio/datasetdetail/27732)

### Figure1-COVID-chestxray-dataset

| 名称 | 标注内容 | 类型 | 模态 | 数量 | 标签格式 | 文件格式 |
| - | - | - | - | - | - | - |
| [Figure1-COVID-chestxray-dataset](https://github.com/agchung/Figure1-COVID-chestxray-dataset) |          | 分类 | CXR  | 48   |          | 图片     |

DarwinAI收集的一些新冠CT的图片，是CovidX数据集的一部分。持续更新，使用前可以先pull。

[Aistudio下载](https://aistudio.baidu.com/aistudio/datasetdetail/34208)

### RSNA肺炎检测

|                                     名称                                     |      标注内容       |   类型    | 模态 |    数量    | 标签格式 | 文件格式 |                                   License                                   |
| ---------------------------------------------------------------------------- | ------------------- | --------- | ---- | ---------- | -------- | -------- | --------------------------------------------------------------------------- |
| [RSNA肺炎检测](https://www.kaggle.com/c/rsna-pneumonia-detection-challenge/) | 是否肺炎 肺炎区域BB | 分类 检测 | CXR  | 26684+3000 |          |   图片   | [Custom](https://www.kaggle.com/c/rsna-pneumonia-detection-challenge/rules) |

北美放射学会在Kaggle上组织的一个比赛数据集，数据来自[NIH](https://nihcc.app.box.com/v/ChestXray-NIHCC)。包含26684张训练数据，有图片的分类和肺炎区域的边界框。

[//]: # (https://aistudio.baidu.com/aistudio/datasetdetail/34214)

### CovidX

| 名称 | 标注内容 | 类型 | 模态 | 数量 | 标签格式 | 文件格式 |
| - | - | - | - | - | - | - |
| [CovidX](https://github.com/lindawangg/COVID-Net/blob/master/docs/COVIDx.md) | 新冠/其他肺炎/正常 | 分类 | CT   | 13569+231 |          | 图片     |

CovidX数据集是DarwinAI训练[CovidNet](https://github.com/lindawangg/COVID-Net)做的一个数据集，本身没有新的数据，是Ieee8023，Figure1和RSNA组合成的一个数据集。


### Flyai Covid

| 名称 | 标注内容 | 类型 | 模态 | 数量 | 标签格式 | 文件格式 |
| - | - | - | - | - | - | - |
| [Flyai Covid](https://www.flyai.com/d/ChestXray02) |          |      |      |      |          |          |

Flyai举办的一个新冠分类比赛。

[Aistudio下载](https://aistudio.baidu.com/aistudio/datasetdetail/34230)

### covid19-radiography-database

| 名称 | 标注内容 | 类型 | 模态 | 数量 | 标签格式 | 文件格式 |
| - | - | - | - | - | - | - |
| [covid19-radiography-database](https://www.kaggle.com/tawsifurrahman/covid19-radiography-database) | 新冠/其他肺炎/正常 | 分类 | CT   | 219+1314+1345 |          | 图片     |

跟CovidX一样是一个组合数据集，数据来自论文图片和RSNA。

[Aistudio下载](https://aistudio.baidu.com/aistudio/datasetdetail/34241)

### COVID-19-AR

| 名称 | 标注内容 | 类型 | 模态 | 数量 | 标签格式 | 文件格式 |
| - | - | - | - | - | - | - |
| [COVID-19-AR](https://wiki.cancerimagingarchive.net/pages/viewpage.action?pageId=70226443) | |  |    |  | | dcm|

Chest Imaging with Clinical and Genomic Correlates Representing a Rural COVID-19 Positive Population (COVID-19-AR)

[Aistudio下载](https://aistudio.baidu.com/aistudio/datasetdetail/63553)

### CT Images in COVID-19

| 名称 | 标注内容 | 类型 | 模态 | 数量 | 标签格式 | 文件格式 |
| --- | --- | --- | --- | --- | --- | --- |
| [CT Images in COVID-19](https://wiki.cancerimagingarchive.net/display/Public/CT+Images+in+COVID-19) | 无标签 | 分类/分割 | CT 平扫 | 771 | 无 | nii |

<img src="https://raw.githubusercontent.com/linhandev/dataset/main/static/ct-images-in-covid19.png" width="50%"/>

[Aistudio下载](https://aistudio.baidu.com/aistudio/datasetdetail/63794)
相关论文：
- [Artificial intelligence for the detection of COVID-19 pneumonia on chest CT using multinational datasets](https://www.nature.com/articles/s41467-020-17971-2)
- [Generalized chest CT and lab curves throughout the course of COVID-19](https://www.nature.com/articles/s41598-021-85694-5)

## 肺结节

### LIDC-IDRI

| 名称 | 标注内容 | 类型 | 模态 | 数量 | 标签格式 | 文件格式 |
| - | - | - | - | - | - | - |
| [LIDC-IDRI](https://wiki.cancerimagingarchive.net/display/Public/LIDC-IDRI) | 肺部肿瘤 | 目标检测 | CT | 1012 | xls | dcm |

介绍论文： [The Lung Image Database Consortium (LIDC) and Image Database Resource Initiative (IDRI): A Completed Reference Database of Lung Nodules on CT Scans](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC3041807/)

[The public cancer radiology imaging collections of The Cancer Imaging Archive](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC3041807/)

Aistudio下载 [Part1](https://aistudio.baidu.com/aistudio/datasetdetail/63957) [Part2](https://aistudio.baidu.com/aistudio/datasetdetail/64008)

### LUNA16

| 名称 | 标注内容 | 类型 | 模态 | 数量 | 标签格式 | 文件格式 |
| - | - | - | - | - | - | - |
| [LUNA16](https://luna16.grand-challenge.org) |          |      |      |      |          |          |

[Aistudio下载](https://aistudio.baidu.com/aistudio/datasetdetail/1860)

### 天池肺部结节

| 名称 | 标注内容 | 类型 | 模态 | 数量 | 标签格式 | 文件格式 | License |
| - | - | - | - | - | - | - | - |
| [天池肺部结节](https://tianchi.aliyun.com/competition/entrance/231601/introduction) | 肺部结节| 检测 | 低剂量肺部CT | 1000(初赛) + 2000(复赛) | 位置+直径 | mhd | [Custom](https://tianchi.aliyun.com/competition/entrance/231601/introduction) |

[//]: # (训练：https://aistudio.baidu.com/aistudio/datasetDetail/20000 测试 : https://aistudio.baidu.com/aistudio/datasetdetail/10063)

### LNDB

| 名称 | 标注内容 | 类型 | 模态 | 数量 | 标签格式 | 文件格式 |
| - | - | - | - | - | - | - |
| [LNDB](https://lndb.grand-challenge.org) | 直径大于3mm的肿瘤分割标注/小于3mm肿瘤和非肿瘤标记中心 | 分割/分类 | CT   | 294  | XML      | MetaImage |

介绍论文： [LNDb: A Lung Nodule Database on Computed Tomography](https://arxiv.org/abs/1911.08434)

[Aistudio下载](https://aistudio.baidu.com/aistudio/datasetdetail/23909)

### Lung Nodule Malignancy

| 名称 | 标注内容 | 类型 | 模态 | 数量 | 标签格式 | 文件格式 |
| - | - | - | - | - | - | - |
| [Lung Nodule Malignancy](https://www.kaggle.com/kmader/lungnodemalignancy) | 肺结界良恶性 | 分类 | CT   | 4165+2526 |          | tif      |

[Aistudio下载](https://aistudio.baidu.com/aistudio/datasetdetail/28474)

### Data Science Bowl 17

| 名称 | 标注内容 | 类型 | 模态 | 数量 | 标签格式 | 文件格式 |
| - | - | - | - | - | - | - |
| [Data Science Bowl 17](https://www.kaggle.com/c/data-science-bowl-2017) |          |      |      |      |          |          |

[Aistudio下载](https://aistudio.baidu.com/aistudio/datasetdetail/25423)

### Lung-PET-CT-Dx

| 名称 | 标注内容 | 类型 | 模态 | 数量 | 标签格式 | 文件格式 |
| - | - | - | - | - | - | - |
| [Lung-PET-CT-Dx](https://wiki.cancerimagingarchive.net/pages/viewpage.action?pageId=70224216) | 肺癌　| 目标检测 | CT | 363 | xml | dcm |

![Lung-PET-CT-Dx](https://raw.githubusercontent.com/linhandev/dataset/main/static/Lung-PET-CT-Dx.png)

## 气胸

### SIIM-ACR Pneumothorax Segmentation

| 名称      | 标注内容 | 类型 | 模态 | 数量 | 标签格式 | 文件格式 |
| - | - | - | - | - | - | - |
| [SIIM-ACR Pneumothorax Segmentation](https://www.kaggle.com/c/siim-acr-pneumothorax-segmentation) |   |   |    |   |   |  |

# 胸

## CBIS-DDSM

| 名称 | 标注内容 | 类型 | 模态 | 数量 | 标签格式 | 文件格式 |
| - | - | - | - | - | - | - |
| [CBIS-DDSM](https://wiki.cancerimagingarchive.net/display/Public/CBIS-DDSM) | 正常/良性/恶性 | 分类 | CT   | 2620 |          |          |

介绍论文： [Deep Learning to Improve Breast Cancer Early Detection on Screening Mammography](https://arxiv.org/abs/1708.09427) [A curated mammography data set for use in computer-aided detection and diagnosis research](https://www.nature.com/articles/sdata2017177)

[Aistudio下载](https://aistudio.baidu.com/aistudio/datasetdetail/37567)

## QIN Breast

| 名称 | 标注内容 | 类型 | 模态 | 数量 | 标签格式 | 文件格式 |
| - | - | - | - | - | - | - |
| QIN Breast [01](https://wiki.cancerimagingarchive.net/display/Public/QIN-Breast)[02](https://wiki.cancerimagingarchive.net/display/Public/QIN-BREAST-02) |          |      | MRI  | 67   |          |          |

[Aistudio下载](https://aistudio.baidu.com/aistudio/datasetdetail/37536)

## Rider Breast MRI

| 名称 | 标注内容 | 类型 | 模态 | 数量 | 标签格式 | 文件格式 |
| - | - | - | - | - | - | - |
| [Rider Breast MRI](https://wiki.cancerimagingarchive.net/display/Public/RIDER+Breast+MRI) |   |   | MRI   | |   |  |

## ACRIN 6688

| 名称 | 标注内容 | 类型 | 模态 | 数量 | 标签格式 | 文件格式 |
| - | - | - | - | - | - | - |
| [ACRIN 6688](https://wiki.cancerimagingarchive.net/pages/viewpage.action?pageId=30671268) |          |      | CT   | 83   |          |          |

[Aistudio下载](https://aistudio.baidu.com/aistudio/datasetdetail/37565)

# 脑

## BraTS2013

| 名称 | 标注内容 | 类型 | 模态 | 数量 | 标签格式 | 文件格式 |
| - | - | - | - | - | - | - |
| [BraTS2013](https://www.smir.ch/BRATS/Start2013) |          |      |      |      |          |          |



## BraTS2015

| 名称 | 标注内容 | 类型 | 模态 | 数量 | 标签格式 | 文件格式 |
| - | - | - | - | - | - | - |
| [BraTS2015](https://www.smir.ch/BRATS/Start2015) |          |      |      |      |          |          |

[Aistudio下载](https://aistudio.baidu.com/aistudio/datasetdetail/26367)

## BraTS2021

| 名称 | 标注内容 | 类型 | 模态 | 数量 | 标签格式 | 文件格式 |
| - | - | - | - | - | - | - |
| [BraTS2021](http://www.braintumorsegmentation.org/) |          |      |      |      |          |          |

## MSD脑瘤分割

| 名称 | 标注内容 | 类型 | 模态 | 数量 | 标签格式 | 文件格式 | License |
| - | - | - | - | - | - | - | - |
| [MSD Brain Tumor Segmentation](http://medicaldecathlon.com/) | 胶质瘤/肿瘤/水肿 | 分割 | MRI | 484 Train + 266 Test | 0/1 | nii | [CC-BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/) |

![msd-brain](https://raw.githubusercontent.com/linhandev/dataset/main/static/msd-brain-tumor.png)

[Aistudio下载](https://aistudio.baidu.com/aistudio/datasetdetail/10277)


## MSD海马体分割

| 名称 | 标注内容 | 类型 | 模态 | 数量 | 标签格式 | 文件格式 | License |
| - | - | - | - | - | - | - | - |
| [MSD Hippocampus Segmentation](http://medicaldecathlon.com/) | 海马体 | 分割 | MRI | 394 | 0/1 | nii | [CC-BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/) |

![msd-hippocampus](https://raw.githubusercontent.com/linhandev/dataset/main/static/msd-hippocampus.png)

[Aistudio下载](https://aistudio.baidu.com/aistudio/datasetdetail/23862)

## Iseg2019

| 名称 | 标注内容 | 类型 | 模态 | 数量 | 标签格式 | 文件格式 |
| - | - | - | - | - | - | - |
| [Iseg2019](http://iseg2019.web.unc.edu/) |          |      |      |      |          |          |

## ABIDE

| 名称 | 标注内容 | 类型 | 模态 | 数量 | 标签格式 | 文件格式 |
| - | - | - | - | - | - | - |
| [ABIDE](http://fcon_1000.projects.nitrc.org/indi/abide/) | 是否有自闭症 | 分类 | MRI  | 539+573 |          |          |

自闭症患者的头部MRI扫描，包含539例自闭症患者和573个正常扫描对照组。  介绍论文： [The autism brain imaging data exchange: towards a large-scale evaluation of the intrinsic brain architecture in autism.](https://www.ncbi.nlm.nih.gov/pubmed/23774715)

[下载地址](http://preprocessed-connectomes-project.org/abide/download.html)


## ADNI

| 名称 | 标注内容 | 类型 | 模态 | 数量 | 标签格式 | 文件格式 |
| - | - | - | - | - | - | - |
| [ADNI](http://adni.loni.usc.edu/data-samples/access-data/) |          |      |      |      |          |          |

介绍论文： [Alzheimer's Disease Neuroimaging Initiative (ADNI)](https://n.neurology.org/content/74/3/201.short)

## CQ500

| 名称 | 标注内容 | 类型 | 模态 | 数量 | 标签格式 | 文件格式 | License |
| - | - | - | - | - | - | - | - |
| [CQ500](http://headctstudy.qure.ai/) |  | 分割 |  | CT | 491组扫描 |  | [by-nc-sa 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/) |

介绍论文:[Development and Validation of Deep Learning Algorithms for Detection of Critical Findings in Head CT Scans](https://arxiv.org/abs/1803.05854)


## 脑出血

### RSNA Intracranial Hemorrhage Detection

| 名称 | 标注内容 | 类型 | 模态 | 数量 | 标签格式 | 文件格式 |
| - | - | - | - | - | - | - |
| [RSNA Intracranial Hemorrhage Detection](https://www.kaggle.com/c/rsna-intracranial-hemorrhage-detection) |          |      | CT   |      |          |          |

[//]: # (https://aistudio.baidu.com/aistudio/datasetdetail/35741)
[//]: # (TODO:链接)
[//]: # (TODO:完善内容)

# 肾脏

## Kits19

| 名称 | 标注内容 | 类型 | 模态 | 数量 | 标签格式 | 文件格式 | License |
| - | - | - | - | - | - | - | - |
| [Kits19](https://kits19.grand-challenge.org/) | 肾脏/肾肿瘤 | 分割 |  | | | | |

![kits19](https://raw.githubusercontent.com/linhandev/dataset/main/static/kits19.png)

[Aistudio下载](https://aistudio.baidu.com/aistudio/datasetdetail/24582)

# 肠

## CT COLONOGRAPHY

| 名称 | 标注内容 | 类型 | 模态 | 数量 | 标签格式 | 文件格式 |
| - | - | - | - | - | - | - |
| [CT COLONOGRAPHY](https://wiki.cancerimagingarchive.net/display/Public/CT+COLONOGRAPHY#dc149b9170f54aa29e88f1119e25ba3e) |          |      | CT   |      |          |          |

包含没有结肠息肉，有6-9mm息肉和大于10mm息肉的数据。

## MSD肠道分割数据集

| 名称 | 标注内容 | 类型 | 模态 | 数量 | 标签格式 | 文件格式 | License |
| - | - | - | - | - | - | - | - |
| [MSD肠道分割数据集](http://medicaldecathlon.com/) | 结肠癌原发病灶 | 分割 | CT | 126训练+64测试 |  |  | [CC-BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/) |

[Aistudio下载](https://aistudio.baidu.com/aistudio/datasetdetail/10332)

# 心脏

## EchoNet

| 名称 | 标注内容 | 类型 | 模态 | 数量 | 标签格式 | 文件格式 |
| - | - | - | - | - | - | - |
| [EchoNet](https://echonet.github.io/dynamic/index.html) | 心脏 | 分割 | MRI  | 10300 | 0/1 | |

介绍论文： [EchoNet-Dynamic: a Large New Cardiac Motion Video Data Resource for Medical Machine Learning](https://echonet.github.io/dynamic/NeuroIPS_2019_ML4H%20Workshop_Paper.pdf)

## MMWHS

| 名称 | 标注内容 | 类型 | 模态 | 数量 | 标签格式 | 文件格式 |
| - | - | - | - | - | - | - |
| [MMWHS](https://zmiclab.github.io/zxh/0/mmwhs/) | 心脏     | 分割 | CT / MRI | 20CT、20MRI | 类别     | nii      |

mmwhs是心脏分割数据集，共有8类，MRI和CT两种模态  相关项目： [Hybrid Loss Guided Convolutional Networks for Whole Heart Parsing](https://github.com/xy0806/miccai17-mmwhs-hybrid)

<!-- [Aistudio下载](https://aistudio.baidu.com/aistudio/datasetdetail/38799) -->

## MSD心脏分割

| 名称 | 标注内容 | 类型 | 模态 | 数量 | 标签格式 | 文件格式 | License |
| - | - | - | - | - | - | - | - |
| [MSD心脏分割](http://medicaldecathlon.com/) | 左心房 | 分割 | MRI | 20(训练)+10(测试) |  |  | [CC-BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/) |

![msd-Cardiac](https://raw.githubusercontent.com/linhandev/dataset/main/static/mds-cardiac.png)

[Aistudio下载](https://aistudio.baidu.com/aistudio/datasetdetail/23911)

## 主动脉

### 冠状动脉分割

| 名称 | 标注内容 | 类型 | 模态 | 数量 | 标签格式 | 文件格式 | License |
| - | - | - | - | - | - | - | - |
| [Automated Segmentation of Coronary Arteries](https://asoca.grand-challenge.org/) | 冠状动脉 | 分割 | CTA | 40+20 | |  | [Custom](https://zenodo.org/record/3819799#.YKccAUQzbIU) |

[Grand Challenge下载](https://asoca.grand-challenge.org/)

# 眼睛

## DRIVE

| 名称 | 标注内容 | 类型 | 模态 | 数量 | 标签格式 | 文件格式 |
| - | - | - | - | - | - | - |
| [DRIVE](https://drive.grand-challenge.org/) | 眼底血管 | 分割 | 眼底照片 | 40   | 0/1      | 图片     |

DRIVE数据集是一个糖尿病病人眼底血管分割数据集。

[Aistudio下载](https://aistudio.baidu.com/aistudio/datasetdetail/27737)

## ODIR-5k

| 名称 | 标注内容 | 类型 | 模态 | 数量 | 标签格式 | 文件格式 |
| - | - | - | - | - | - | - |
| [ODIR-5k](https://odir2019.grand-challenge.org/) | 正常和7种疾病 | 分类 | 眼底彩色照片 | 5000 |          | 图片     |

ODIR-5K包括5000名患者的年龄，双眼的彩色眼底照片和医生的诊断关键词。该数据集是上工医疗技术有限公司从中国不同医院/医疗中心收集的“真实”患者信息。在这些机构中，眼底图像由市场上的各种相机捕获，例如Canon，Zeiss和Kowa，因此导致各种各样的图像分辨率。病人的识别信息会被移除。注释由经过培训的人类读者进行标记，并具有质量控制管理。患者分为8个标签，包括正常（N），糖尿病（D），青光眼（G），白内障（C），AMD（A），高血压（H），近视（M）和其他疾病/异常（O）。

[//]: # (TODO:搬运，添加下载链接)

## FIRE 视网膜图像数据

| 名称 | 标注内容 | 类型 | 模态 | 数量 | 标签格式 | 文件格式 |
| - | - | - | - | - | - | - |
| [FIRE 视网膜图像数据](http://www.ics.forth.gr/cvrl/fire/) |          | 分类 | 视网膜图像 | 129  |          |          |

FIRE 是一个视网膜眼底图像数据集，包含 129张 眼底视网膜图像，由不同特征组合成 134对 图像组合。这些图像组合根据特质被划分为3类。眼底图像由 Nidek AFC-210 眼底照相机采集，分辨率为2912x2912，视觉仰角为40度。图像由 Papageorgiou Hospital 医院和Aristotle University of Thessaloniki大学共同构建，由于Thessaloniki 大学采集自39名患者。. 数据包括以下几部分内容：  1.成对的视网膜图像。 2.彩色ROI掩模（作为二值图像）。 3.特征ROI掩模（作为二值图像）。 4.每个图像对应的标注点。

[//]: # (TODO:添加数据集链接)

## STARE

| 名称 | 标注内容 | 类型 | 模态 | 数量 | 标签格式 | 文件格式 | License |
| - | - | - | - | - | - | - | - |
| [STARE](https://cecas.clemson.edu/~ahoover/stare/) | 眼底血管 | 分割 | 眼底照片 | 400 | 照片 | 照片 | 无 |

![stare](https://raw.githubusercontent.com/linhandev/dataset/main/static/stare.png)

STructured Analysis of the Retina数据集包含400张眼底照片，作者团队对这些数据进行了多种诊断，并对部分数据的血管进行了标注

[Aistudio下载](https://aistudio.baidu.com/aistudio/datasetdetail/81241)


## CHASE_DB1

| 名称 | 标注内容 | 类型 | 模态 | 数量 | 标签格式 | 文件格式 | License |
| - | - | - | - | - | - | - | - |
| [CHASE_DB1](https://blogs.kingston.ac.uk/retinal/) | 眼底血管 | 分割 | 眼底照片 | 28 | png | png | 无 |

![CHASE_DB1](https://raw.githubusercontent.com/linhandev/dataset/main/static/CHASE_DB1.png)

Kinston大学公开的一个小规模眼底分割数据集，包含28张眼底照片及对应的分割标签。

[Aistudio下载](https://aistudio.baidu.com/aistudio/datasetdetail/81247)

## IDRiD

| 名称 | 标注内容 | 类型 | 模态 | 数量 | 标签格式 | 文件格式 | License |
| - | - | - | - | - | - | - | - |
| [IDRiD](https://idrid.grand-challenge.org) | 常见DR病灶、视盘、DR病变等级等 | 分类、检测、分割 | 眼底照片 | * | tif/csv | jpg | [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) |

Indian Diabetic Retinopathy Image Dataset (IDRiD)

[Aistudio下载](https://aistudio.baidu.com/aistudio/datasetdetail/91860/0)



# 前列腺

## PANDA

| 名称 | 标注内容 | 类型 | 模态 | 数量 | 标签格式 | 文件格式 |
| - | - | - | - | - | - | - |
| [PANDA](https://www.kaggle.com/c/prostate-cancer-grade-assessment/overview) | 前列腺癌分级 |      | 镜检图片 | 10616张镜检 | 分类     | tiff |


## MSD前列腺分割

| 名称 | 标注内容 | 类型 | 模态 | 数量 | 标签格式 | 文件格式 | License |
| - | - | - | - | - | - | - | - |
| [MSD前列腺分割](http://medicaldecathlon.com/) | 前列腺中央腺体及外周区域 | 分割 | 多模态核磁 | 32(训练)+16(测试) | | | [CC-BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/) |

![msd-prostate](https://raw.githubusercontent.com/linhandev/dataset/main/static/msd-prostate.png)

[Aistudio下载](https://aistudio.baidu.com/aistudio/datasetdetail/23912)

## QIN-PROSTATE-Repeatability

| 名称 | 标注内容 | 类型 | 模态 | 数量 | 标签格式 | 文件格式 |
| - | - | - | - | - | - | - |
| [QIN-PROSTATE-Repeatability](https://wiki.cancerimagingarchive.net/display/Public/QIN-PROSTATE-Repeatability) | 前列腺癌　|  | MRI | 15 |　　| dcm |

![QIN-Prostate-Repeatability](https://raw.githubusercontent.com/linhandev/dataset/main/static/QIN-Prostate-Repeatability.png)

[Aistudio下载](https://aistudio.baidu.com/aistudio/datasetdetail/63950)

# 胰腺

## MSD胰腺分割

| 名称 | 标注内容 | 类型 | 模态 | 数量 | 标签格式 | 文件格式 | License |
| - | - | - | - | - | - | - | - |
| [MSD胰腺分割](http://medicaldecathlon.com/) | 胰腺肿瘤 | 分割 | CT | 282(训练)+139(验证) | 0/1 | nii | [CC-BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/) |

[Aistudio下载](https://aistudio.baidu.com/aistudio/datasetdetail/23914)

## PDMR-833975-119-R

| 名称 | 标注内容 | 类型 | 模态 | 数量 | 标签格式 | 文件格式 |
| - | - | - | - | - | - | - |
| [PDMR-833975-119-R](https://wiki.cancerimagingarchive.net/display/Public/Imaging+tissue+characterization+of+a+patient+derived+xenograft+model+of+adenocarcinoma+pancreas%3A+PDMR-833975-119-R) |　胰腺癌　|      |　MRI | 20 | | dcm |

![PDMR-833975-119-R](https://raw.githubusercontent.com/linhandev/dataset/main/static/PDMR-833975-119-R.png)

[Aistudio下载](https://aistudio.baidu.com/aistudio/datasetdetail/64052)

# 皮肤

## SIIM-ISIC Melanoma Classification

| 名称 | 标注内容 | 类型 | 模态 | 数量 | 标签格式 | 文件格式 |
| - | - | - | - | - | - | - |
| [SIIM-ISIC Melanoma Classification](https://www.kaggle.com/c/siim-isic-melanoma-classification/data) | 皮肤癌病变类别 | 分类 | 皮肤镜 | 88.3K张图片 | 类别     | dicom   |

目前最大的皮肤镜图像集合，用来在皮肤病变图像中之别黑色素瘤，图片以DICOM格式提供，同时包含图像元数据，有的图像也以JPEG和TFRecord格式提供，TFRecords格式的图像已被调整为统一的1024x1024

[//]: # (TODO: 添加这个数据集的下载)

# 镜检

## 细胞

### Data Science Bowl 18

| 名称 | 标注内容 | 类型 | 模态 | 数量 | 标签格式 | 文件格式 |
| - | - | - | - | - | - | - |
| [Data Science Bowl 18](https://www.kaggle.com/c/data-science-bowl-2018) | 细胞核   | 分割 |      | 841张/37333个细胞核 | 0/1      | 图片     |

细胞核分割数据集

介绍论文： [Nucleus segmentation across imaging experiments: the 2018 Data Science Bowl](https://www.ncbi.nlm.nih.gov/pubmed/31636459)

[Aistudio下载](https://aistudio.baidu.com/aistudio/datasetdetail/10292)

### 血细胞涂片分类

| 名称 | 标注内容 | 类型 | 模态 | 数量 | 标签格式 | 文件格式 |
| - | - | - | - | - | - | - |
| [血细胞涂片分类](https://www.kaggle.com/paultimothymooney/blood-cells) | 四种血细胞类型 | 分类 | 镜检 | 12500 | -        | 图片     |

血细胞分类数据集包含12500张四种血细胞的照片。图片是从大的血细胞涂片照片上截下来的，数据集经过增广。图片都很小，训练时注意IO瓶颈。

[Aistudio下载](https://aistudio.baidu.com/aistudio/datasetdetail/10278)

### ISBI细胞跟踪

| 名称 | 标注内容 | 类型 | 模态 | 数量 | 标签格式 | 文件格式 |
| - | - | - | - | - | - | - |
| [ISBI细胞跟踪](http://celltrackingchallenge.net/) | 细胞像素级别位置 | 跟踪 | 镜检 |      |          | 图片     |

在镜检视频中像素级跟踪细胞位置

Aistudio下载 [2D+Time Datasets](https://aistudio.baidu.com/aistudio/datasetdetail/78515)

## 穿刺
### BCNB乳腺癌穿刺活检
|                    名称                    |  标注内容  | 类型 | 模态 | 数量 | 标签格式 | 文件格式  |                        License                         |
| ------------------------------------------ | ---------- | ---- | ---- | ---- | -------- | --------- | ------------------------------------------------------ |
| [BCNB](https://bupt-ai-cz.github.io/BCNB/) | 乳腺癌肿瘤 | 分类 |      | 1058 |  excel   | JPG Excel | [Custom](https://github.com/bupt-ai-cz/BALNMP#license) |

Early Breast Cancer Core-Needle Biopsy WSI (BCNB) Dataset，早期乳腺癌患者的穿刺活检WSI。在早期乳腺癌患者的病理WSI中，标注了部分的肿瘤区域，并提供了一些临床信息（age, tumor size, tumor type, ER, PR, HER2, HER2 expression, histological grading, surgical, Ki67, molecular subtype, number of lymph node metastases, label）

# 骨骼

## MURA-1.1

| 名称 | 标注内容 | 类型 | 模态 | 数量 | 标签格式 | 文件格式 |
| - | - | - | - | - | - | - |
| [MURA-1.1](https://stanfordmlgroup.github.io/competitions/mura/) | 正常/非正常 | 分类 | x-ray | 40561 |          |          |

介绍论文： [MURA: Large Dataset for Abnormality Detection in Musculoskeletal Radiographs](https://arxiv.org/abs/1712.06957)

[Aistudio下载](https://aistudio.baidu.com/aistudio/datasetdetail/20010)


## RSNA Bone Age

| 名称 | 标注内容 | 类型 | 模态 | 数量 | 标签格式 | 文件格式 |
| - | - | - | - | - | - | - |
| [RSNA Bone Age](https://www.kaggle.com/kmader/rsna-bone-age) |          |      |      |      |          |          |

[Aistudio下载](https://aistudio.baidu.com/aistudio/datasetdetail/36300)

## 磁共振图像脊柱结构多类别三维自动分割

| 名称 | 标注内容 | 类型 | 模态 | 数量  | 标签格式 | 文件格式  | License |
| - | - | - | - | - | - | - | - |
| [磁共振图像脊柱结构多类别三维自动分割](https://www.spinesegmentation-challenge.com/) | 椎骨和椎间盘 | 分割 | MRI T2WI | 172 | 0/1 | nii | [Custom](https://www.spinesegmentation-challenge.com/?page_id=34) |

![spine-mri](https://raw.githubusercontent.com/linhandev/dataset/main/static/spine-mri.png)

[Aistudio下载](https://aistudio.baidu.com/aistudio/datasetdetail/81211)

## 膝盖

### MRNet

| 名称 | 标注内容 | 类型 | 模态 | 数量 | 标签格式 | 文件格式 |
| - | - | - | - | - | - | - |
| [MRNet](https://stanfordmlgroup.github.io/competitions/mrnet/) |          |      |      |      |          |          |

[Aistudio下载](https://aistudio.baidu.com/aistudio/datasetdetail/24584)

## 脊椎

### Verse大规模脊椎分割数据集

| 名称 | 标注内容 | 类型 | 模态 | 数量  | 标签格式 | 文件格式  | License |
| - | - | - | - | - | - | - | - |
| [VerSe](https://github.com/anjany/verse) | 脊椎 | 分割 | | | | | [CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/) |

<img src="https://raw.githubusercontent.com/linhandev/dataset/main/static/verse.png" width="50%"/>

[Aistudio下载](https://aistudio.baidu.com/aistudio/datasetdetail/86496)


# VQA

## PathVQA

| 名称 | 标注内容 | 类型 | 模态 | 数量 | 标签格式 | 文件格式 |
| - | - | - | - | - | - | - |
| [PathVQA](https://pathvqachallenge.grand-challenge.org/PathVQA_challenge/) |          |      | 图片 | 4998图片/32799问答 |          | 图片     |

介绍论文： [PathVQA: 30000+ Questions for Medical Visual Question Answering](https://arxiv.org/abs/2003.10286)

[Aistudio下载](https://aistudio.baidu.com/aistudio/datasetdetail/25239)

# 内窥镜

## SARAS-MESAD

| 名称 | 标注内容 | 类型 | 模态 | 数量 | 标签格式 | 文件格式 | License |
| - | - | - | - | - | - | - | - |
| [SARAS-MESAD](https://saras-mesad.grand-challenge.org/) | 24种动作 | 静态背景动作识别 | 内窥镜 | 4(真实手术)+5(模拟手术) |  |     | [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/) |

![saras-mesad](https://raw.githubusercontent.com/linhandev/dataset/main/static/saras-mesad.png)

[//]: # (TODO: https://aistudio.baidu.com/aistudio/datasetdetail/90922)


## SARAS-MESAD

| 名称 | 标注内容 | 类型 | 模态 | 数量 | 标签格式 | 文件格式 | License |
| - | - | - | - | - | - | - | - |
| [SARAS-ESAD](https://saras-esad.grand-challenge.org/) | 21种手术动作 | 静态背景动作识别 | 内窥镜 |  22,601(训练)+4,574(测试) | 图片 | BB | [CC BY-NC-SA](https://creativecommons.org/licenses/by-nc-sa/3.0/) |

![SARAS-ESAD](https://raw.githubusercontent.com/linhandev/dataset/main/static/SARAS-ESAD.png)

[//]: # (TODO: https://aistudio.baidu.com/aistudio/datasetdetail/90922)

# 数字病理

## CAMELYON
| 名称 | 标注内容 | 类型 | 模态 | 数量 | 标签格式 | 文件格式 | License |
| - | - | - | - | - | - | - | - |
| [CAMELYON16，17](https://camelyon17.grand-challenge.org/) |  | | 镜检 |  | 图片 | BB | [CC0](https://creativecommons.org/publicdomain/zero/1.0/) |

![CAMELYON17](https://grand-challenge-public-prod.s3.amazonaws.com/b/80/camelyon17_header.x15.jpeg)

[//]: # (TODO: Aistudio下载)

# 心电图

## CAMELYON
| 名称 | 标注内容 | 类型 | 模态 | 数量 | 标签格式 | 文件格式 | License |
| - | - | - | - | - | - | - | - |
| [TUH EEG信号](https://isip.piconepress.com/projects/tuh_eeg/html/downloads.shtml) | 癫痫类别 | 分类 | 心电图 | 发作数 2377 | 癫痫发作类别 | edf | can be used for both research and commercialization purposes |

![EEG](https://isip.piconepress.com/images/bootstrap/tuh_eeg/prod/tuh_eeg_signal_long.jpg)

[//]: # (TODO: Aistudio下载)

# Ultrasound Imaging

## Fetal head
| 名称 | 标注内容 | 类型 | 模态 | 数量 | 标签格式 | 文件格式 | License |
| - | - | - | - | - | - | - | - |
| [HC18](https://hc18.grand-challenge.org/) | 胎儿头围 | 分割 | 超声图 | 训练集 999 | 胎儿头围数值，胎儿头围形状（椭圆） | png | Creative Commons Attribution 4.0 International|

![HC18](static/hc18.jpeg)



# 医学影像数据库

[TCIA](https://www.cancerimagingarchive.net/):The Cancer Imaging Archive

[MedPix](https://medpix.nlm.nih.gov/home) 包含超过12000名患者和59000张影像

[Belarus tuberculosis portal](http://tuberculosis.by/) 包含结核病人的CT，胸透和检验数据

[Grand Challenges](https://grand-challenge.org/)

[LONI](https://ida.loni.usc.edu/login.jsp) 神经相关医学影像

[TUH EEG](https://isip.piconepress.com/projects/tuh_eeg/html/downloads.shtml) Temple大学脑电波公开数据库，包含超过4T数据

# 参考项目/列表

[医学影像分割挑战](http://medicaldecathlon.com/)

[胸部\肺部ct数据集](https://aistudio.baidu.com/aistudio/projectdetail/431782)

[//]: # (TODO: https://github.com/Awesome-Image-Registration-Organization/awesome-image-registration#21-datasets 配准)

[//]: # (TODO: )
[adalca](https://github.com/adalca/medical-datasets)

[//]: # (TODO: )
[beamandrew](https://github.com/beamandrew/medical-data)

[//]: # (TODO: )
[Stanford ML Group](https://stanfordmlgroup.github.io/)

[//]: # (TODO: )
[omic tools](https://omictools.com/)

[//]: # (TODO: )
[各领域公开数据集](https://zhuanlan.zhihu.com/p/25138563)

[//]: # (TODO: )
[medical-imaging-datasets](https://github.com/sfikas/medical-imaging-datasets)

[//]: # (TODO: )
[Open-Access Medical Image Repositories](http://www.aylward.org/notes/open-access-medical-image-repositories)

[//]: # (TODO: )
[Medical Image Datasets Download Links](https://www.ilovephd.com/medical-image-datasets-download-links/)

[//]: # (TODO: )
[HAM10000 dataset](https://dataverse.harvard.edu/dataset.xhtml?persistentId=doi:10.7910/DVN/DBW86T)

[//]: # (TODO: )
[Dermatology Image Classification](https://www.kaggle.com/yuningalexliu/dermatology-image-classification)

[//]: # (TODO: )
[havard](https://library.med.utah.edu/kw/derm/)

[//]: # (TODO: )
[usc](http://sipi.usc.edu/database/)

[//]: # (TODO: )
[burkely](https://www2.eecs.berkeley.edu/Research/Projects/CS/vision/bsds/)

[//]: # (TODO: )
[isdis](https://isdis.net/)

[//]: # (TODO: )
[radiopedia](https://radiopaedia.org/articles/imaging-data-sets-artificial-intelligence)

[//]: # (TODO: )
[aimi](https://aimi.stanford.edu/research/public-datasets)

[//]: # (TODO: https://zhuanlan.zhihu.com/p/24634505 )


[//]: # (TODO: https://isip.piconepress.com/projects/tuh_eeg/html/downloads.shtml)




