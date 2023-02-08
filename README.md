# Smart-Analysis-of-Economics-in-Spanish
Smart Analysis of Economics Sentiment in Spanish based on Linguistic Features and Transformers


## Abstract
Texts related to economics and finances are characterized by the use of words and expressions whose meaning (and the sentiments they convey) substantially depend on the context. This poses a major challenge to Natural Language Processing tasks in general, and Sentiment Analysis in particular. For low-resource languages such as Spanish, this situation becomes even more acute. Yet, the latest advancements in the field, including word embeddings and transformers, have allowed to boost the performance of Sentiment Analysis solutions. In this work we explore the impact of the combination of different feature sets in the accuracy of Sentiment Analysis in Spanish financial texts. For this, a corpus with 15,915 tweets has been compiled and manually annotated as either positive, negative, or neutral. Then, feature sets based on contextual and non-contextual embeddings along with linguistic features were evaluated both individually and combined. The best results, with a weighted F1-score of 73.15880%, were obtained with a combination of feature sets by means of knowledge integration.


## Dataset
The dataset can be found at: 
```
http://pln.inf.um.es/corpora/economics/economics-2021.rar
```

| Label    | Train | Val  | Test | Total |
|----------|-------|------|------|-------|
| Positive | 2505  | 835  | 836  | 4176  |
| Neutral  | 4669  | 1556 | 1557 | 7782  |
| Negative | 2374  | 791  | 792  | 3957  |
| Total    | 9548  | 3182 | 3185 | 15915 |



## Funding
This work is part of the research projects AIInFunds (PDC2021-121112-I00) and LT-SWM (TED2021-131167B-I00) funded by MCIN/AEI/10.13039/501100011033 and by the European Union NextGenerationEU/PRTR. This work is also part of the research project LaTe4PSP (PID2019-107652RB-I00/AEI/ 10.13039/501100011033) funded by MCIN/AEI/10.13039/501100011033. Besides, it was partially supported by the Seneca Foundation-the Regional Agency for Science and Technology of Murcia (Spain)-through project 20963/PI/18. In addition, José Antonio García-Díaz is supported by Banco Santander and the University of Murcia through the Doctorado Industrial programme.
