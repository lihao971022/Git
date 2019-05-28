新增用户接口地址:

[http://192.168.142.6:8080/user/add](http://192.168.142.6:8080/user/add)

请求方式:

POST

参数:

```
后台接收参数类型:  User user, Long[] roles
```

| 参数名 | 参数说明 |
| :--- | :--- |
| username | 用户名 |
| password | 密码 |
| email | 邮箱 |
| mobile | 电话 |
| roles | 角色       根据下拉框选择角色 |
| status | 状态       ,默认开启 |
| ssex | 性别 |
| deptId | 部门      根据单选框选择 |



