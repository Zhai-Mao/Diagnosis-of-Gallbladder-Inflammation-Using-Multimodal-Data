# 数据集的准备
数据集是存放CT数据集以及血液样本数据集，这是用于多模态模型输入所需要的数据。其中CT影响数据集包括胆囊扩张程度、周围组织炎症作为分割类别。
## :black_nib: Citation

```bibtex
@article{shaaban2024medpromptx,
      title={MedPromptX: Grounded Multimodal Prompting for Chest X-ray Diagnosis}, 
      author={Mai A. Shaaban and Adnan Khan and Mohammad Yaqub},
      year={2024},
      url={https://arxiv.org/abs/2403.15585},
}
@inproceedings{zhang2023transformer,
  title={Transformer-Based Multimodal Fusion for Early Diagnosis of Alzheimer's Disease Using Structural MRI And PET},
  author={Zhang, Yuanwang and Sun, Kaicong and Liu, Yuxiao and Shen, Dinggang},
  booktitle={2023 IEEE 20th International Symposium on Biomedical Imaging (ISBI)},
  pages={1--5},
  year={2023},
  organization={IEEE}
}
@inproceedings{zhang2023vector,
  title={Vector Quantized Multi-modal Guidance for Alzheimer’s Disease Diagnosis Based on Feature Imputation},
  author={Zhang, Yuanwang and Sun, Kaicong and Liu, Yuxiao and Ou, Zaixin and Shen, Dinggang},
  booktitle={International Workshop on Machine Learning in Medical Imaging},
  pages={403--412},
  year={2023},
  organization={Springer}
}
@ARTICLE{10702472,
  author={Zhang, Yuanwang and Sun, Kaicong and Liu, Yuxiao and Xie, Fang and Guo, Qihao and Shen, Dinggang},
  journal={IEEE Journal of Biomedical and Health Informatics}, 
  title={A Modality-Flexible Framework for Alzheimer's Disease Diagnosis Following Clinical Routine}, 
  year={2025},
  volume={29},
  number={1},
  pages={535-546},
  keywords={Magnetic resonance imaging;Transformers;Feature extraction;Medical diagnostic imaging;Vectors;Switches;Fuses;Alzheimer's disease;Bioinformatics;Accuracy;Multi-modal fusion;Alzheimer's disease diagnosis;transformer;imaging and non-imaging data},
  doi={10.1109/JBHI.2024.3472011}}
@article{10.1093/jamia/ocac168,
    author = {Golovanevsky, Michal and Eickhoff, Carsten and Singh, Ritambhara},
    title = {Multimodal attention-based deep learning for Alzheimer’s disease diagnosis},
    journal = {Journal of the American Medical Informatics Association},
    volume = {29},
    number = {12},
    pages = {2014-2022},
    year = {2022},
    month = {09},
    abstract = {Alzheimer’s disease (AD) is the most common neurodegenerative disorder with one of the most complex pathogeneses, making effective and clinically actionable decision support difficult. The objective of this study was to develop a novel multimodal deep learning framework to aid medical professionals in AD diagnosis.We present a Multimodal Alzheimer’s Disease Diagnosis framework (MADDi) to accurately detect the presence of AD and mild cognitive impairment (MCI) from imaging, genetic, and clinical data. MADDi is novel in that we use cross-modal attention, which captures interactions between modalities—a method not previously explored in this domain. We perform multi-class classification, a challenging task considering the strong similarities between MCI and AD. We compare with previous state-of-the-art models, evaluate the importance of attention, and examine the contribution of each modality to the model’s performance.MADDi classifies MCI, AD, and controls with 96.88\% accuracy on a held-out test set. When examining the contribution of different attention schemes, we found that the combination of cross-modal attention with self-attention performed the best, and no attention layers in the model performed the worst, with a 7.9\% difference in F1-scores.Our experiments underlined the importance of structured clinical data to help machine learning models contextualize and interpret the remaining modalities. Extensive ablation studies showed that any multimodal mixture of input features without access to structured clinical information suffered marked performance losses.This study demonstrates the merit of combining multiple input modalities via cross-modal attention to deliver highly accurate AD diagnostic decision support.},
    issn = {1527-974X},
    doi = {10.1093/jamia/ocac168},
    url = {https://doi.org/10.1093/jamia/ocac168},
    eprint = {https://academic.oup.com/jamia/article-pdf/29/12/2014/47027859/ocac168.pdf},
}
```
