# Impact-factor-on-Mashup-clustering-TWE-NMF
NMF+K: 通过传统的非负矩阵分解方法对Mashup进行主题建模，并采用k-means方法对建模结果进行聚类。<br>
NMF+SC: 通过传统的非负矩阵分解方法对Mashup进行主题建模，并采用谱聚类方法对建模结果进行聚类。<br>
WE-NMF+K: 在非负矩阵分解中引入词嵌入信息后对Mashup服务进行主题建模，采用k-means方法对结果进行聚类。<br>
WE-NMF+SC: 在非负矩阵分解中引入词嵌入信息后对Mashup服务进行主题建模，采用谱聚类方法对结果进行聚类。<br>
T-NMF+K：通过TCSW方法重新计算单词权重信息，代替传统非负矩阵中的文档-词频信息，对Mashup服务进行主题建模，采用k-means方法对结果进行聚类。<br>
T-NMF+SC：通过TCSW方法重新计算单词权重信息，代替传统非负矩阵中的文档-词频信息，对Mashup服务进行主题建，采用谱聚类方法对结果进行聚类。<br>
TWE-NMF+K: 在非负矩阵分解中综合词嵌入信息和TCSW方法计算的单词权重信息对Mashup服务进行建模，采用谱聚类的方式对最后结果聚类。<br>
TWE-NMF+SC：本文提出的方法，在非负矩阵分解中综合词嵌入信息和TCSW方法计算的单词权重信息对Mashup服务进行主题建模，采用谱聚类的方式对最后结果聚类。<br>
WE-NMF方法，通过注释TWE-NMF.py中379行的TCSW方法注释实现<br>
T-NMF方法，通过将TWE-NMF.py中将359，360行中lam_w，lam_t赋值为0实现<br>
