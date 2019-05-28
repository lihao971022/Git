根据id查询用户接口:

[http://192.168.142.6:8080/user/getUser](http://192.168.142.6:8080/user/getUser)

请求方式:

POST

参数:

| 参数名 | 参数说明 |
| :--- | :--- |
| userId | 用户id |

返回值:

```
{ 
    "msg":
    {
        "userId":93,
        "username":"lihao",
        "password":null,
        "deptId":6,
        "deptName":null,
        "email":"bebetter66@163.com",
        "mobile":"18778671256",
        "status":"1",
        "crateTime":null,
        "modifyTime":null,
        "lastLoginTime":null,
        "ssex":"0",
        "theme":null,
        "avatar":null,
        "description":null,
        "roleName":null,
        "roleId":1,
        "roleIds":[1,2,3,23,24,25],
        "authCacheKey":93},"code":0
    }
```

| 返回值 | 返回值说明 |
| :--- | :--- |
| username | 用户名 |
| email | 邮箱 |
| mobile | 手机 |
| roleIds | 角色 |
| status | 状态 |
| ssex | 性别 |
| deptId | 部门id |

修改用户接口地址:

[http://192.168.142.6:8080/user/update](http://192.168.142.6:8080/user/update)

请求方式:

POST

参数: 

```
后台接收参数 :  User user, Long[] rolesSelect
```

| 参数名 | 参数说明 |
| :--- | :--- |
| username | 用户名 |
| oldusername | 老用户名 |
| userId | 用户ID |
| password | 密码 |
| email | 邮箱 |
| mobile | 手机 |
| rolesSelect | 多种角色数组  Long\[\] rolesSelect |
| roles | 角色  根据下拉框选择角色    |
| status | 状态 |
| ssex | 性别 |
| deptId | 部门   根据复选框选择部门 |



