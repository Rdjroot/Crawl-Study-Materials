# Crawl-Study-Materials
爬取赛事星模拟题下面的题库

原为企业课提供模拟考试网址，下面有题库，但复习使用起来较为麻烦，便使用python selenium 爬取下来存为word文件以供复习

模拟试题网址：http://saishi.cnki.net/PaperIndex/ks0af38326-10ce-48a5-a2cb-84204baf254c

查看源代码找到题库地址：http://saishi.cnki.net/Exercise/Practice/ks0af38326-10ce-48a5-a2cb-84204baf254c/1

使用四个代码分别爬取单选，多选，填空，判断。


单选对应代码：singleTest.py 

    对应结果文件：1.docx

多选对应代码：doubleTest.py

    对应结果文件：double.docx

判断对应代码：judgeTest.py

    对应结果文件：judge.docx

填空对应代码：fullTest.py

    对应结果文件：full.docx
    
-------------------------------
以上为初次提交，为了尽快使用，代码也有许多瑕疵且缺少注解，若日后有时间会补充。
