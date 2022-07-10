表头：diseaseId	name	vocabulary	code	vocabularyName
UMLS的id	UMLS的name	包括整合数据库的类型（如DO，Mesh，OMIM)	整合数据库中对应的id	对应的name

##
vocabulary为MSH：
1、一个diseaseId 对应一个name。
2、一个code 可能对应多个vocabularyName。
- 有一个是MeSH heading，其他重复的是entry term（？一个heading对应多个entry。官网搜索entry返回相同term）
- 之前提取的Mesh文件就是提取的MeSH heading。
	1，2 ==> 一个UMLS term 可能对应多个vocabulary term（不同vocabularyName）
3、多个UMLS term 可能对应一个 code。

##
vocabulary为ICD10：
1、一个code 对应一个 vocabularyName
2、一个UMLS term 可能对应多个 vocabulary term。