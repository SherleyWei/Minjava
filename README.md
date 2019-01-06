# Minjava

文法文件为src文件夹下的MiniJava.g4文件
运行前需要加载antlr-4.7.2-complete.jar包并添加到系统环境变量路径中。

编译器使用步骤
（1）编写Minijava.g4语法文件，在其中加入错误处理的java代码
（2）执行antlr4命令：antlr4 MiniJava.g4
（3）编译生成的java文件，执行命令：javac –cp antlr-4.7.2-complete.jar *.java
（4）添加测试代码binarysearch.java到目录下
（5）得到语法分析树，执行命令：grun MiniJava prog -gui binarysearch.java  
通过以上步骤既可生成binarysearch.java程序的语法分析树，得到下图所示语法分析树。



实验分工：
曹楠	15307130312	错误类型及错误测试、撰写报告
韦霞杰	15307130416	撰写语法分析文件、撰写报告、课程演示
