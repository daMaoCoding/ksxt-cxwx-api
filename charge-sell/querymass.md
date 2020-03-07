# 入参

* url：```https://2858y3h397.qicp.vip/cxwx/receiveEntRecharge/queryMass```
* type:GET
* params:

| 字段          | 类型    | 是否必填 |
| ------------- | ------- | -------- |
| token         | string  | 是       |
| receiveEntId1 | string  | 是       |
| startTime1    | string  | 是       |
| endTime1      | string  | 是       |
| pageSize      | Integer | 否       |
| pageNumber    | Integer | 否       |



# 出参

| 字段    | 类型       | 值                                                           |
| ------- | ---------- | ------------------------------------------------------------ |
| status  | Integer    | 1 成功<br />其他值失败                                       |
| message | string     | status的描述                                                 |
| data    | JsonObject | {<br />bean:ReceiveEntRecharge<br />pageParams:`Map<String,Object>`<br />page:`Page<ReceiveEntRecharge>`<br />lsitent:`List<ReceiveEnt>`<br />end:endTime<br />sta:startTime<br />} |

# 示例

* 请求

>`https://2858y3h397.qicp.vip/cxwx/receiveEntRecharge/queryMass?token=123456&receiveEntId1=0bd88dc0593d11ea12bd32d1c58070fe&startTime1=2020-01-01&endTime1=2020-03-07&pageSize=10&pageNumber=1`

* 响应

>{
>  "state" : 1,
>  "message" : "OK",
>  "data" : {
>    "pageParams" : {
>      "xjMoney" : 0,
>      "giveMoney" : 0,
>      "receiveEntId1" : "0bd88dc0593d11ea12bd32d1c58070fe",
>      "mineralPrice" : 0,
>      "pageEnd" : 0,
>      "pageStart" : 0,
>      "useAccount" : 0,
>      "startTime" : "2020-01-01 00:00:00",
>      "endTime" : "2020-03-07 23:59:59",
>      "accountBalance" : 0
>    },
>    "sta" : "2020-01-01",
>    "end" : "2020-03-07",
>    "page" : {
>      "pageNumber" : 1,
>      "pageSize" : 10,
>      "totalCount" : 0,
>      "pageCount" : 0,
>      "content" : [ ],
>      "param" : { }
>    },
>    "lsitent" : [ {
>      "excludeOperateId" : null,
>      "dealUserId" : null,
>      "states" : null,
>      "order" : null,
>      "pageSize" : null,
>      "currentPage" : null,
>      "id" : "be123e4085cc11e9491b8e73bcd21860",
>      "taxpayerCode" : null,
>      "name" : "陈波",
>      "legalPerson" : null,
>      "contacts" : null,
>      "mobile" : null,
>      "coOwner" : null,
>      "validity" : null,
>      "status" : 1,
>      "entId" : "0fa929207ae311e974b14704957c2a21",
>      "address" : null,
>      "remark" : null,
>      "createTime" : 1559545002200,
>      "creater" : null,
>      "modifyTime" : null,
>      "modifier" : null,
>      "accountBalance" : null,
>      "entNo" : null,
>      "chargeStatus" : null,
>      "receiveEntId" : null,
>      "isPreDeposit" : null,
>      "rechargeAccount" : null,
>      "giveMoney" : null,
>      "ids" : null
>    }
>  }
>}

