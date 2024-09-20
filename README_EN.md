# BX-Chinese-Person-Names

Last Updated On：2024-09-04

## Overview

Named Entity Recognition (NER) is a core technology in the field of Natural Language Processing (NLP). As the foundation of information extraction, NER can accurately identify and classify key entities in text, such as person names, place names, and organization names, providing strong support for advanced NLP tasks such as relation extraction and question answering systems. Especially in the fields of human-computer interaction and intelligent services, NER enables systems to more accurately understand user needs by precisely identifying named entities in user inputs, providing a personalized service experience. Therefore, person name datasets play an indispensable role in the performance evaluation of NER models, and their data quality and annotation quality are crucial for assessing model performance. However, there is still a lack of publicly available, high-quality, and ultra-large-scale Chinese person name datasets, which severely restricts the in-depth development of related research and applications. To fill this gap, we have meticulously collected hundreds of millions of person name data from the internet and subjected them to rigorous processes including data correction, text normalization, and deduplication, ultimately open-sourcing a tens of millions of large-scale Chinese person name corpus to cater to the needs of academic research and commercial development.

This open-sourced ten-million-scale Chinese name corpus will enrich and provide high-quality training and evaluation data for subtasks in the NLP field, such as word segmentation, named entity recognition, sentiment analysis, and knowledge graph construction, thereby contributing to algorithm optimization and model performance enhancement. We aspire to lower the data barriers between research and industry by providing standardized data resources, promote the translation of academic research achievements into practical applications, and accelerate the innovative application of AI technologies in fields like intelligent robots and human-computer interaction. In the realm of intelligent robots, precise person name recognition and processing form the foundation for efficient and natural human-computer interaction. We also anticipate that our name corpus will empower intelligent robots with a better understanding of user intentions and elevate the interactive experience.


### Dataset Characteristics:
**Large Scale**: Comprising hundreds of millions of name data collected from the internet, the dataset has been meticulously screened and processed, ultimately open-sourced as a ten-million-scale large corpus.
<br> 
**High Quality**: Advanced techniques such as data correction, text normalization, and deduplication have been employed to ensure the accuracy and reliability of the dataset.
<br> 
**Standardized**: Adhering to a unified annotation standard and data format, it facilitates data sharing and comparison among different research teams.
<br> 
**Diverse**: Encompassing names from various backgrounds, including different eras, genders, regions, and occupations, it caters to a wide range of research needs.
<br> 

## Project Overview
### Directory

The directory classification for this project is as follows:

* [Chinese-Person-Names](/Chinese-Person-Names) 

     &emsp;&emsp;  [Chinese-Person-Names_Big-Data_nh](Chinese-Person-Names/Chinese-Person-Names_Big-Data_nh.txt)
     <br> 
     &emsp;&emsp;  [Chinese-Person-Names_Han_nhh](Chinese-Person-Names/Chinese-Person-Names_Han_nhh.txt)
     <br> 
     &emsp;&emsp;  [Chinese-Person-Names_Large_nh](Chinese-Person-Names/Chinese-Person-Names_Large_nh.txt)
     <br> 
     &emsp;&emsp;  [Chinese-Person-Names_Web_nh](Chinese-Person-Names/Chinese-Person-Names_Web_nh.txt)
    
  
     
* [POS standards](/POS_standards)

     &emsp;&emsp;  [POS standards.pdf](POS_standard/POS_standard.pdf)
     <br> 
     &emsp;&emsp;  [POS standards.png](POS_standard/POS_standard.png)
     <br> 
     
### File Encoding Format

File Format: The vocabulary bank is provided in the form of plain text files (.txt), with each line containing a single personal name vocabulary.
<br> 
Encoding Method: It employs UTF-8 encoding to ensure support for multilingual characters (though the primary focus of this vocabulary bank is on Chinese person names).
<br> 
No Additional Annotations: The current version of the personal name vocabulary bank does not include additional annotation information, such as part of speech, but future versions may consider adding them.
<br> 
Note: the remaining part of the "Note" section was cut off in the original request, but if there's more content to be
<br> 

### Part-Of-Speech tagging (POS) Standards
                                                                                        
| Number |Signal | Definition |
|:--:| :--: | :--:|
| 1 | nh | proper nouns referring to people's names |
| 2| nhh | proper nouns referring to Han people's names |

### Size of the data sample

|   Number  |   Name   |   Size of Names  |
|:--:| :--: | :--:|           
| 1  | Chinese-Person-Name_Big-Data_nh |16689250|                                                                          
| 2  | Chinese-Person-Names_Han_nhh |937472|
| 3  | Chinese-Person-Names_Large_nh |937648|
| 4  | Chinese-Person-Names_Web_nh |917426|

### Data Example
Chinese-Person-Name_Big-Data_nh.txt

```
蔚承清   
董祥圣  
葛祥甫
```

## License

This project is freely open to universities, research institutes, enterprises, organizations, and individuals both domestically and internationally, and can be used for research and commercial purposes.
<br>
We warmly welcome any valuable opinions and suggestions for this open-source project. Please send your emails to botx@botxfoundry.com.
<br>
The license agreement for this project is **Apache License 2.0**. You are free to use, copy, modify, and distribute this project, but you must comply with the provisions in the license.
<br>

## Publisher Introduction

BotXFoundry      &emsp;&emsp;   Web: http://www.botxfoundry.com

As a leading provider of commercial-grade intelligent robot platform solutions, BotX Foundry is dedicated to offering customers advanced intelligent robot universal platform products and technical services. It empowers digital transformation through its unique "F (Foundation) + X (Innovative Scenarios)" model.

The company's core products encompass three main sectors: universal mobile platforms for robots (tethered chassis), essential universal components for robots, and intelligent cloud-based robot brains. This forms a comprehensive and closed-loop product technology system centered around the five-dimensional ABCDE foundational capabilities: AI (Artificial Intelligence for Intelligent Cloud-Based Robot Brains), Bot (Universal Tethered Chassis for Robots), Control (Core Control Components for Robots), Drive (Power and Drive Components for Robots), and Edge (Universal Edge Computing Platforms for Robots).
<br> 
BotXFoundry boasts core technologies in various areas such as indoor and outdoor universal mobile chassis, high-precision servo control for robots, multi-modal and high-precision positioning and navigation, spatial computing for the Metaverse, large-scale models and intelligent human-machine interaction, integrated large-scale model development and training, and autonomous driving for robots.

As a tech company specializing in robotics, we are deeply aware of the significance of data in AI technology development. Consequently, we will continue to invest resources in optimizing and expanding this project while exploring more innovative application scenarios, thereby contributing further to the advancement of AI technology and human-computer interaction in intelligent robots. We look forward to collaborating with researchers and industry peers worldwide to jointly propel the prosperity and development of artificial intelligence technology.