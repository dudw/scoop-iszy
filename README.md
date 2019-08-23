# Scoop ISZY Bucket [![Build status](https://ci.appveyor.com/api/projects/status/3ays0dwt7k4oc6ko/branch/master?svg=true)](https://ci.appveyor.com/project/ZvonimirSun/scoop-iszy)

`scoop bucket add iszy 'https://github.com/ZvonimirSun/scoop-iszy.git'`

个人使用，软件版本可能更新不及时，如果介意可以 fork 一份，自己保持更新。本 Repository 采用 Ash258 大佬的项目模板，大部分内容已写 checkver 和 autoupdate 语句，可通过 Ash258 大佬已经写好的脚本自动更新。

-   [Scoop bucket 模板](https://github.com/Ash258/GenericBucket)
-   [Manifests](#manifests)

## Manifests

### 原创

| 应用名称                                                                                     |                         Scoop 内名称                         |
| -------------------------------------------------------------------------------------------- | :----------------------------------------------------------: |
| [Clash for Windows](https://github.com/Fndroid/clash_for_windows_pkg)                        |                 [clash](./bucket/clash.json)                 |
| [LAV Filters](https://github.com/Nevcairiel/LAVFilters)                                      |            [lavfilters](./bucket/lavfilters.json)            |
| [Meow](https://github.com/ZvonimirSun/MEOW)                                                  |                  [meow](./bucket/meow.json)                  |
| [Office Tool Plus](https://otp.landian.vip/zh-cn/)                                           |           [office-tool](./bucket/office-tool.json)           |
| [万彩办公大师](http://www.wofficebox.com/)                                                   |             [officebox](./bucket/officebox.json)             |
| [Oracle Instant Client](https://www.oracle.com/database/technologies/instant-client.html)    |   [OracleInstantClient](./bucket/OracleInstantClient.json)   |
| [Oracle Instant Client 11](https://www.oracle.com/database/technologies/instant-client.html) | [OracleInstantClient11](./bucket/OracleInstantClient11.json) |
| [Oracle JDK 8](https://www.oracle.com/technetwork/java/javase/overview/index.html)           |            [oraclejdk8](./bucket/oraclejdk8.json)            |
| [Tim](https://office.qq.com/)                                                                |                   [tim](./bucket/tim.json)                   |
| [微信](https://pc.weixin.qq.com/)                                                            |                [wechat](./bucket/wechat.json)                |
| [企业微信](https://work.weixin.qq.com/)                                                      |           [wechat-work](./bucket/wechat-work.json)           |
| [WinRAR](https://www.win-rar.com/)                                                           |             [winrar-sc](./bucket/winrar-sc.json)             |

### 收集

| 应用名称                                      |                 Scoop 内名称                 | 来源                                                                    |
| --------------------------------------------- | :------------------------------------------: | ----------------------------------------------------------------------- |
| [网易云音乐](https://music.163.com/)          | [netease-music](./bucket/netease-music.json) | [h404bi/dorado](https://github.com/h404bi/dorado)                       |
| [Origin EA](https://www.origin.com/)          |        [origin](./bucket/origin.json)        | [Ash258/scoop-Ash258](https://github.com/Ash258/scoop-Ash258)           |
| [pgAdmin 4](https://www.pgadmin.org)          |   [pgadmin4-np](./bucket/pgadmin4-np.json)   | [oltolm/scoop-nonportable](https://github.com/oltolm/scoop-nonportable) |
| [PicGo](https://github.com/Molunerfinn/PicGo) |         [picgo](./bucket/picgo.json)         | [helbing/scoop-bucket](https://github.com/helbing/scoop-bucket)         |
| [PotPlayer](https://potplayer.daum.net)       |     [potplayer](./bucket/potplayer.json)     | [Ash258/scoop-Ash258](https://github.com/Ash258/scoop-Ash258)           |
| [Uplay 育碧](https://uplay.ubi.com/)          |         [uplay](./bucket/uplay.json)         | [Ash258/scoop-Ash258](https://github.com/Ash258/scoop-Ash258)           |

**收集理由：**

-   个人使用，不喜欢添加太多 bucket
-   可能原 bucket 更新不够及时
