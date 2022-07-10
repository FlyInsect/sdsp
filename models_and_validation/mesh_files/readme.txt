
1、mtrees2020.txt	数据来源		来源名称
https://nlmpubs.nlm.nih.gov/projects/mesh/2020/meshtrees/	mtrees2020.bin

2、mtrees_dis.txt来自mtrees2020.txt	只含C大类（没有进一步过滤），不含C01 Infection这种一级子疾病。
mtrees_dis_correct.txt	包含C大类，包含C01 Infection这种一级子疾病。

3、dis_mesh.json	来自mtrees_dis.txt	{疾病：{C下一级分类}},不含C01 Infection这种一级子疾病。
dis_mesh_correct.json	来自mtrees_dis.txt	{疾病：{C下一级分类}},包含C大类，包含C01 Infection这种一级子疾病。