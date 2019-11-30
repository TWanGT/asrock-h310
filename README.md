# asrock-Deskmini-h310-hackintosh-EFI

本仓库提供黑苹果的引导文件(clover和oc都有)

理论上同配置的可以直接用(需要修改下3码, 以防handoff, icloud等苹果功能不正常)

## 本人机器配置如下
类型|型号|价格|购买渠道
-|-|-|-
cpu|i5 8400散片|1068|淘宝
主板|DeskMini 310|999|京东
机箱|主板包含|0|京东
电源|主板包含|0|京东
内存|威刚16g 2666|539|京东
内存2|威刚16g 2666|499|京东
cpu散热器|大镰刀十手8039双风扇|189|淘宝
nvme硬盘|西数黑盘sn720 500g|799|京东
wifi和蓝牙|94360cs2|115|淘宝

详情请跳转[链接](https://blog.csdn.net/qq_34208844/article/details/90232888)

## 使用说明
oc 和 clover 2选一, 将EFI文件整个考入引导分区(包括EFI文件夹)

clover 和 oc 各有优劣
* clover: 引导界面优美, 更加成熟, 配套工具成熟, 配置简单, 文章资料多
* openCore: 目前任然是beta版本, 但是是未来的趋势, 越来越多的补丁作者宣布后续只维护oc版本, 对10.15系统引导时间快不少, 可以更接近原生苹果的体验(包括恢复模式什么的)