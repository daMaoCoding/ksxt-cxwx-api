# 入参

* url: ```https://2858y3h397.qicp.vip/cxwx/userRemoveOpenId```

* type: GET

* params:

  

  | 字段  |  类型  | 是否必填 |
  | :---: | :----: | :------: |
  | token | String |    是    |

# 出参

|  字段   |  类型   |         值          |
| :-----: | :-----: | :-----------------: |
| status  | Integer | 1 成功 ，其他值失败 |
| message | String  |   对status的描述    |
|  data   | Object  |         空          |

# 示例

* 请求

> `https://2858y3h397.qicp.vip/cxwx/userRemoveOpenId?token=123456`

* 响应

> {
>   "state" : 1,
>   "message" : "OK",
>   "data" : null
> }