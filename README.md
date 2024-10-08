# NER-中文人名库

最近更新日期：2024-09-04

## 项目概述

命名实体识别（NER）是自然语言处理（NLP）领域的一项核心技术，作为信息抽取的基础，NER能够准确识别并分类文本中的关键实体，如人名、地名、组织机构名等，为高级NLP任务如关系抽取、问答系统提供有力支撑。特别是在人机交互和智能服务领域，NER通过精准识别用户输入中的命名实体，使得系统能够更准确地理解用户需求，提供个性化的服务体验。所以说人名数据集在NER模型性能评估环节处于不可或缺的地位,其数据质量和注释质量对于评判模型性能起着非常重要的作用。然而，目前仍缺乏公开、高质量且超大规模的中文人名数据集，这严重制约了相关研究和应用的深入发展。为了填补这一空白，我们精心收集来自互联网的数亿的人名数据并进行数据校正、文本规范化、去重等处理，开源成千万级大型人名词语料库，以满足学术研究和商业开发的需求。
<br> 
本项目开源的千万级大型中文人名库，将为NLP领域的分词、NER、情感分析、知识图谱构建等子任务提供丰富且高质量的训练与评估数据，助力算法优化与模型性能提升。我们期望通过提供标准化的数据资源，降低科研与产业之间的数据壁垒，促进学术研究成果向实际应用的转化，加速AI技术在智能机器人、人机交互等领域的创新应用。在智能机器人领域，精准的人名识别与处理是实现高效、自然人机交互的基础。我们也期待本项目的人名库助力智能机器人更好地理解用户意图，提升交互体验。

### 数据集特点：

**数据量大**：收集自互联网的数亿级人名数据，经过精心筛选与处理，最终开源成千万级大型语料库。
<br> 
**质量高**：采用先进的数据校正、文本规范化、去重等技术手段，确保数据集的准确性和可靠性。
<br> 
**标准化**：遵循统一的标注规范与数据格式，便于不同研究团队之间的数据共享与比较。
<br> 
**多样化**：涵盖不同年代、性别、地域、职业等背景的人名，满足多样化研究需求。

## 项目内容

### 文件目录

本项目目录分类如下：
     
* [中文人名库](/Chinese-Person-Names) 

     &emsp;&emsp;  [超大样本中文人名_nh](Chinese-Person-Names/Chinese-Person-Names_Big-Data_nh.txt)
     <br> 
     &emsp;&emsp;  [汉族中文人名_nhh](Chinese-Person-Names/Chinese-Person-Names_Han_nhh.txt)
     <br> 
     &emsp;&emsp;  [大样本中文人名_nh](Chinese-Person-Names/Chinese-Person-Names_Large_nh.txt)
     <br> 
     &emsp;&emsp;  [互联网中文人名_nh](Chinese-Person-Names/Chinese-Person-Names_Web_nh.txt)
     
* [词性标准](/POS_Standards)

     &emsp;&emsp;  [词性标准.pdf](POS_Standards/POS_Standards.pdf)
     <br> 
     &emsp;&emsp;  [词性标准.png](POS_Standards/POS_Standards.png)
     <br> 
  
### 文件编码格式

文件格式：本词库以纯文本文件（.txt）的形式提供，每行包含一个人名词汇。
<br> 
编码方式：采用UTF-8编码，确保支持多语言字符（尽管本词库主要关注中文人名）。
<br> 
无额外标注：当前版本的人名词库未包含额外的标注信息，如词性等，但未来版本可能会考虑添加。
<br> 
注：文件名后缀若加带词性,如_nh，表示整个文档所有词汇词性均为_nh。

### 词性标准解释

本项目词性解释参考自《信息处理用现代汉语词类标记规范》与《信息处理用现代汉语分词规范》。
                                                                                        
| 序号 |符号 | 定义 |
|:--:| :--: | :--:|
| 1 | nh | 表示人的名称的专有名词 |
| 2 | nhh | 表示汉族人的名称的专有名词 |

### 词量大小

| 序号 |名称 | 容量 |
|:--:| :--: | :--:|    
| 1  | 超大样本中文人名_nh|16689250|                                                                                   
| 2  | 汉族中文人名_nhh |937472|
| 3  | 大样本中文人名_nh  |937648|
| 4  | 互联网中文人名_nh |917426|


### 文件数据示例

超大样本中文人名_nh.txt

```
蔚承清   
董祥圣  
葛祥甫
```

## 版权和许可

本项目面向国内外大学、研究所、企业、机构以及个人免费开放，可用于研究与商业。
<br> 
欢迎对该开源项目提出任何宝贵意见和建议。请发邮件至botx@botxfoundry.com。
<br> 
本项目的授权协议为 **Apache License 2.0**。您可以自由地使用、复制、修改和分发本项目，但需遵守许可证中的规定。
<br>

## 发布者简介

湖南灵牛机器人科技有限公司       &emsp;&emsp;  Web:  http://www.botxfoundry.com

湖南灵牛机器人科技有限公司作为领先的商用级智能机器人平台底座提供商，致力于为客户提供领先的智能机器人通用平台产品及技术服务，以“F（平台底座）+X（创新场景）”模式赋能数字化转型。
<br> 
公司主营产品包括机器人通用移动平台（线控底盘）、机器人通用关键基础部件、机器人智慧云端大脑三大板块，构建以 ABCDE 五维基础要素能力为核心的智能机器人平台底座闭环产品技术体系，即 AI（人工智能机器人智慧云端大脑）、Bot（机器人通用线控底盘）、Contol（机器人核心控制部件）、Drive（机器人电源驱动部件）、Edge(机器人通用边缘计算平台)。公司在室内外全场景通用移动底盘、机器人高精伺服控制、多模融合高精定位导航、元宇宙空间计算、大模型与智能人机对话、一体化大模型开发及训练、机器人自动驾驶等方面有拥有核心技术。
 
作为一家专注于机器人领域的科技公司，我们深知数据对于AI技术发展的重要性。因此，我们将持续投入资源，不断优化和完善本项目，同时探索更多创新的应用场景，为AI技术、智能机器人人机交互的发展贡献更多力量。我们期待与全球科研工作者和产业界同仁携手合作，共同推动人工智能技术的繁荣与发展。


