# 入参

* url:```https://2858y3h397.qicp.vip/cxwx/ReceiveEnt/list```

* type:GET

* params:

  

  |    字段    |    类型    | 是否必填 |
  | :--------: | :--------: | :------: |
  |    bean    | ReceiveEnt |    否    |
  |   token    |   String   |    是    |
  |  pageSize  |  Integer   |    否    |
  | pageNumber |  Integer   |    否    |

  

## 出参

|  字段   |    类型    |                              值                              |
| :-----: | :--------: | :----------------------------------------------------------: |
| status  |  Integer   |                   1 成功<br />其他表示失败                   |
| message |   String   |                        对status的描述                        |
|  data   | JsonObject | {<br />bean:ReceiveEnt <br />page:`Page<ReceiveEnt>` <br />pageParams:`Map<String, Object>` <br />} |

