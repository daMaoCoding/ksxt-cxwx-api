# 入参

* url：```https://2858y3h397.qicp.vip/cxwx/supplierEnt/supplierEntEdit```
* type:GET
* params:

| 字段  | 类型   | 是否必填 |
| ----- | ------ | -------- |
| token | string | 是       |
| id    | String | 是       |



# 出参

| 字段    | 类型       | 值                                                         |
| ------- | ---------- | ---------------------------------------------------------- |
| status  | Integer    | 1 成功<br />其他值失败                                     |
| message | string     | status的描述信息                                           |
| data    | JsonObject | {<br />bean:SupplierEnt<br />list：List<Enterprise><br />} |

# 示例

* 请求

>`https://2858y3h397.qicp.vip/cxwx/supplierEnt/supplierEntEdit?token=123456&id=732d15505fc211ea2f6a024550129bbd`

* 响应

>{
>  "state" : 1,
>  "message" : "OK",
>  "data" : {
>    "bean" : {
>      "excludeOperateId" : null,
>      "dealUserId" : null,
>      "states" : null,
>      "order" : null,
>      "pageSize" : null,
>      "currentPage" : null,
>      "id" : "732d15505fc211ea2f6a024550129bbd",
>      "taxpayerCode" : null,
>      "name" : "岑溪市超达石业有限公司5",
>      "legalPerson" : "test5",
>      "contacts" : "test5",
>      "mobile" : "13800138000",
>      "coOwner" : null,
>      "validity" : null,
>      "status" : 1,
>      "entId" : "test",
>      "address" : null,
>      "remark" : "test5",
>      "createTime" : 1583509934887,
>      "creater" : "test",
>      "modifyTime" : 1583510633957,
>      "modifier" : "test",
>      "accountBalance" : null,
>      "entNo" : null,
>      "chargeStatus" : 1,
>      "supplierEndId" : "03567AA13E1446C68B3AE3CD50232A31",
>      "ids" : null
>    }
>  }
>}
>
>