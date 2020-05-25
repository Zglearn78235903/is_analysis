#接口：login

###用例：登录
   https://zglearn78235903.github.io/is_analysis/test6/用例/登录.md
   
   功能：登录
   
   权限：访客。
   
   API请求地址：http://myweb/v1/api/login
   
   请求方式：POST
   
   请求实例：
   ```angular2
{
    "id":"1",
    "password":"1",
    "type":"学生"
}
```

####请求参数说明:
| 参数名称  |  说明 |
| :-----| ----: | 
| id | 学生学号或者老师的工号，与type有关 |
| password | 用户的密码，不是原文，是加密后的字符串 |
| type | 用户类型，学生或者老师 |

返回实例：
```angular2
{
    "status":true,
    "info":null,
}
```

####返回参数说明:
| 参数名称  |  说明 |
| :-----| ----: | 
| status | bool类型，true表示返回正确，false表示有错误 |
| info | 返回结果说明信息 |