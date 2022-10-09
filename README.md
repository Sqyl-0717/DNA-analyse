# DNA-analyse
统计建模
XY二核苷分类方法
X=Y∈{A、T、C、G}，XY二核苷组合有16类。基因组序列8-mer集合共有48=65536个模体。
具体分类如下，M是给定的8-mer模体（即M∈8-mer集合），num代表M模体中包含XY的个数。
若num=0，则M∈XY0子集，若num=1，则M∈XY1子集，若num≥2，则M∈XY2子集。按照X与Y之间的关系，表2中列出每类子集包含8-mer模体数。

八个物种基因组序列：Chimpanzee（大猩猩），Orangutan（红毛猩猩），Turkey（火鸡），Nile tilapia（尼罗罗非鱼），Vase tunicate（玻璃海鞘）
Caenorhabditis brenneri（线虫），Caenorhabditis briggsae（线虫），Schizosaccharomyces pombe（裂殖酵母）

表1  八个物种基因组数据表
物种名称	数据库
Chimpanzee（大猩猩）	P. troglodytes	UCSC
Orangutan（红毛猩猩）	P. abelii	UCSC
Turkey（火鸡）	M. gallopavo	NCBI
Nile tilapia（尼罗罗非鱼）	O. niloticus	NCBI
Vase tunicate（玻璃海鞘）	C. intestinalis	NCBI
Nenatode（线虫）	C. briggsae	NCBI
Nenatode（线虫）	C. brenneri	NCBI
Schizosaccharomyces pombe（裂殖酵母）	S. pombe	NCBI


accdb文件为步骤2的另一种方法，但是好像搞乱掉了，sorry
