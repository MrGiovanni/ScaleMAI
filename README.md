# ScaleMAI

<div align="center">
 
![logo](document/fig_scalemai_agent.jpg)
</div>
ScaleMAI is an AI-integrated data curation and annotation agent that combines iterative, multi-stage processes with AI and human expertise to progressively enhance dataset quality.

## Paper

<b>ScaleMAI: Accelerating the Development of Trusted Datasets and AI Models</b> <br/>
[Wenxuan Li](https://scholar.google.com/citations?hl=en&user=tpNZM2YAAAAJ), [Pedro R. A. S. Bassi](https://scholar.google.com/citations?user=NftgL6gAAAAJ), [Tianyu Lin](https://scholar.google.com/citations?user=eHJYs-IAAAAJ&hl=zh-CN), [Yu-Cheng Chou](https://scholar.google.com.tw/citations?user=YVNRBTcAAAAJ&hl), Xinze Zhou, [Yucheng Tang](https://scholar.google.com/citations?user=0xheliUAAAAJ&hl=en), [Fabian Isensee](https://scholar.google.com/citations?user=PjerEe4AAAAJ&hl=en), Kang Wang, [Qi Chen](https://scholar.google.com/citations?user=4Q5gs2MAAAAJ&hl=en), [Xiaowei Xu](https://scholar.google.com.hk/citations?user=1vVgUeQAAAAJ&hl=zh-CN), [Xiaoxi Chen](https://scholar.google.com/citations?user=FQ53_nAAAAAJ&hl=zh-CN), Lizhou Wu, [Qilong Wu](https://scholar.google.com/citations?user=xrWDBjcAAAAJ&hl=zh-CN), [Yannick Kirchhoff](https://scholar.google.de/citations?user=nfvjwmkAAAAJ&hl=de), [Maximilian Rokuss](https://scholar.google.de/citations?user=u2cX-YAAAAAJ&hl=de), [Saikat Roy](https://scholar.google.de/citations?user=dSs0DfoAAAAJ&hl=de), Yuxuan Zhao, Dexin Yu, [Kai Ding](https://scholar.google.com/citations?user=OvpsAYgAAAAJ&hl=en), [Constantin Ulrich](https://scholar.google.de/citations?user=PtkCbCwAAAAJ&hl=de), [Klaus Maier-Hein](https://scholar.google.de/citations?user=oCrBpVMAAAAJ&hl=de), [Yang Yang](https://scholar.google.com/citations?user=6XsJUBIAAAAJ&hl=en), [Alan Yuille](https://www.cs.jhu.edu/~ayuille/), [Zongwei Zhou](https://www.zongweiz.com/)* <br/>
Johns Hopkins University <br/>
<a href='https://www.zongweiz.com/dataset'><img src='https://img.shields.io/badge/Project-Page-Green'></a> <a href='https://www.cs.jhu.edu/~zongwei/publication/li2025scalemai.pdf'><img src='https://img.shields.io/badge/Paper-PDF-purple'></a> <a href='document/rsna2024_slides.pdf'><img src='https://img.shields.io/badge/Slides-2024-orange'></a> [![YouTube](https://badges.aleen42.com/src/youtube.svg)](https://youtu.be/5ByuftwmF7w)

## *PancreaVerse:* An AI Trusted Dataset for Pancreatic Cancer Studies

<div align="center">
 
![logo](document/fig_reader_study_tumor_detection.jpg)
</div>
AI models, trained on the PancreaVerse dataset, match senior and expert radiologists in tumor detection and surpasses them in tumor classification accuracy. <br/><br/>


| **dataset** | **# of class** | **# of CT** | **# of center** |
|-----------|:--------:|:---------:|:---------:|
| TCIA-CBCT [[Han et al., Med. Phys. 2021](https://pubmed.ncbi.nlm.nih.gov/33905539/)] | 0 | 40 | 1 |
| MSD-Pancreas [[Antonelli et al., Nat. Commun. 2022](https://www.nature.com/articles/s41467-022-30695-9.pdf)] | 2 | 420 | 1 |
| TCIA-panNET [[Chen et al., Int. J. Cancer 2023](https://pubmed.ncbi.nlm.nih.gov/36111424/)] | 0 | 38 | 1 |
| PANORAMA [[Alves et al., 2024](https://panorama.grand-challenge.org)] | 6 | 3,000 | 7 |
| **PancreaVerse [[Li et al., 2025](https://www.cs.jhu.edu/~zongwei/publication/li2025scalemai.pdf)]**  | **27** | **25,362** | **112** |

PancreaVerse comprises **25,362** CT scans with precise per-voxel annotations of **benign and malignant pancreatic tumors**, **pancreas head, body, and tail**, along with **24** surrounding structures (i.e., *pancreas, superior mesenteric artery, pancreatic duct, celiac artery, common bile duct, veins, aorta, gall bladder, left and right kidneys, liver, postcava, spleen, stomach, left and right adrenal glands, bladder, colon, duodenum, left and right femurs, left and right lungs, and prostate*). Sourced from **112** hospitals, this dataset includes imaging **metadata** such as patient sex, age, contrast phase, diagnosis, spacing, and scanner details. 

This dataset enables standard medical imaging tasks—detection, segmentation, and classification—and clinical tasks such as tumor staging and radiotherapy planning.

## Citation

```
@article{li2025scalemai,
    title={ScaleMAI: Accelerating the Development of Trusted Datasets and AI Models}, 
    author={Wenxuan Li and Pedro R. A. S. Bassi and Tianyu Lin and Yu-Cheng Chou and Xinze Zhou and Yucheng Tang and Fabian Isensee and Kang Wang and Qi Chen and Xiaowei Xu and Xiaoxi Chen and Lizhou Wu and Qilong Wu and Yannick Kirchhoff and Maximilian Rokuss and Saikat Roy and Yuxuan Zhao and Dexin Yu and Kai Ding and Constantin Ulrich and Klaus Maier-Hein and Yang Yang and Alan L. Yuille and Zongwei Zhou},
    journal={arXiv preprint arXiv:2501.03410},
    year={2025},
    url={https://github.com/MrGiovanni/ScaleMAI}
}
```

## Acknowledgement

This work was supported by the Lustgarten Foundation for Pancreatic Cancer Research and the McGovern Foundation. Paper content is covered by patents pending.
