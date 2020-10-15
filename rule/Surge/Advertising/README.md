# 去广告

## 前言

本项目的去广告分流规则由爬虫程序自动维护。

定时爬取互联网上开源的去广告分流规则，将其进行清洗、去重、合并、优化后，形成单一的分流规则文件，旨在解决引用大量外部规则造成规则重复的问题。

本分流规则不包含任何知乎去广告规则。

最后检查时间：2020-10-15 14:49:05。

## 规则统计

总计规则：156031 条。

各类型规则统计：

| 类型 | 数量(条) |
| ---- | ---- |
| DOMAIN | 112970 |
| DOMAIN-KEYWORD | 55 |
| DOMAIN-SUFFIX | 42433 |
| IP-CIDR | 232 |
| URL-REGEX | 341 |
## 重复统计

去广告分流规则，与本项目其他分流规则重复情况统计。

点击重复数量可以查看重复规则明细。

| 名称 | 数量 | 重复 | 重合度 |
| ---- | ---- | ---- | ------ |
|  [AdvertisingLite](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Surge/AdvertisingLite)    | 131289   | [131289](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Repeat/Advertising/AdvertisingLite.list)   |   100.00%  |
|  [China](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Surge/China)    | 593   | [10](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Repeat/Advertising/China.list)   |   1.69%  |
|  [WhiteList](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Surge/WhiteList)    | 6   | [1](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Repeat/Advertising/WhiteList.list)   |   16.67%  |
|  [BlackList](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Surge/BlackList)    | 778   | [24](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Repeat/Advertising/BlackList.list)   |   3.08%  |
|  [Youtube](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Surge/Youtube)    | 14   | [1](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Repeat/Advertising/Youtube.list)   |   7.14%  |
|  [Apple](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Surge/Apple)    | 49   | [1](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Repeat/Advertising/Apple.list)   |   2.04%  |
|  [Global](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Surge/Global)    | 842   | [7](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Repeat/Advertising/Global.list)   |   0.83%  |
|  [GlobalMedia](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Surge/GlobalMedia)    | 192   | [1](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Repeat/Advertising/GlobalMedia.list)   |   0.52%  |
|  [Hijacking](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Surge/Hijacking)    | 209   | [209](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Repeat/Advertising/Hijacking.list)   |   100.00%  |
|  [ChinaMedia](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Surge/ChinaMedia)    | 75   | [1](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Repeat/Advertising/ChinaMedia.list)   |   1.33%  |
|  [Privacy](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Surge/Privacy)    | 28   | [9](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Repeat/Advertising/Privacy.list)   |   32.14%  |
|  [NetEaseMusic](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Surge/NetEaseMusic)    | 41   | [1](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Repeat/Advertising/NetEaseMusic.list)   |   2.44%  |
|  [Proxy](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Surge/Proxy)    | 773   | [24](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Repeat/Advertising/Proxy.list)   |   3.10%  |
## 配置说明

实时版：爬虫程序定时更新，更新频率高，能尽快同步数据源变化

稳定版：不定时手动更新，更新频率低，稳定性好

### Surge 
实时版：

https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Surge/Advertising/Advertising.list

https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Surge/Advertising/Domain.list

稳定版：

https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/release/rule/Surge/Advertising/Advertising.list

https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/release/rule/Surge/Advertising/Domain.list

### 特别说明

Advertising.list请使用RULE-SET，Domain.list请使用DOMAIN-SET。

## 数据来源

本项目的去广告分流规则的数据来自以下链接，通常已涵盖所有数据来源的分流规则。如果你正在使用这些分流规则，请先删除后再使用本项目的去广告分流规则，以免造成规则重复。

- https://raw.githubusercontent.com/NobyDa/ND-AD/master/QuantumultX/AD_Block.txt
- https://raw.githubusercontent.com/NobyDa/ND-AD/master/QuantumultX/AD_Block_Plus.txt
- https://raw.githubusercontent.com/NobyDa/ND-AD/master/Surge/AD_Block.txt
- https://raw.githubusercontent.com/NobyDa/ND-AD/master/Surge/AD_Block_Add.txt
- https://raw.githubusercontent.com/NobyDa/ND-AD/master/Surge/AD_Block_Plus.txt
- https://raw.githubusercontent.com/NobyDa/Script/master/QuantumultX/AdRule.list
- https://raw.githubusercontent.com/NobyDa/Script/master/QuantumultX/AdRuleTest.list
- https://raw.githubusercontent.com/NobyDa/Script/master/Surge/AdRule.list
- https://raw.githubusercontent.com/NobyDa/Script/master/Surge/AdRuleTest.list
- https://raw.githubusercontent.com/DivineEngine/Profiles/master/Surge/Ruleset/Guard/Advertising.list
- https://raw.githubusercontent.com/DivineEngine/Profiles/master/Quantumult/Filter/Guard/Advertising.list
- https://raw.githubusercontent.com/ConnersHua/Profiles/master/Surge/Ruleset/Hijacking.list
- https://raw.githubusercontent.com/ConnersHua/Profiles/master/Surge/Ruleset/Advertising.list
- https://raw.githubusercontent.com/eHpo1/Rules/master/QuantumultX/Filter/Liby.txt
- https://raw.githubusercontent.com/eHpo1/Rules/master/Surge4/Ruleset/Liby.list
- https://raw.githubusercontent.com/eHpo1/Rules/master/Surge4/Ruleset/Tide.list
- https://raw.githubusercontent.com/scomper/surge-list/master/reject.list
- https://raw.githubusercontent.com/scomper/surge-list/master/adblock.list
- https://raw.githubusercontent.com/nzw9314/Surge/master/Ruleset/Tide.list
- https://raw.githubusercontent.com/lhie1/Rules/master/Surge/Surge%203/Provider/Reject.list
- https://raw.githubusercontent.com/privacy-protection-tools/anti-AD/master/anti-ad-surge.txt
- https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/source/rule/Advertising/LianXiangJia/LianXiangJia.list
- https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/source/connershua/Quantumult/X/Filter/Advertising.list


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

欢迎通过[issues](https://github.com/blackmatrix7/ios_rule_script/issues/new)提交反馈，共同完善本项目的去广告分流规则。

感谢

[@zjcfynn](https://github.com/zjcfynn)

提供规则数据及改进建议