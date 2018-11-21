# Multi-label papers


## Review
-  G. Tsoumakas and I. Katakis, “Multi-label classification: An overview,” International Journal of Data Warehousing and
Mining, vol. 3, no. 3, pp. 1–13, 2007

- Min-Ling Zhang and Zhi-Hua Zhou. 2014. A review on multi-label learning algorithms. IEEE Transaction
on Knowledge and Data Engineering 26, 8 (2014), 1819–1837.

- Gibaja E, Ventura S (2015) A tutorial on multilabel learning. ACM Comput Surv 47(3):52


## Problem Transformation
### BinaryRelevance Based
- Min-Ling Zhang,Ku-Kun,LiXu-Ying,LiuXin Geng.Binary relevance for multi-label learning: an overview,ront. Comput. Sci., 2018, 12(2): 191–202

#### BinaryRelevance
这一方法通过对每一个标签类别训练单独的分类器，因此它假定所有标签独立，忽视了标签之前的相关性。

- M. R. Boutell, J. Luo, X. Shen, and C. M. Brown, “Learning multi-label scene classification,” Pattern Recognition, vol. 37,
no. 9, pp. 1757–1771, 2004.

#### 2BinaryRelevance
这一方法主要是克服BR的没有考虑标签相关性的不足，首先和BR一样对每一个标签类别训练单独的分类器，第二个分类器通过处理第一个分类器的输出构造meta-model进行预测

- Godbole, S., Sarawagi, S.:Discriminative methods for multi-labeled classification.Adv.Knowl.
Discov. Data Mining 3056, 22–30 (2004)
传统的one-vs-other方法没有能挖掘相关性，先通过svm单独训练每一标签，再把训练集label(1或者-1)输出值加feature的列上组成new feature，通过归一化方法把old feature的数据归一化化成([0,1])

- G. Tsoumakas, A. Dimou, E. Spyromitros, V. Mezaris, I. Kompatsiaris, and I. Vlahavas, “Correlation-based pruning
of stacked binary relevance models for multi-label learning,” in Working Notes of the First International Workshop on
Learning from Multi-Label Data, Bled, Slovenia, 2009, pp. 101–116.


#### Classifier Chains


## Tools
### MULAN
- Tsoumakas, G., Xioufis, E.S., Vilcek, J., Vlahavas, I.: MULAN: A Java library for multi-label learning. J. Mach. Learn. Res. 12, 2411–2414 (2011)http://www.jmlr.org/papers/v12/tsoumakas11a.html

### MEKA
- Read, J., Reutemann, P.: MEKA multi-label dataset repository. http://sourceforge.net/projects/meka/files/Datasets/

### scikit-multilearn
- zyma ́nski and T. Kajdanowicz.  A scikit-based Python environment for performingmulti-label classification.ArXiv e-prints, February 2017.http://scikit.ml/index.html

### MLC toolbox
- K.  Kimura,  L.  Sun,  and  M.  Kudo.  (2017). MLC toolbox:A MATLAB/OCTAVE library for multi-label classification.'' [Online].Available: https://arxiv.org/abs/1704.02592

### 周志华主页
- LAMDA Lab (Nanjing Univ., China) Code Repository. http://lamda.nju.edu.cn/Default.aspx?Page=Data&NS=&AspxAutoDetectCookieSupport=1•Prof.

### 张敏灵主页
- Min-Ling Zhang (Southeast Univ., China)http://cse.seu.edu.cn/old/people/zhangml/Resources.htm#codes