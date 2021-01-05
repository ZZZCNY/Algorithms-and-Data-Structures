算法数据结构      
                         ---- 链表
实验目的：
1．掌握线性表-链表的定义；
2．掌握线性表-链表的基本操作，如建立、查找、插入和删除等。
实验内容：
1.(必做)定义一个包含学生信息（学号，姓名，成绩）的的链表，使其具有如下功能：
(1) 根据指定学生个数，逐个输入学生信息；
(2) 逐个显示学生表中所有学生的相关信息；
(3) 根据姓名进行查找，返回此学生的学号和成绩；
(4) 根据指定的位置可返回相应的学生信息（学号，姓名，成绩）； 
(5) 给定一个学生信息，插入到表中指定的位置； 
(6) 删除指定位置的学生记录；
(7) 统计表中学生个数。
选做（至少在2，3，4中选择其中一题完成）：
2. 基于单链表实现一元多项式（稀疏）的相加和相减
3．P53 7实现单链表的“原地”逆转。
4．基于循环单链表实现约瑟夫环问题。
实验提示： 
学生信息的定义：
typedef struct {
    char no[8];   //8位学号
    char name[20]; //姓名
    int price;     //成绩
}Student;

顺序表的定义
typedef  struct {
  Student  *elem;     //指向数据元素的基地址
  int  length;       //线性表的当前长度                                                           
 }SqList；
	实验要求：
(1) 程序要添加适当的注释，程序的书写要采用缩进格式。
(2) 程序要具在一定的健壮性，即当输入数据非法时，程序也能适当地做出反应，如插入删除时指定的位置不对等等。
(3) 程序要做到界面友好，在程序运行时用户可以根据相应的提示信息进行操作。
(4) 根据实验报告模板详细书写实验报告,在实验报告中给出链表根据姓名进行查找的算法和插入算法的流程图。
(5) 上传实验报告到网络教学平台实验报告命名为：实验2+班级+学号姓名.doc。如实验1+软件工程1701+070814101薛力.docx，报告命名格式严格遵守！！
