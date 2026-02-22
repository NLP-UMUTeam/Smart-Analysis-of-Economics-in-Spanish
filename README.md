# Smart Analysis of Economics in Spanish
Smart Analysis of Economics Sentiment in Spanish based on Linguistic Features and Transformers

### Authors

- **José Antonio García-Díaz** — University of Murcia  
  [Google Scholar](https://scholar.google.com/citations?user=ek7NIYUAAAAJ) · [ORCID](https://orcid.org/0000-0002-3651-2660)

- **Francisco García-Sánchez** — University of Murcia  
  [Google Scholar](https://scholar.google.com/citations?user=ZKFL__kAAAAJ) · [ORCID](https://orcid.org/0000-0003-1911-8749)

- **Rafael Valencia-García** — University of Murcia  
  [Google Scholar](https://scholar.google.com/citations?user=GLpBPNMAAAAJ) · [ORCID](https://orcid.org/0000-0003-2457-1791)  

> **Affiliations:**  
> \* *Departamento de Informática y Sistemas, Universidad de Murcia, Campus de Espinardo, Murcia, Spain*  

## Publication
https://ieeexplore.ieee.org/abstract/document/10041929

## Abstract
Texts related to economics and finances are characterized by the use of words and expressions whose meaning (and the sentiments they convey) substantially depend on the context. This poses a major challenge to Natural Language Processing tasks in general, and Sentiment Analysis in particular. For low-resource languages such as Spanish, this situation becomes even more acute. Yet, the latest advancements in the field, including word embeddings and transformers, have allowed to boost the performance of Sentiment Analysis solutions. In this work we explore the impact of the combination of different feature sets in the accuracy of Sentiment Analysis in Spanish financial texts. For this, a corpus with 15,915 tweets has been compiled and manually annotated as either positive, negative, or neutral. Then, feature sets based on contextual and non-contextual embeddings along with linguistic features were evaluated both individually and combined. The best results, with a weighted F1-score of 73.15880%, were obtained with a combination of feature sets by means of knowledge integration.


## Dataset
The dataset can be found at the ```dataset``` folder.

Due to X's Terms of Service, the publicly available version of the dataset only includes tweet identifiers and annotations.

These are the statistics of the dataset.

| Label    | Train | Val  | Test | Total |
|----------|-------|------|------|-------|
| Positive | 2505  | 835  | 836  | 4176  |
| Neutral  | 4669  | 1556 | 1557 | 7782  |
| Negative | 2374  | 791  | 792  | 3957  |
| Total    | 9548  | 3182 | 3185 | 15915 |



## Funding
This work is part of the research projects AIInFunds (PDC2021-121112-I00) and LT-SWM (TED2021-131167B-I00) funded by MCIN/AEI/10.13039/501100011033 and by the European Union NextGenerationEU/PRTR. This work is also part of the research project LaTe4PSP (PID2019-107652RB-I00/AEI/ 10.13039/501100011033) funded by MCIN/AEI/10.13039/501100011033. Besides, it was partially supported by the Seneca Foundation-the Regional Agency for Science and Technology of Murcia (Spain)-through project 20963/PI/18. In addition, José Antonio García-Díaz is supported by Banco Santander and the University of Murcia through the Doctorado Industrial programme.


## Citation
```
@article{garcia2023smart,
  title={Smart analysis of economics sentiment in Spanish based on linguistic features and transformers},
  author={Garc{\'\i}a-D{\'\i}az, Jos{\'e} Antonio and Garc{\'\i}a-S{\'a}nchez, Francisco and Valencia-Garc{\'\i}a, Rafael},
  journal={IEEE Access},
  volume={11},
  pages={14211--14224},
  year={2023},
  publisher={IEEE}
}
```
