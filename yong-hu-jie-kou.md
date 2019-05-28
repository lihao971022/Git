验证码:   [http://192.168.142.6:8080/gifCode](http://192.168.142.6:8080/gifCode)

请求方式:   GET

登录接口地址:  [http://192.168.142.6:8080/login](http://192.168.142.6:8080/login)

请求方式:  POST

参数:

```
后台接收参数:  String username, String password, String code, Boolean rememberMe
```

| 参数名 | 参数说明 |
| :--- | :--- |
| username | 用户名 |
| password | 密码 |
| code | 验证码 |
| rememberMe | 是否记住我 |

返回值:

{

```
{ "msg": "验证码不能为空！","code": 1}
{"msg":"用户名或密码错误！","code":500}
{"msg":"验证码错误！","code":1}
```

| 返回值 | 返回值说明 |
| :--- | :--- |
| msg | 提示信息 |
| code | 错误代码 |



