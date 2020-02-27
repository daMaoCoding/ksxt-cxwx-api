# 入参

* url:```https://2858y3h397.qicp.vip/cxwx/ReceiveEnt/chongzhi```

* type:GET

* params:

  

  | 字段       | 类型       | 是否必填 |
  | ---------- | ---------- | -------- |
  | token      | string     | 是       |
  | bean       | ReceiveEnt | 是       |
  | pageSize   | Integer    | 否       |
  | pageNumber | Integer    | 否       |

  

  

# 出参

| 字段    | 类型       | 值                                                           |
| ------- | ---------- | ------------------------------------------------------------ |
| status  | Integer    | 1 成功<br />其他值表示失败                                   |
| message | String     | status的描述                                                 |
| data    | JsonObject | {<br />bean:ReceiveEnt<br />list:List<ReceiveEntMineral><br />} |

