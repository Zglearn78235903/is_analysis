#接口：setPassword

###用例：

修改密码：https://zglearn78235903.github.io/is_analysis/test6/用例/修改密码.md

功能：修改用户密码

权限：学生/老师

API请求地址：http://myweb/v1/api/setUpdate

请求方式：POST

请求实例:
```angular2
{
     "user_id":1,
      "password":***
}
```
####请求参数说明
| 参数名称  |  说明 |
| :-----| ----: | 
| user_id | 用户的ID号 |
| password | 用户的密码 |

返回实例：
```angular2
{
 "status": true,
      "info": null,
}
```

####返回参数说明
| 参数名称  |  说明 |
| :-----| ----: | 
| status | bool类型，true表示正确的返回，false表示有错误 |
| info | 返回结果说明信息 |
