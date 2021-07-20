# conflux-rpc-doc

访问[可交互的 OPEN-RPC 在线文档](https://playground.open-rpc.org/?schemaUrl=https://raw.githubusercontent.com/darwintree/conflux-openrpc/main/static/conflux-openrpc.json&uiSchema[appBar][ui:splitView]=false)

Visit [here](https://playground.open-rpc.org/?schemaUrl=https://raw.githubusercontent.com/darwintree/conflux-openrpc/main/static/conflux-openrpc.json&uiSchema[appBar][ui:splitView]=false) for real-time interaction

## RPC 文档问题

### 样例

部分样例在主网下无法运行，现在大部分无法运行的已经更改为可运行的版本了，但目前仍有部分样例无法运行 / 样例意义较小, 之后需要再进行构造

- `cfx_call` 当前样例无法运行
- `cfx_getDepositList` `cfx_getVoteList` 当前样例只会返回空值
- `getLogs` 参数的 `topics` 字段当前置空

### 文档缺失报错部分内容

现在缺少报错的错误码相关说明

例如 `cfx_getCode` `cfx_call` `cfx_getLogs` `estimate` 等
