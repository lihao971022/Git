校验输入的原密码接口地址:

```
http://192.168.142.6:8080/user/checkPassword?password=123456
```

请求方式:

GET

参数:

```
后台接收参数: String password
```

| 参数名 | 参数说明 |
| :--- | :--- |
| password | 密码 |

返回值:

```
Boolean   true  或者 false 
```

修改密码接口地址:

```
http://192.168.142.6:8080/user/updatePassword
```

请求方式:

POST

参数:

```
后台接收参数:  String newPassword
```

| 参数名 | 参数说明 |
| :--- | :--- |
| password | 新密码 |

返回值:

```
{
    "msg":"更改密码成功！",
    "code":0
}
```



