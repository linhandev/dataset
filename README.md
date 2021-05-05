# 医学影像数据集集锦
# 前言
本项目的目标是整理一个医学影像方向数据集的列表，提供每个数据集的基本信息，并对其中License允许的提供**不限速下载**。项目按照数据集关注的器官对其进行分类。需要整理的数据集很多，我们十分期待大佬们为项目**作出贡献**。

- 如果您发现项目已有的内容中有任何错误（包括但不限于md格式问题，网址失效，数据错误，简介信息补充等），可以通过Pull/Request进行修正。
- 如果您想用的数据集没有出现在列表中，请按照模板[提交Issue](https://github.com/linhandev/dataset/issues/new?assignees=linhandev&labels=%E6%96%B0%E5%A2%9E%E6%95%B0%E6%8D%AE%E9%9B%86&template=-----.md&title=%5B%E6%96%B0%E5%A2%9E%5D+%E6%B7%BB%E5%8A%A0%E6%96%B0%E6%95%B0%E6%8D%AE%E9%9B%86%E3%80%80xx)，并尽量详细地描述数据集信息。我们会尽快添加，若License允许可以**免费代下**。

当前共收录约 20 个方向的 70+ 个数据集

目录
=================
* [肝脏](#肝脏)
   * [LiTS](#lits)
   * [Sliver07](#sliver07)
   * [3D-IRCADB](#3d-ircadb)
   * [CHAOS](#chaos)
   * [TCGA-LIHC](#tcga-lihc)
   * [MSD肝脏血管分割](#msd肝脏血管分割)
* [肺](#肺)
   * [MSD肺脏分割](#msd肺脏分割)
   * [LoLa11肺页分割](#lola11肺页分割)
   * [StructSeg2019](#structseg2019)
   * [肺部多病智能诊断](#肺部多病智能诊断)
   * [CheXpert](#chexpert)
   * [NIHChest Xray](#nihchest-xray)
   * [QIN Lung CT](#qin-lung-ct)
   * [4D-Lung](#4d-lung)
   * [NSCLC-Radiomics](#nsclc-radiomics)
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
* [乳腺癌](#乳腺癌)
   * [CBIS-DDSM](#cbis-ddsm)
   * [QIN Breast](#qin-breast)
   * [Rider Breast MRI](#rider-breast-mri)
   * [ACRIN 6688](#acrin-6688)
   * [BraTS2015](#brats2015)
* [脑](#脑)
   * [MSD脑瘤分割](#msd脑瘤分割)
   * [MSD海马体分割](#msd海马体分割)
   * [Iseg2019](#iseg2019)
   * [ABIDE](#abide)
   * [ADNI](#adni)
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
* [眼睛](#眼睛)
   * [DRIVE](#drive)
   * [ODIR-5k](#odir-5k)
   * [FIRE 视网膜图像数据](#fire-视网膜图像数据)
   * [STARE](#stare)
   * [CHASE_DB1](#chase_db1)
* [细胞](#细胞)
   * [Data Science Bowl 18](#data-science-bowl-18)
   * [血细胞涂片分类](#血细胞涂片分类)
   * [ISBI细胞跟踪](#isbi细胞跟踪)
* [骨骼](#骨骼)
   * [MURA-1.1](#mura-11)
   * [RSNA Bone Age](#rsna-bone-age)
   * [膝盖](#膝盖)
      * [MRNet](#mrnet)
   * [脊椎](#脊椎)
      * [Verse大规模脊椎分割数据集](#verse大规模脊椎分割数据集)
* [前列腺](#前列腺)
   * [PANDA](#panda)
   * [MSD前列腺分割](#msd前列腺分割)
   * [QIN-PROSTATE-Repeatability](#qin-prostate-repeatability)
* [胰腺](#胰腺)
   * [MSD胰腺分割](#msd胰腺分割)
   * [PDMR-833975-119-R](#pdmr-833975-119-r)
* [皮肤](#皮肤)
   * [SIIM-ISIC Melanoma Classification](#siim-isic-melanoma-classification)
* [VQA](#vqa)
   * [PathVQA](#pathvqa)
* [医学影像数据库](#医学影像数据库)
* [参考项目/列表](#参考项目列表)
* [贡献者](#贡献者)
* [Release Note](#release-note)


# 肝脏

## LiTS
[//]: # (FIN)

| 名称 | 标注内容 | 类型 | 模态 | 数量 | 标签格式 | 文件格式 | License |
| - | - | - | - | - | - | - | - |
| [LiTS](https://competitions.codalab.org/competitions/17094) | 肝脏/肝脏肿瘤 | 分割 | CT   | 131+70 | 0/1标签  | nii | [CC 4.0](https://competitions.codalab.org/competitions/17094#learn_the_details-terms_and_conditions) |

<img src="./static/lits.jpg" width="50%"/>

LiTS数据集包含131套训练扫描和70组测试数据，其中70组测试数据标签不公开。LiTS训练集中包含3DIRCADB中的所有数据，所以如果合并多个数据集不要合并这两个。Medical Segmentation Decathlon中肝脏分割的数据集就是LiTS。

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
| 3D-IRCADb [01](https://www.ircad.fr/research/3d-ircadb-01/) [02](https://www.ircad.fr/research/3d-ircadb-01/) | 肝脏/肝肿瘤 | 分割 | CT   | 20+2 | surface mesh | dcm | CC |

<img src="./static/3Dircadb.jpg" width="80%"/>


3D-IRCADb是比较早的一个数据集，有两个子集，分别包含20组和2组CT片子。

[Aistudio下载](https://aistudio.baidu.com/aistudio/datasetdetail/10293)

## CHAOS
[//]: # (FIN)

| 名称 | 标注内容 | 类型 | 模态 | 数量 | 标签格式 | 文件格式 | License |
| - | - | - | - | - | - | - | - |
| [CHAOS](https://chaos.grand-challenge.org/) | 肝/肾/脾 | 分割 | CT+MRI | 40CT+120MRI | 0/1标签  | dcm | [CC 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/legalcode) |

CHAOS是一个多脏器，多模态分割数据集。

![CHAOS](./static/chaos.png)

[Aistudio下载](https://aistudio.baidu.com/aistudio/datasetdetail/23864)

## TCGA-LIHC
[//]: # (FIN)

| 名称 | 标注内容 | 类型 | 模态 | 数量 | 标签格式 | 文件格式 | License |
| - | - | - | - | - | - | - | - |
| [TCGA-LIHC](https://wiki.cancerimagingarchive.net/display/Public/TCGA-LIHC) | 肝 |  | CT/MR/PT | 97患者/237套 | 无标签   | dcm | [Other](https://wiki.cancerimagingarchive.net/display/Public/Data+Usage+Policies+and+Restrictions) |

![tcga-lihc](./static/tcga-lihc.jpg)

[Aistudio下载](https://aistudio.baidu.com/aistudio/datasetdetail/37439)

## MSD肝脏血管分割

| 名称 | 标注内容 | 类型 | 模态 | 数量 | 标签格式 | 文件格式 | License |
| - | - | - | - | - | - | - | - |
| [MSD肝脏血管分割](http://medicaldecathlon.com/) | 肝脏血管 | 分割 | CT | 443 | 0/1 | nii | [CC-BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/) |

![hepatic-Vessels](./static/Hepatic-Vessels.png)

[Aistudio下载](https://aistudio.baidu.com/aistudio/datasetdetail/10333)

# 肺
## MSD肺脏分割

| 名称 | 标注内容 | 类型 | 模态 | 数量 | 标签格式 | 文件格式  | License |
| - | - | - | - | - | - | - | - |
| [MSD肺脏分割](http://medicaldecathlon.com/) | 肺脏 | 分割 | CT | 96 | 0/1 | nii | [CC-BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/) |

![Lung-Tumours](./static/Lung-Tumours.png)

[Aistudio下载](https://aistudio.baidu.com/aistudio/datasetdetail/10334)

## LoLa11肺页分割

[//]: # (FIN)

| 名称 | 标注内容    | 类型 | 模态 | 数量 | 标签格式 | 文件格式  | License |
| - | - | - | - | - | - | - | - |
| [LoLa11](https://lola11.grand-challenge.org/) | 左右肺/肺页 | 分割 | CT   | 55 | 0/1标签  | Metaimage | [Other](https://zenodo.org/record/4708800) |

![lola11](https://grand-challenge-public.s3.amazonaws.com/f/challenge/39/c4ab1b11-3338-4b99-a732-174ddc9e3b70/lola11_web.png)

55组扫描的肺页分割，包含左右肺，左上，左下，右上，右中，右下肺页的标注。

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

| 名称 | 标注内容 | 类型 | 模态 | 数量 | 标签格式 | 文件格式 |
| - | - | - | - | - | - | - |
| [CheXpert](https://stanfordmlgroup.github.io/competitions/chexpert/) |  |      |      |      |          |          |

![chestxpert](./static/chest-x-pert.png)

介绍论文： [CheXpert: A Large Chest Radiograph Dataset with Uncertainty Labels and Expert Comparison](https://arxiv.org/abs/1901.07031)

[相关项目](https://github.com/gaetandi/cheXpert)

## NIHChest Xray

| 名称 | 标注内容 | 类型 | 模态 | 数量 | 标签格式 | 文件格式 | License |
| - | - | - | - | - | - | - | - |
| [NIHChest Xray](https://www.kaggle.com/nih-chest-xrays/data) |  |      |      |          |  | CC0: Public Domain | | |

介绍论文： [ChestX-ray8: Hospital-scale Chest X-ray Database and Benchmarks on Weakly-Supervised Classification and Localization of Common Thorax Diseases](http://openaccess.thecvf.com/content_cvpr_2017/papers/Wang_ChestX-ray8_Hospital-Scale_Chest_CVPR_2017_paper.pdf)

[Aistudio下载](https://aistudio.baidu.com/aistudio/datasetdetail/35660)

## QIN Lung CT

| 名称 | 标注内容 | 类型 | 模态 | 数量 | 标签格式 | 文件格式 |
| - | - | - | - | - | - | - |
| [QIN Lung CT](https://wiki.cancerimagingarchive.net/display/Public/QIN+LUNG+CT) |          |      | CT   |      |          |          |

[Aistudio下载](https://aistudio.baidu.com/aistudio/datasetdetail/35205)

## 4D-Lung

| 名称 | 标注内容 | 类型 | 模态 | 数量 | 标签格式 | 文件格式 |
| - | - | - | - | - | - | - |
| [4D-Lung](https://wiki.cancerimagingarchive.net/display/Public/4D-Lung) |          |      |      |      |          |          |

[Aistudio下载](https://aistudio.baidu.com/aistudio/datasetdetail/37482)

## NSCLC-Radiomics

| 名称 | 标注内容 | 类型 | 模态 | 数量 | 标签格式 | 文件格式 |
| - | - | - | - | - | - | - |
| [NSCLC-Radiomics](https://wiki.cancerimagingarchive.net/display/Public/NSCLC-Radiomics) | 非小细胞癌　| 分割　|　CT | 422 |          | dcm |

![NSCLC-Radiomics](./static/NSCLC-Radiomics.png)

[Aistudio下载](https://aistudio.baidu.com/aistudio/datasetdetail/63958)

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

| 名称 | 标注内容 | 类型 | 模态 | 数量 | 标签格式 | 文件格式 |
| - | - | - | - | - | - | - |
| [RSNA肺炎检测](https://www.kaggle.com/c/rsna-pneumonia-detection-challenge/) | 之否肺炎/肺炎区域BB | 分类/检测 | CXR  | 26684+3000 |          | 图片     |

RSNA是北美放射学会在Kaggle上组织的一个比赛数据集，数据来自[NIH](https://nihcc.app.box.com/v/ChestXray-NIHCC)。包含26684张训练数据，有图片的分类和肺炎区域的边界框。

[Aistudio下载](https://aistudio.baidu.com/aistudio/datasetdetail/34214)

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

| 名称 | 标注内容 | 类型 | 模态 | 数量  | 标签格式 | 文件格式 |
| - | - | - | - | - | - | - |
| [CT Images in COVID-19](https://wiki.cancerimagingarchive.net/display/Public/CT+Images+in+COVID-19) | 无标签 | 分类/分割 | CT   | 650 | 无 | nii|

[Aistudio下载](https://aistudio.baidu.com/aistudio/datasetdetail/63794)

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
| [天池肺部结节](https://tianchi.aliyun.com/competition/entrance/231601/introduction) |          |      |      |      |          |          | [Custom](https://tianchi.aliyun.com/competition/entrance/231601/introduction) |

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

![Lung-PET-CT-Dx](./static/Lung-PET-CT-Dx.png)

## 气胸

### SIIM-ACR Pneumothorax Segmentation

| 名称      | 标注内容 | 类型 | 模态 | 数量 | 标签格式 | 文件格式 |
| - | - | - | - | - | - | - |
| [SIIM-ACR Pneumothorax Segmentation](https://www.kaggle.com/c/siim-acr-pneumothorax-segmentation) |   |   |    |   |   |  |

# 乳腺癌

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

## BraTS2015

| 名称 | 标注内容 | 类型 | 模态 | 数量 | 标签格式 | 文件格式 |
| - | - | - | - | - | - | - |
| [BraTS2015](http://www.braintumorsegmentation.org/) |          |      |      |      |          |          |

[Aistudio下载](https://aistudio.baidu.com/aistudio/datasetdetail/26367)

# 脑

## MSD脑瘤分割

| 名称 | 标注内容 | 类型 | 模态 | 数量 | 标签格式 | 文件格式 | License |
| - | - | - | - | - | - | - | - |
| [MSD Brain Tumor Segmentation](http://medicaldecathlon.com/) | 胶质瘤/肿瘤/水肿 | 分割 | MRI | 484 Train + 266 Test | 0/1 | nii | [CC-BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/) |

![msd-brain](./static/msd-brain-tumor.png)

[Aistudio下载](https://aistudio.baidu.com/aistudio/datasetdetail/10277)


## MSD海马体分割

| 名称 | 标注内容 | 类型 | 模态 | 数量 | 标签格式 | 文件格式 | License |
| - | - | - | - | - | - | - | - |
| [MSD Hippocampus Segmentation](http://medicaldecathlon.com/) | 海马体 | 分割 | MRI | 394 | 0/1 | nii | [CC-BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/) |

![msd-hippocampus](./static/msd-hippocampus.png)

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


## 脑出血

### RSNA Intracranial Hemorrhage Detection

| 名称 | 标注内容 | 类型 | 模态 | 数量 | 标签格式 | 文件格式 |
| - | - | - | - | - | - | - |
| [RSNA Intracranial Hemorrhage Detection](https://www.kaggle.com/c/rsna-intracranial-hemorrhage-detection) |          |      | CT   |      |          |          |

[Aistudio下载](https://aistudio.baidu.com/aistudio/datasetdetail/35741)

# 肾脏

## Kits19

| 名称 | 标注内容 | 类型 | 模态 | 数量 | 标签格式 | 文件格式 | License |
| - | - | - | - | - | - | - | - |
| [Kits19](https://kits19.grand-challenge.org/) | 肾脏/肾肿瘤 | 分割 |  | | | | |

![kits19](./static/kits19.png)

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
| [MSD肠道分割数据集](http://medicaldecathlon.com/) |          |      |      |      |          |          | [CC-BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/) |

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
| [MMWHS](https://zmiclab.github.io/projects/mmwhs/) | 心脏     | 分割 | CT / MRI | 20CT、20MRI | 类别     | nii      |

mmwhs是心脏分割数据集，共有8类，MRI和CT两种模态  相关项目： [Hybrid Loss Guided Convolutional Networks for Whole Heart Parsing](https://github.com/xy0806/miccai17-mmwhs-hybrid)

[Aistudio下载](https://aistudio.baidu.com/aistudio/datasetdetail/38799)

## MSD心脏分割

| 名称 | 标注内容 | 类型 | 模态 | 数量 | 标签格式 | 文件格式 | License |
| - | - | - | - | - | - | - | - |
| [MSD心脏分割](http://medicaldecathlon.com/) |          |      |      |      |          |          | [CC-BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/) |

[Aistudio下载](https://aistudio.baidu.com/aistudio/datasetdetail/23911)

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

![stare](./static/stare.png)

STructured Analysis of the Retina数据集包含400张眼底照片，作者团队对这些数据进行了多种诊断，并对部分数据的血管进行了标注

[Aistudio下载](https://aistudio.baidu.com/aistudio/datasetdetail/81241)


## CHASE_DB1

| 名称 | 标注内容 | 类型 | 模态 | 数量 | 标签格式 | 文件格式 | License |
| - | - | - | - | - | - | - | - |
| [CHASE_DB1](https://blogs.kingston.ac.uk/retinal/) | 眼底血管 | 分割 | 眼底照片 | 28 | png | png | 无 |

![CHASE_DB1](./static/CHASE_DB1.png)

Kinston大学公开的一个小规模眼底分割数据集，包含28张眼底照片及对应的分割标签。

[Aistudio下载](https://aistudio.baidu.com/aistudio/datasetdetail/81247)


# 细胞

## Data Science Bowl 18

| 名称 | 标注内容 | 类型 | 模态 | 数量 | 标签格式 | 文件格式 |
| - | - | - | - | - | - | - |
| [Data Science Bowl 18](https://www.kaggle.com/c/data-science-bowl-2018) | 细胞核   | 分割 |      | 841张/37333个细胞核 | 0/1      | 图片     |

细胞核分割数据集

介绍论文： [Nucleus segmentation across imaging experiments: the 2018 Data Science Bowl](https://www.ncbi.nlm.nih.gov/pubmed/31636459)

[Aistudio下载](https://aistudio.baidu.com/aistudio/datasetdetail/10292)

## 血细胞涂片分类

| 名称 | 标注内容 | 类型 | 模态 | 数量 | 标签格式 | 文件格式 |
| - | - | - | - | - | - | - |
| [血细胞涂片分类](https://www.kaggle.com/paultimothymooney/blood-cells) | 四种血细胞类型 | 分类 | 镜检 | 12500 | -        | 图片     |

血细胞分类数据集包含12500张四种血细胞的照片。图片是从大的血细胞涂片照片上截下来的，数据集经过增广。图片都很小，训练时注意IO瓶颈。

[Aistudio下载](https://aistudio.baidu.com/aistudio/datasetdetail/10278)

## ISBI细胞跟踪

| 名称 | 标注内容 | 类型 | 模态 | 数量 | 标签格式 | 文件格式 |
| - | - | - | - | - | - | - |
| [ISBI细胞跟踪](http://celltrackingchallenge.net/) | 细胞像素级别位置 | 跟踪 | 镜检 |      |          | 图片     |

在镜检视频中像素级跟踪细胞位置

Aistudio下载 [2D+Time Datasets](https://aistudio.baidu.com/aistudio/datasetdetail/78515)

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

<img src="./static/verse.png" width="50%"/>

[Aistudio下载](https://aistudio.baidu.com/aistudio/datasetdetail/86496)


# 前列腺

## PANDA

| 名称 | 标注内容 | 类型 | 模态 | 数量 | 标签格式 | 文件格式 |
| - | - | - | - | - | - | - |
| [PANDA](https://www.kaggle.com/c/prostate-cancer-grade-assessment/overview) | 前列腺癌分级 |      | 镜检图片 | 10616张镜检 | 分类     | tiff     |


## MSD前列腺分割

| 名称 | 标注内容 | 类型 | 模态 | 数量 | 标签格式 | 文件格式 | License |
| - | - | - | - | - | - | - | - |
| [MSD前列腺分割](http://medicaldecathlon.com/) |          |      |      |      |          |          | [CC-BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/) |

[Aistudio下载](https://aistudio.baidu.com/aistudio/datasetdetail/23912)

## QIN-PROSTATE-Repeatability

| 名称 | 标注内容 | 类型 | 模态 | 数量 | 标签格式 | 文件格式 |
| - | - | - | - | - | - | - |
| [QIN-PROSTATE-Repeatability](https://wiki.cancerimagingarchive.net/display/Public/QIN-PROSTATE-Repeatability) | 前列腺癌　|  | MRI | 15 |　　| dcm |

![QIN-Prostate-Repeatability](./static/QIN-Prostate-Repeatability.png)

[Aistudio下载](https://aistudio.baidu.com/aistudio/datasetdetail/63950)

# 胰腺

## MSD胰腺分割

| 名称 | 标注内容 | 类型 | 模态 | 数量 | 标签格式 | 文件格式 | License |
| - | - | - | - | - | - | - | - |
| [MSD胰腺分割](http://medicaldecathlon.com/) |      |      |      |   |     |     | [CC-BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/) |

[Aistudio下载](https://aistudio.baidu.com/aistudio/datasetdetail/23914)

## PDMR-833975-119-R

| 名称 | 标注内容 | 类型 | 模态 | 数量 | 标签格式 | 文件格式 |
| - | - | - | - | - | - | - |
| [PDMR-833975-119-R](https://wiki.cancerimagingarchive.net/display/Public/Imaging+tissue+characterization+of+a+patient+derived+xenograft+model+of+adenocarcinoma+pancreas%3A+PDMR-833975-119-R) |　胰腺癌　|      |　MRI | 20 | | dcm |

![PDMR-833975-119-R](./static/PDMR-833975-119-R.png)

[Aistudio下载](https://aistudio.baidu.com/aistudio/datasetdetail/64052)

# 皮肤

## SIIM-ISIC Melanoma Classification

| 名称 | 标注内容 | 类型 | 模态 | 数量 | 标签格式 | 文件格式 |
| - | - | - | - | - | - | - |
| [SIIM-ISIC Melanoma Classification](https://www.kaggle.com/c/siim-isic-melanoma-classification/data) | 皮肤癌病变类别 | 分类 | 皮肤镜 | 88.3K张图片 | 类别     | dicom   |

目前最大的皮肤镜图像集合，用来在皮肤病变图像中之别黑色素瘤，图片以DICOM格式提供，同时包含图像元数据，有的图像也以JPEG和TFRecord格式提供，TFRecords格式的图像已被调整为统一的1024x1024

[//]: # (TODO: 添加这个数据集的下载)

# VQA

## PathVQA

| 名称 | 标注内容 | 类型 | 模态 | 数量 | 标签格式 | 文件格式 |
| - | - | - | - | - | - | - |
| [PathVQA](https://pathvqachallenge.grand-challenge.org/PathVQA_challenge/) |          |      | 图片 | 4998图片/32799问答 |          | 图片     |

介绍论文： [PathVQA: 30000+ Questions for Medical Visual Question Answering](https://arxiv.org/abs/2003.10286)

[Aistudio下载](https://aistudio.baidu.com/aistudio/datasetdetail/25239)


# 医学影像数据库

[TCIA](https://www.cancerimagingarchive.net/):The Cancer Imaging Archive

[MedPix](https://medpix.nlm.nih.gov/home) 包含超过12000名患者和59000张影像

[Belarus tuberculosis portal](http://tuberculosis.by/) 包含结核病人的CT，胸透和检验数据

[Grand Challenges](https://grand-challenge.org/)

[LONI](https://ida.loni.usc.edu/login.jsp) 神经相关医学影像

# 参考项目/列表

[胸部\肺部ct数据集](https://aistudio.baidu.com/aistudio/projectdetail/431782)

[医学影像分割挑战](http://medicaldecathlon.com/)

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



# 贡献者

（按照首次贡献时间排序）

[多语言代码生成器](https://aistudio.baidu.com/aistudio/personalcenter/thirdview/33061) Mail : linhandev@qq.com

[自尊心3](https://aistudio.baidu.com/aistudio/personalcenter/thirdview/218586)

[底迪](https://aistudio.baidu.com/aistudio/personalcenter/thirdview/31756)

[ChenchenHu007](https://github.com/ChenchenHu007)

# Release Note

2020/11/20<br>添加Issue模板，鼓励外部贡献，数据集数量达到67

2020/11/8<br>在Github发布，整理格式，添加多个数据集

2020/6/11<br>添加LIDC-IDIR，编写数据压缩脚本

2020/6/4<br>添加MMWHS心脏分割数据集，SIIM皮肤病分类比赛数据集

2020/5/27<br>添加ISBI细胞分割，TCGA-LIHC肝脏，4D-Lung肺部数据集，围绕乳腺癌添加一系列数据集

2020/5/20<br>项目添加数据集计数和release note，数据集方面添加 RSNA骨龄，PathVQA，FIRE视网膜，DDSM乳腺癌等数据集

2020/5/13<br>项目在Aistudio公开，包含约40个数据集

[//]: # (TODO: 做一个tcia转nii的py程序)
[//]: # (TODO: 图片一样的大小,居中)
