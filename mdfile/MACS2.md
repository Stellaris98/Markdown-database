#MACS2
##安装
`pip install MACS2`

##背景
####ChIP-Seq
ChIP全称为 **染色质免疫共沉淀技术**（Chromatin Immunoprecipitation），是研究蛋白质与DNA相互作用的有力工具，用于转录因子结合位点或组蛋白特异性修饰位点的研究
![img](https://github.com/Stellaris98/Markdown-database/blob/main/images/%E5%90%84%E7%A7%8DChIP.png)
####MACS2
MACS2全称为 **model-based analysis of ChIP-Seq**，基于模型（**泊松分布**）进行检峰，也就是**双峰模型**，目的是将比对上的 reads 向3`端进行延伸偏移（即 shift 参数），但这也仅仅针对于单端测序（SE）的数据适用，双端测序数据（PE）则可以直接使用测出来的真实 Fragment Size 进行检峰