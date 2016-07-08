# FictionAnalysis
对小说文本进行分析，提炼小说剧情内容和人物关系

如果一部从未度过的小说，经过程序的分析解读便可列出小说中的主要人物，并阐明人物关系，是不是很有意思呢！
#程序的主要思路如下:

1、在没有词库的情况下，解析文本，通过计算一个词的内部凝固程度和自由运用度来判断一个词可否为单词

2、提取人名和地名

3、通过人物名称在文本中的位置和发生关系的动作建立人物关系图谱

听起来是不是很高大上呢，哈哈，现在勉强完成了第一步，在此感谢这篇博客的作者 http://www.csdn.net/article/2013-05-08/2815186 ，程序的第一步完全是在实现这篇博客的算法

#如何使用
<!--hibiscusMain.py 为主程序，直接运行即可，程序将读取《黑色裂变.txt》并最终输出一个excel-->
python hibiscusMain.py "path/file"
-->file.xls
