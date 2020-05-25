#实验6.基于GitHub的实验管理平台的分析与设计
| 姓名  |  学号 | 班级 |
| :-----| ----: | :----: |
| 钟港 | 201710414130 | 17级软工1班 |

##1.概述
  a.基于GitHub的实验管理平台的作用是在线管理实验成绩的web应用系统。学生和老师的实验内容都可以存放在GitHub页面上。
  b.学生功能：设置自己的的GitHub用户名，查询自己的实验成绩。学生的GitHub用户名是公开的，但是成绩不公开。
  c.老师的功能：批改学生的成绩，查看每个学生的成绩。
  d.实验成绩是0-100分，满分为100分，0分为最低分
  
##2.系统设计总体结构

  界面设计参见：https://zglearn78235903.github.io/is_analysis/test6/ui/index.html
  
##3.用例图设计 
   源码：https://zglearn78235903.github.io/is_analysis/test6/src/UseCase.puml
   
##4.类图设计
   源码：https://zglearn78235903.github.io/is_analysis/test6/src/class.puml
   
##5.数据库设计
   参见数据库设计：https://zglearn78235903.github.io/is_analysis/test6/数据库设计.md
   
   
6.用例及界面设计详细设计
   学生列表  用例：
            界面：https://zglearn78235903.github.io/is_analysis/test6/ui/student.html
            
   用户修改   用例：
              界面：https://zglearn78235903.github.io/is_analysis/test6/ui/用户修改.html 
              
   成绩查询   用例：
             界面：https://zglearn78235903.github.io/is_analysis/test6/ui/查看成绩.html  
   
   成绩评定   用例：
              界面：https://zglearn78235903.github.io/is_analysis/test6/ui/成绩评定.html
              
  