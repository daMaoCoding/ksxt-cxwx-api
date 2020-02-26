# 入参

* url:```https://2858y3h397.qicp.vip/cxwx/order/order2```

* type:GET

* params:

  

  |    字段     |  类型   | 是否必填 |
  | :---------: | :-----: | :------: |
  |    token    | String  |    是    |
  |    order    |  Order  |    否    |
  |  pageSize   | Integer |    否    |
  | currentPage | Integer |    否    |

# 出参

| 字段    | 类型       | 值                                                           |
| ------- | ---------- | ------------------------------------------------------------ |
| status  | Integer    | 1 成功，其他失败                                             |
| message | String     | 对status的描述                                               |
| data    | JsonObject | {<br/>	"status": "0 或者1",<br/>	"message": "status对应的描述",<br/>	"orderSet": [{<br/>			"name": "aaa"<br/>		},<br/>		{<br/>			"name": "bbb"<br/>		}<br/>	],<br/>	"orderList": [{<br/>		"id": 1,<br/>		"name": "aaa"<br/>	}],<br/>	"order": {<br/>		"id": "xxx",<br/>		"name": " xxx"<br/>	},<br/>	"page": {<br/>		"pageSize": 10,<br/>		"pageNumber": 1,<br/>		"totalCount": 100,<br/>		"pageCount": 10<br/>	}<br/>} |

