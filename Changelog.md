V1.2.1 (2018-11-09)

* Update

1. 日志优化，减少输入打印的日志

* Fix

1. 解决Tomcat重启之后的交易表主键冲突的错误

* Delete

1. 删除历史版本中多余的文件和代码



V1.2.0 (2018-05-31)

- Update

1. 提升部署脚本的易用性
2. 增加ReportAgent的可用性
3. 调整路径的命名方式，更加亲近开源

- Add
1. 增加LICENSE
2. 增加代码的文件头和开发人员

- Fix
1. 修复出块者为00000000的bug（与FISCO-BCOS v1.2.0对应）
2. 修复一些安全性漏洞 

V1.1.0 (2018-03-28)

- Update

1. 可通过页面配置多个需要监控的区块链节点。
2. 支持监控节点是否存活。
3. server端调整为通过tomcat启动，可接收监控agent上报的数据。
4. 数据库增加更多的表。

- Add

1. 一键部署脚本。
2. 支持监控多个节点的各种指标（单点统计）。
3. 支持监控区块出块流程（共识流）。
4. 支持监控交易的上链过程（交易流）。
5. 增加Report Agent，通过在每个部署了区块链节点的机器上部署Report Agent，监控区块链节点。

- Fix

1. 修改数据库建表脚本，修复某些情况下无法识别中文注释的bug。
2. 修复交易param较大导致无法写入数据库的bug。
3. 修改一些可能引起歧义的错误输出。

