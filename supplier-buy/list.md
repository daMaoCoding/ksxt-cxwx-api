# 入参

* url：```https://2858y3h397.qicp.vip/cxwx/supplierEnt/list```
* type:GET
* params:

| 字段       | 类型        | 是否必填 |
| ---------- | ----------- | -------- |
| token      | string      | 是       |
| bean       | SupplierEnt | 否       |
| pageSize   | Integer     | 是       |
| pageNumber | Integer     | 是       |



# 出参

| 字段    | 类型       | 值                                                           |
| ------- | ---------- | ------------------------------------------------------------ |
| status  | Integer    | 1 成功<br />其他值失败                                       |
| message | string     | status的描述信息                                             |
| data    | JsonObject | {<br />bean:SupplierEnt<br />pageParams:SupplierEnt类型字段名为key，值为value的map<br />page：Page`<SupplierEnt>`<br />} |

# 示例

* 请求

>`https://2858y3h397.qicp.vip/cxwx/supplierEnt/list?token=123456&pageNumber=1&pageSize=10`

* 响应

>{
>  "state" : 1,
>  "message" : "OK",
>  "data" : {
>    "pageParams" : {
>      "pageNumber" : 1,
>      "pageSize" : 10,
>      "token" : "123456",
>      "status" : 1
>    },
>    "bean" : {
>      "excludeOperateId" : null,
>      "dealUserId" : null,
>      "states" : null,
>      "order" : null,
>      "pageSize" : 10,
>      "currentPage" : null,
>      "id" : null,
>      "taxpayerCode" : null,
>      "name" : null,
>      "legalPerson" : null,
>      "contacts" : null,
>      "mobile" : null,
>      "coOwner" : null,
>      "validity" : null,
>      "status" : 1,
>      "entId" : null,
>      "address" : null,
>      "remark" : null,
>      "createTime" : null,
>      "creater" : null,
>      "modifyTime" : null,
>      "modifier" : null,
>      "accountBalance" : null,
>      "entNo" : null,
>      "chargeStatus" : null,
>      "supplierEndId" : null,
>      "token" : "123456",
>      "pageNumber" : 1,
>      "ids" : null
>    },
>    "page" : {
>      "pageNumber" : 1,
>      "pageSize" : 10,
>      "totalCount" : 0,
>      "pageCount" : 0,
>      "content" : [ {
>        "excludeOperateId" : null,
>        "dealUserId" : null,
>        "states" : null,
>        "order" : null,
>        "pageSize" : null,
>        "currentPage" : null,
>        "id" : "b905a53049b311eae0caf42eb649f56b",
>        "taxpayerCode" : null,
>        "name" : "岑溪市鸿闰沙石加工场（站内固废处理）",
>        "legalPerson" : "1",
>        "contacts" : "21",
>        "mobile" : "12",
>        "coOwner" : null,
>        "validity" : null,
>        "status" : 1,
>        "entId" : "4494f170998611e94b099cbb70e631c3",
>        "address" : null,
>        "remark" : "1",
>        "createTime" : 1581084684370,
>        "creater" : "ea453f3031c011ea4cb9d89742a774d0",
>        "modifyTime" : null,
>        "modifier" : null,
>        "accountBalance" : null,
>        "entNo" : null,
>        "chargeStatus" : 1,
>        "supplierEndId" : "79a44bc097c611e932db06b30d1462b3",
>        "ids" : null
>      }, {
>        "excludeOperateId" : null,
>        "dealUserId" : null,
>        "states" : null,
>        "order" : null,
>        "pageSize" : null,
>        "currentPage" : null,
>        "id" : "732d15505fc211ea2f6a024550129bbd",
>        "taxpayerCode" : null,
>        "name" : "岑溪市超达石业有限公司5",
>        "legalPerson" : "test5",
>        "contacts" : "test5",
>        "mobile" : "13800138000",
>        "coOwner" : null,
>        "validity" : null,
>        "status" : 1,
>        "entId" : "test",
>        "address" : null,
>        "remark" : "test5",
>        "createTime" : 1583509934887,
>        "creater" : "test",
>        "modifyTime" : 1583510633957,
>        "modifier" : "test",
>        "accountBalance" : null,
>        "entNo" : null,
>        "chargeStatus" : 1,
>        "supplierEndId" : "03567AA13E1446C68B3AE3CD50232A31",
>        "ids" : null
>      }, {
>        "excludeOperateId" : null,
>        "dealUserId" : null,
>        "states" : null,
>        "order" : null,
>        "pageSize" : null,
>        "currentPage" : null,
>        "id" : "81313ec05fbc11eac2a9e033bd6eb84f",
>        "taxpayerCode" : null,
>        "name" : "全部",
>        "legalPerson" : "",
>        "contacts" : "",
>        "mobile" : "",
>        "coOwner" : null,
>        "validity" : null,
>        "status" : 1,
>        "entId" : "940a7fa09ec611e9bab3ffee39c72684",
>        "address" : null,
>        "remark" : "",
>        "createTime" : 1583507381420,
>        "creater" : "3f4e653016b711ea5a6df2513cec98d3",
>        "modifyTime" : null,
>        "modifier" : null,
>        "accountBalance" : null,
>        "entNo" : null,
>        "chargeStatus" : 1,
>        "supplierEndId" : "",
>        "ids" : null
>      }, {
>        "excludeOperateId" : null,
>        "dealUserId" : null,
>        "states" : null,
>        "order" : null,
>        "pageSize" : null,
>        "currentPage" : null,
>        "id" : "df86df705fbc11eac2a9e033bd6eb84f",
>        "taxpayerCode" : null,
>        "name" : "岑溪市超达石业有限公司",
>        "legalPerson" : "test2",
>        "contacts" : "test2",
>        "mobile" : "13800138000",
>        "coOwner" : null,
>        "validity" : null,
>        "status" : 1,
>        "entId" : "940a7fa09ec611e9bab3ffee39c72684",
>        "address" : null,
>        "remark" : "test2",
>        "createTime" : 1583507539687,
>        "creater" : "3f4e653016b711ea5a6df2513cec98d3",
>        "modifyTime" : null,
>        "modifier" : null,
>        "accountBalance" : null,
>        "entNo" : null,
>        "chargeStatus" : 1,
>        "supplierEndId" : "03567AA13E1446C68B3AE3CD50232A31",
>        "ids" : null
>      } ],
>      "param" : { }
>    }
>  }
>}
>
>