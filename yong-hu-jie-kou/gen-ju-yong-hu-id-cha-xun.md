根据用户id进行用户资料接口地址:

```
http://192.168.142.6:8080/user/getUserProfile?userId=4
```

请求方式:

GET

参数:

```
后天接收参数:  Long userId
```

| 参数名 | 参数说明 |
| :--- | :--- |
| userId | 用户id |

返回值:

```
{
  "msg": {
    "userId": 4,
    "username": "MrBird",
    "password": null,
    "deptId": 1,
    "deptName": "安全责任人",
    "email": "mrbird@hotmail.com",
    "mobile": "13455533222",
    "status": "1",
    "crateTime": null,
    "modifyTime": null,
    "lastLoginTime": null,
    "ssex": "0",
    "theme": null,
    "avatar": "default.jpg",
    "description": "我是作者。",
    "roleName": "管理员",
    "authCacheKey": 4
  },
  "code": 0
}
```

| 返回值 | 返回值说明 |
| :--- | :--- |
| userId | 用户id |
| username | 用户名 |
| deptName | 部门名称 |
| email | 邮箱 |
| mobile | 电话 |
| status | 状态  0=锁定,1=有效 |
| ssex |  性别 0=男,1=女,2=保密 |
|  description | 个人描述 |
|  roleName | 角色名称 |



