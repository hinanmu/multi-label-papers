# Multi-label papers

## Review
-  G. Tsoumakas and I. Katakis, “Multi-label classification: An overview,” International Journal of Data Warehousing and
Mining, vol. 3, no. 3, pp. 1–13, 2007

- Min-Ling Zhang and Zhi-Hua Zhou. 2014. A review on multi-label learning algorithms. IEEE Transaction
on Knowledge and Data Engineering 26, 8 (2014), 1819–1837.

- Gibaja E, Ventura S (2015) A tutorial on multilabel learning. ACM Comput Surv 47(3):52

- Charte, F., Rivera, A.J., del Jesus, M.J., Herrera, F.: Multilabel Classification. Problem analysis, metrics and techniques book repository(2016)

- PPT2014-Multi-label Classification

- PPT2014-Tutorial on Multilabel

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

- G. Tsoumakas, A. Dimou, E. Spyromitros, V. Mezaris, I. Kompatsiaris, and I. Vlahavas, “Correlation-based pruning
of stacked binary relevance models for multi-label learning,” in Working Notes of the First International Workshop on
Learning from Multi-Label Data, Bled, Slovenia, 2009, pp. 101–116.


#### ClassifierChains
- PPT2014-Multi-target Prediction with Classifier Chains
##### CC & ECC
- Read J., Pfahringer B., Holmes G., Frank E. (2009) Classifier Chains for Multi-label Classification. In: Buntine W., Grobelnik M., Mladenić D., Shawe-Taylor J. (eds) Machine Learning and Knowledge Discovery in Databases. ECML PKDD 2009. Lecture Notes in Computer Science, vol 5782. Springer, Berlin, Heidelberg

- Jesse Read·Bernhard Pfahringer·Geoff Holmes·Eibe Frank, “Classifier chains for multi-label classification,” Machine Learning, vol. 85, no. 3, pp. 333–359, 2011

##### PCC & EPCC
-  K. Dembczy´nski, W. Cheng, and E. H¨ullermeier, “Bayes optimal multilabel classification via probabilistic classifier chains,” in Proceedings of the 27th International Conference on Machine Learning, Haifa, Israel, 2010, pp. 279–286

### LabelCombination Based
#### LabelPowerset
##### LP
- M. R. Boutell, J. Luo, X. Shen, and C. M. Brown, “Learning multi-label scene classification,” Pattern Recognition, vol. 37,
no. 9, pp. 1757–1771, 2004.

-  G. Tsoumakas and I. Katakis, “Multi-label classification: An overview,” International Journal of Data Warehousing and
Mining, vol. 3, no. 3, pp. 1–13, 2007

##### RAkEL
- Random k-labelsets for multi-label classification, IEEE Transactions on Knowledge and Data Engineering, vol. 23,
no. 7, pp. 1079–1089, 2011.

#### PS

#### EPS

### Label Space Dimension Reduction
#### CS
- Hsu, D., Kakade, S. M., Langford, J., & Zhang, T. (2009). Multi-label prediction via compressed sensing. In
NIPS ’09: neural information processing systems 2009.

#### PLST
- F. Tai and H.-T. Lin. Multi-Label classification with principal label space transformation. In Neural
Computation, 2012.

#### CPLST
- Y.-N. Chen and H.-T. Lin, “Feature-aware label space dimension
reduction for multi-label classification,” in NIPS, 2012, pp. 1529–1537

## Tools
### scikit-multiflow(Python)
- Jacob Montiel, Jesse Read, Albert Bifet, and Talel Abdessalem. 2018.   Scikit-MultiFlow: A Multi-output Streaming Framework.Manuscript in Preparation(2018), 1–5.  https://github.com/scikit-multiflow/scikit-multiflow

### MULAN(JAVA)
- Tsoumakas, G., Xioufis, E.S., Vilcek, J., Vlahavas, I.: MULAN: A Java library for multi-label learning. J. Mach. Learn. Res. 12, 2411–2414 (2011)http://www.jmlr.org/papers/v12/tsoumakas11a.html

### MEKA(JAVA)
- Read, J., Reutemann, P.: MEKA multi-label dataset repository. http://sourceforge.net/projects/meka/files/Datasets/

### scikit-multilearn(Python)
- zyma ́nski and T. Kajdanowicz.  A scikit-based Python environment for performingmulti-label classification.ArXiv e-prints, February 2017.http://scikit.ml/index.html

### MLC toolbox(Matlab)
- K.  Kimura,  L.  Sun,  and  M.  Kudo.  (2017). MLC toolbox:A MATLAB/OCTAVE library for multi-label classification.'' [Online].Available: https://arxiv.org/abs/1704.02592

### 周志华主页(Matlab)
- LAMDA Lab (Nanjing Univ., China) Code Repository. http://lamda.nju.edu.cn/Default.aspx?Page=Data&NS=&AspxAutoDetectCookieSupport=1•Prof.

### 张敏灵主页(Matlab)
- Min-Ling Zhang (Southeast Univ., China)http://cse.seu.edu.cn/old/people/zhangml/Resources.htm#codes