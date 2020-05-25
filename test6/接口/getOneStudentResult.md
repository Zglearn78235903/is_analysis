#接口：getOneStudentResult

###用例：

查看成绩： https://github.com/Zglearn78235903/is_analysis/test6/用例/查看成绩.md

评定成绩： https://github.com/Zglearn78235903/is_analysis/test6/用例/评定成绩.md

权限：学生：只能查看自己的成绩，即接口参数student_id必须等于登录学生的student_id 老师：可以查看所有学生的成绩。

API请求地址：http://myweb/v1/api/getStudent

请求方式：GET

####请求参数说明：

| 参数名称  |  说明 |
| :-----| ----: | 
| student_id | 学生学号 |

返回实例：
```angular2
{
"status": true,
      "info": null,    
      "student_id": "1", 
      "github_username": "chinajuedui", 
      "class": "软件(本)17-1", 
      "name": "张三", 
      "total": 6,
      "avgresult":90,       
      "data": [
          {
          "test_id":1,
          "web_exists": true, 
          "result": 90, 
          "memo":"做得好",
          }, 
          {
          ...
          }
      ] 
}
```

####返回参数说明:
| 参数名称  |  说明 |
| :-----| ----: | 
| status | bool类型，true表示返回正确，false表示有错误 |
| info | 返回结果说明信息 |
| student_id | 学号 |
| github_username | 学生的gitHub用户名 |
| class | 班级 |
| name | 真实姓名 |
| total |实验总数 |
| avgresult | 实验平均成绩 |
| data | 所有实验的成绩和评语 |
| result | 本实验成绩 |

