#接口: getUse

###用例：
查看用户修改信息：https://zglearn78235903.github.io/is_analysis/test6/用例/查看用户修改信息.md

修改用户信息:https://zglearn78235903.github.io/is_analysis/test6/用例/修改用户信息.md

权限：学生/老师：查看自己的信息，必须先登录，不能查看其他用户的信息。

API请求地址：http://myweb/v1/api/getUpdate

请求方式：GET

####请求参数说明
| 参数名称  |  说明 |
| :-----| ----: | 
| user_id | 用户的ID号 |

返回实例：
```angular2
{
"status": true,
      "info": null,
      "ID":"1",    
      "name":"张三",
      "class_dept":"软件工程1班"
      "github_username":"123",
      "type":"学生" 
}
```

####返回参数说明
| 参数名称  |  说明 |
| :-----| ----: | 
| status | bool类型，true表示正确的返回，false表示有错误 |
| info	 | 返回结果说明信息 |
| ID | 学号或者工号 |
| name | 用户的真实姓名 |
| class_dept | 班级或者部门名称 |
| github_username | gitHub用户名 |
| type | 用户类型：老师或者学生 |
