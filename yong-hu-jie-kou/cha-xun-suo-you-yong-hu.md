查询所有用户信息接口地址:

[http://192.168.142.6:8080/user/list?pageSize=10&pageNum=1&username=&ssex=&status=](http://192.168.142.6:8080/user/list?pageSize=10&pageNum=1&username=&ssex=&status=&_=1559035165460)

请求方式:

GET

参数:

默认查询全部,查询条件如下:

| 参数名 | 参数说明 |
| :--- | :--- |
| pageSize | 每页显示多少条 |
| pageNum | 第几页 |
| username | 用户名 |
| ssex | 性别 |
| status | 状态 |

返回值:

{

```
{
  "total": 6,
  "rows": [
    {
      "userId": 4,
      "username": "MrBird",
      "password": null,
      "deptId": null,
      "deptName": "null",
      "email": "mrbird@hotmail.com",
      "mobile": "13455533222",
      "status": "1",
      "crateTime": "2017-12-27 23:47:19",
      "modifyTime": null,
      "lastLoginTime": null,
      "ssex": "0",
      "theme": null,
      "avatar": null,
      "description": null,
      "roleName": null,
      "authCacheKey": 4
    },
    {
      "userId": 6,
      "username": "tester",
      "password": null,
      "deptId": null,
      "deptName": "null",
      "email": "tester@qq.com",
      "mobile": "13888888888",
      "status": "1",
      "crateTime": "2017-12-28 01:35:14",
      "modifyTime": null,
      "lastLoginTime": null,
      "ssex": "1",
      "theme": null,
      "avatar": null,
      "description": null,
      "roleName": null,
      "authCacheKey": 6
    },
    {
      "userId": 23,
      "username": "scott",
      "password": null,
      "deptId": null,
      "deptName": "测试部",
      "email": "scott@qq.com",
      "mobile": "15134627380",
      "status": "1",
      "crateTime": "2017-12-30 00:16:39",
      "modifyTime": null,
      "lastLoginTime": null,
      "ssex": "0",
      "theme": null,
      "avatar": null,
      "description": null,
      "roleName": null,
      "authCacheKey": 23
    },
    {
      "userId": 24,
      "username": "smith",
      "password": null,
      "deptId": null,
      "deptName": "null",
      "deptName": "smith@qq.com",
      "mobile": "13364754932",
      "status": "1",
      "crateTime": "2017-12-30 00:21:31",
      "modifyTime": null,
      "lastLoginTime": null,
      "ssex": "1",
      "theme": null,
      "avatar": null,
      "description": null,
      "roleName": null,
      "authCacheKey": 24
    },
    {
      "userId": 26,
      "username": "martin",
      "password": null,
      "deptId": null,
      "deptName": "null",
      "email": "martin@qq.com",
      "mobile": "15562736678",
      "status": "1",
      "crateTime": "2017-12-30 00:22:24",
      "modifyTime": null,
      "lastLoginTime": null,
      "ssex": "1",
      "theme": null,
      "avatar": null,
      "description": null,
      "roleName": null,
      "authCacheKey": 26
    },
    {
      "userId": 91,
      "username": "系统监控员",
      "password": null,
      "deptId": null,
      "deptName": "null",
      "email": "xtjk@qq.com",
      "mobile": "18088736652",
      "status": "1",
      "crateTime": "2018-01-09 23:52:56",
      "modifyTime": null,
      "lastLoginTime": null,
      "ssex": "0",
      "theme": null,
      "avatar": null,
      "description": null,
      "roleName": null,
      "authCacheKey": 91
    }
  ]
}
```

}

| 返回值 | 返回值说明 |
| :--- | :--- |
| total | 总条数 |
| rows | 数组 |
| userId | 用户id |
| username | 用户名称 |
| deptName | 部门名称 |
| email | 邮箱 |
| mobile | 手机 |
| status | 状态  0=锁定,1=有效 |
| crateTime | 创造时间 |
| ssex | 性别 0=男,1=女,2=保密 |



