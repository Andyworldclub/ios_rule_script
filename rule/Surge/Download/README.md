# 下载

## 前言

本项目的下载分流规则由爬虫程序自动维护。

定时爬取互联网上开源的下载分流规则，将其进行清洗、去重、合并、优化后，形成单一的分流规则文件，旨在解决引用大量外部规则造成规则重复的问题。


最后检查时间：2020-10-16 23:33:50。

## 规则统计

总计规则：11 条。

各类型规则统计：

| 类型 | 数量(条) |
| ---- | ---- |
| DOMAIN | 1 |
| DOMAIN-KEYWORD | 5 |
| DOMAIN-SUFFIX | 1 |
| URL-REGEX | 4 |
## 重复统计

下载分流规则，与本项目其他分流规则重复情况统计。

点击重复数量可以查看重复规则明细。

| 名称 | 数量 | 重复 | 重合度 |
| ---- | ---- | ---- | ------ |
|  [Apple](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Surge/Apple)    | 51   | [1](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Repeat/Download/Apple.list)   |   1.96%  |
|  [AppleBlock](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Surge/AppleBlock)    | 6   | [1](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Repeat/Download/AppleBlock.list)   |   16.67%  |
|  [AppleNews](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Surge/AppleNews)    | 9   | [1](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Repeat/Download/AppleNews.list)   |   11.11%  |
|  [BlackList](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Surge/BlackList)    | 778   | [1](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Repeat/Download/BlackList.list)   |   0.13%  |
|  [Microsoft](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Surge/Microsoft)    | 99   | [1](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Repeat/Download/Microsoft.list)   |   1.01%  |
|  [Global](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Surge/Global)    | 842   | [1](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Repeat/Download/Global.list)   |   0.12%  |
## 配置说明

实时版：爬虫程序定时更新，更新频率高，能尽快同步数据源变化

稳定版：不定时手动更新，更新频率低，稳定性好

### Surge 
实时版：

https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Surge/Download/Download.list

稳定版：

https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/release/rule/Surge/Download/Download.list

## 数据来源

本项目的下载分流规则的数据来自以下链接，通常已涵盖所有数据来源的分流规则。如果你正在使用这些分流规则，请先删除后再使用本项目的下载分流规则，以免造成规则重复。

- https://raw.githubusercontent.com/NobyDa/Script/master/Surge/Download.list
- https://raw.githubusercontent.com/ACL4SSR/ACL4SSR/master/Clash/Download.list


感谢以上分流规则作者的辛勤付出（排名不分先后）。

如果你有更好的分流规则，欢迎提交给我，我会将它加到数据源中继续完善。

## 最后

### 正则过滤

爬虫程序在清洗原始规则数据时，可根据正则定向过滤规则，以达到保留特定规则的目的。经过正则过滤的规则，无法100%涵盖原始规则数据，请知悉。

### 黑名单

爬虫程序内置部分规则黑名单，在对原始数据进行清洗时，自动将可能引起异常的黑名单规则去除。经过黑名单去除的规则，无法100%涵盖原始规则数据，请知悉。

### 完善规则

如果你：

1. 有更优的原始规则数据
2. 有更多的黑名单规则数据
3. 有更好的优化建议
4. 在使用分流规则时出现异常
5. 有其他问题

欢迎通过[issues](https://github.com/blackmatrix7/ios_rule_script/issues/new)提交反馈，共同完善本项目的下载分流规则。

感谢

[@zjcfynn](https://github.com/zjcfynn) [@Tartarus2014](https://github.com/Tartarus2014)

提供规则数据及改进建议