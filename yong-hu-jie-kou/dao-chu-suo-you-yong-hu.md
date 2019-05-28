导出Excel接口地址:

[http://192.168.142.6:8080/user/excel](http://192.168.142.6:8080/user/excel)

导出csv接口地址:

http://192.168.142.6:8080/user/csv

请求方式:

POST

参数

| 参数名 | 参数说明 |
| :--- | :--- |
| username | 用户名 |
| sexx | 性别 |
| status | 状态 |

返回值:

```
{
    "msg":"233b4e0e-7c5d-48f6-afa2-be999be99ee4_用户表.xlsx",
    "code":0
}
```

| 返回值 | 返回值说明 |
| :--- | :--- |
| msg | 操作结果信息 |
| code | 操作结果代码 |



