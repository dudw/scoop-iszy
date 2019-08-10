# Scoop ISZY Bucket [![Build status](https://ci.appveyor.com/api/projects/status/3ays0dwt7k4oc6ko/branch/master?svg=true)](https://ci.appveyor.com/project/ZvonimirSun/scoop-iszy)

`scoop bucket add iszy 'https://github.com/ZvonimirSun/scoop-iszy.git'`

仅用于我个人使用

-   [Scoop bucket 模板](https://github.com/Ash258/GenericBucket)
-   [Manifests](#manifests)

## Manifests

没在这里列举的不是我写的。。。自用 bucket，大家包涵一下啦。。。

| 应用名称 **(Scoop 内名称)**                                                                 | 经过测试 | 自动检测版本 | 自动更新 (Hash) |
| ------------------------------------------------------------------------------------------- | :------: | :----------: | :-------------: |
| [Clash for Windows **(clash)**](./bucket/clash.json)                                        |    ✔     |      ✔       |     ✔ (⛔)      |
| [Meow **(meow)**](./bucket/meow.json)                                                       |    ✔     |      ✔       |     ✔ (⛔)      |
| [Office Tool Plus **(office-tool)**](./bucket/office-tool.json)                             |    ✔     |      ✔       |     ✔ (⛔)      |
| [万彩办公大师 **(officebox)**](./bucket/officebox.json)                                     |    ✔     |      ✔       |     ✔ (⛔)      |
| [微信 **(wechat)**](./bucket/wechat.json)                                                   |    ✔     |      ✔       |     ✔ (⛔)      |
| [Winrar **(winrar-sc)**](./bucket/winrar-sc.json)                                           |   🎃✔    |      ✔       |     ⛔ (⛔)     |
| [Tim **(tim)**](./bucket/tim.json)                                                          |   🎃✔    |      ✔       |     ✔ (⛔)      |
| [Oracle JDK 8 **(oraclejdk8)**](./bucket/oraclejdk8.json)                                   |    ✔     |      ✔       |     ✔ (⛔)      |
| [企业微信 **(wechat-work)**](./bucket/wechat-work.json)                                     |    ✔     |      ✔       |     ✔ (⛔)      |
| [Oracle Instant Client 11 **(OracleInstantClient11)**](./bucket/OracleInstantClient11.json) |    ✔     |      ✔       |     ✔ (⛔)      |
| [Oracle Instant Client **(OracleInstantClient)**](./bucket/OracleInstantClient.json)        |    ✔     |      ✔       |     ✔ (⛔)      |
| [LAV Filters **(lavfilters)**](./bucket/lavfilters.json)                                    |    ✔     |      ✔       |     ✔ (⛔)      |

-   🔶 需要额外测试
-   ⭕ 不需要
-   ⛔ 不存在
-   ♻ 循环版本
-   🎃
    -   会在 Scoop 文件夹外部创建文件
    -   可能使用注册表
    -   可能会需要运行安装程序，且安装目录不可变更
    -   ...
