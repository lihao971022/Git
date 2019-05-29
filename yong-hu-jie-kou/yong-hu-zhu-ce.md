用户注册接口地址:

```
http://192.168.142.6:8080/user/regist
```

请求方式:

POST

参数:

```
后台接收参数: User user
```

| 参数名 | 参数说明 |
| :--- | :--- |
| username | 用户名 |
| password | 密码 |
| deptId | 部门id, 通过下拉框选取 |
| email | 邮箱 |
| mobile | 电话 |
| status | 状态, ,默认是1\(开启\) |
| ssex | 性别, 通过单选框选择 |
| description | 个人描述 |

返回值:

```
{
  "msg": "操作成功",
  "code": 0
}
或者
{
  "msg": "该用户名已被使用！",
  "code": 1
}
```



