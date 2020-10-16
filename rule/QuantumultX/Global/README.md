# Global

## 前言

本项目的Global分流规则由爬虫程序自动维护。

定时爬取互联网上开源的Global分流规则，将其进行清洗、去重、合并、优化后，形成单一的分流规则文件，旨在解决引用大量外部规则造成规则重复的问题。


最后检查时间：2020-10-16 23:33:51。

## 规则统计

总计规则：842 条。

各类型规则统计：

| 类型 | 数量(条) |
| ---- | ---- |
| DOMAIN | 61 |
| DOMAIN-KEYWORD | 18 |
| DOMAIN-SUFFIX | 692 |
| IP-CIDR | 29 |
| IP-CIDR6 | 3 |
| URL-REGEX | 1 |
| USER-AGENT | 38 |
## 重复统计

Global分流规则，与本项目其他分流规则重复情况统计。

点击重复数量可以查看重复规则明细。

| 名称 | 数量 | 重复 | 重合度 |
| ---- | ---- | ---- | ------ |
|  [Adobe](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/QuantumultX/Adobe)    | 34   | [1](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Repeat/Global/Adobe.list)   |   2.94%  |
|  [Advertising](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/QuantumultX/Advertising)    | 157435   | [7](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Repeat/Global/Advertising.list)   |   0.00%  |
|  [AdvertisingLite](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/QuantumultX/AdvertisingLite)    | 131289   | [3](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Repeat/Global/AdvertisingLite.list)   |   0.00%  |
|  [AppStore](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/QuantumultX/AppStore)    | 2   | [2](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Repeat/Global/AppStore.list)   |   100.00%  |
|  [Apple](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/QuantumultX/Apple)    | 51   | [3](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Repeat/Global/Apple.list)   |   5.88%  |
|  [AppleBlock](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/QuantumultX/AppleBlock)    | 6   | [6](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Repeat/Global/AppleBlock.list)   |   100.00%  |
|  [AppleNews](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/QuantumultX/AppleNews)    | 9   | [1](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Repeat/Global/AppleNews.list)   |   11.11%  |
|  [Bahamut](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/QuantumultX/Bahamut)    | 5   | [5](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Repeat/Global/Bahamut.list)   |   100.00%  |
|  [BlackList](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/QuantumultX/BlackList)    | 778   | [236](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Repeat/Global/BlackList.list)   |   30.33%  |
|  [China](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/QuantumultX/China)    | 593   | [4](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Repeat/Global/China.list)   |   0.67%  |
|  [Discord](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/QuantumultX/Discord)    | 6   | [3](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Repeat/Global/Discord.list)   |   50.00%  |
|  [Download](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/QuantumultX/Download)    | 11   | [1](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Repeat/Global/Download.list)   |   9.09%  |
|  [Dubox](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/QuantumultX/Dubox)    | 2   | [2](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Repeat/Global/Dubox.list)   |   100.00%  |
|  [Facebook](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/QuantumultX/Facebook)    | 25   | [25](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Repeat/Global/Facebook.list)   |   100.00%  |
|  [PayPal](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/QuantumultX/PayPal)    | 5   | [3](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Repeat/Global/PayPal.list)   |   60.00%  |
|  [Steam](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/QuantumultX/Steam)    | 16   | [1](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Repeat/Global/Steam.list)   |   6.25%  |
|  [Game](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/QuantumultX/Game)    | 28   | [4](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Repeat/Global/Game.list)   |   14.29%  |
|  [Google](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/QuantumultX/Google)    | 64   | [56](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Repeat/Global/Google.list)   |   87.50%  |
|  [YouTube](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/QuantumultX/YouTube)    | 14   | [9](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Repeat/Global/YouTube.list)   |   64.29%  |
|  [Microsoft](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/QuantumultX/Microsoft)    | 99   | [10](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Repeat/Global/Microsoft.list)   |   10.10%  |
|  [Niconico](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/QuantumultX/Niconico)    | 5   | [5](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Repeat/Global/Niconico.list)   |   100.00%  |
|  [Speedtest](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/QuantumultX/Speedtest)    | 5   | [1](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Repeat/Global/Speedtest.list)   |   20.00%  |
|  [Telegram](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/QuantumultX/Telegram)    | 20   | [16](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Repeat/Global/Telegram.list)   |   80.00%  |
|  [Netflix](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/QuantumultX/Netflix)    | 40   | [28](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Repeat/Global/Netflix.list)   |   70.00%  |
|  [Pornhub](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/QuantumultX/Pornhub)    | 4   | [4](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Repeat/Global/Pornhub.list)   |   100.00%  |
|  [Disney](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/QuantumultX/Disney)    | 7   | [6](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Repeat/Global/Disney.list)   |   85.71%  |
|  [GlobalMedia](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/QuantumultX/GlobalMedia)    | 296   | [193](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Repeat/Global/GlobalMedia.list)   |   65.20%  |
|  [Github](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/QuantumultX/Github)    | 6   | [4](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Repeat/Global/Github.list)   |   66.67%  |
|  [Spotify](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/QuantumultX/Spotify)    | 8   | [7](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Repeat/Global/Spotify.list)   |   87.50%  |
|  [Spark](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/QuantumultX/Spark)    | 4   | [2](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Repeat/Global/Spark.list)   |   50.00%  |
|  [TestFlight](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/QuantumultX/TestFlight)    | 3   | [1](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Repeat/Global/TestFlight.list)   |   33.33%  |
|  [Twitter](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/QuantumultX/Twitter)    | 11   | [10](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Repeat/Global/Twitter.list)   |   90.91%  |
|  [Proxy](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/QuantumultX/Proxy)    | 5984   | [514](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Repeat/Global/Proxy.list)   |   8.59%  |
|  [YouTubeMusic](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/QuantumultX/YouTubeMusic)    | 4   | [2](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Repeat/Global/YouTubeMusic.list)   |   50.00%  |
|  [Instagram](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/QuantumultX/Instagram)    | 2   | [2](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Repeat/Global/Instagram.list)   |   100.00%  |
|  [Wikipedia](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/QuantumultX/Wikipedia)    | 12   | [5](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Repeat/Global/Wikipedia.list)   |   41.67%  |
## 配置说明

实时版：爬虫程序定时更新，更新频率高，能尽快同步数据源变化

稳定版：不定时手动更新，更新频率低，稳定性好

### QuantumultX 
实时版：

https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/QuantumultX/Global/Global.list

稳定版：

https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/release/rule/QuantumultX/Global/Global.list

## 数据来源

本项目的Global分流规则的数据来自以下链接，通常已涵盖所有数据来源的分流规则。如果你正在使用这些分流规则，请先删除后再使用本项目的Global分流规则，以免造成规则重复。

- https://raw.githubusercontent.com/ConnersHua/Profiles/master/Surge/Ruleset/Global.list
- https://raw.githubusercontent.com/ConnersHua/Profiles/master/Surge/Ruleset/GlobalMedia.list
- https://raw.githubusercontent.com/DivineEngine/Profiles/master/Surge/Ruleset/Global.list
- https://raw.githubusercontent.com/eHpo1/Rules/master/Surge4/Ruleset/Global.list


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

欢迎通过[issues](https://github.com/blackmatrix7/ios_rule_script/issues/new)提交反馈，共同完善本项目的Global分流规则。

感谢

[@zjcfynn](https://github.com/zjcfynn) [@Tartarus2014](https://github.com/Tartarus2014)

提供规则数据及改进建议