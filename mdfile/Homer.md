#Homer
##motif
使用一个新的motif算法，只分析DNA序列，通过对比两个sequences文件，寻找富集于某个集合的motif。使用 **ZOOPS** 得分系统（每个sequences出现 0次 或 1次），加上超几何富集计算或二项式来确定motif。虽然主要用于 **ChIP-seq** 和 **promoter** 序列分析，但也可以用于任何核酸序列寻找motif。有两个工具分析motif：`findMotifs.pl` 和 `findMotifsGenome.pl`



###1. findMotifs.pl
寻找启动子区域的motif