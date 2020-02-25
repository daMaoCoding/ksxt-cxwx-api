# 入参

* url:```https://2858y3h397.qicp.vip/cxwx/order2```

* type:GET

* params:

  | 字段  | 类型   | 是否必填 |
  | ----- | ------ | -------- |
  | token | String | 是       |
  | order | Order  | 否       |

  

# 出参

| 字段    | 类型       | 值                                                           |
| ------- | ---------- | ------------------------------------------------------------ |
| status  | Integer    | 1 成功，其他失败                                             |
| message | String     | 对status的描述                                               |
| data    | JsonObject | {orderSet:{[name:'aaa'],[name:'bbb'],...},<br />orderList :{[id:1,name:'aaa',..],..},<br />order:{id:xxx,name:xxx,...}<br />} |

