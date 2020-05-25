#接口：logout

###用例：登录
   https://zglearn78235903.github.io/is_analysis/test6/用例/登出.md
   
   功能：用户退出登录
   
   权限：学生/老师已经登录
   
   API请求地址：http://myweb/v1/api/logout
   
   请求方式：POST

   请求实例：
   
   ```angular2
{
    "user_id":1
}
```

####请求参数说明:
| 参数名称  |  说明 |
| :-----| ----: | 
| user_id | 已经登录用户的id |

返回实例：
```angular2
   "status":true,
   "info":null,
```

####返回参数说明:
| 参数名称  |  说明 |
| :-----| ----: | 
| status | bool类型，true表示返回正确，false表示有错误 |
| info | 返回结果说明信息 |