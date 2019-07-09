# Scoop ISZY Bucket [![Build status](https://ci.appveyor.com/api/projects/status/3ays0dwt7k4oc6ko?svg=true)](https://ci.appveyor.com/project/ZvonimirSun/scoop-iszy)

`scoop bucket add iszy 'https://github.com/ZvonimirSun/scoop-iszy.git'`

-   [Scoop bucket Template](https://github.com/Ash258/GenericBucket)
-   [Manifests](#manifests)

## Manifests

| App name **(Scoop name)**                                                                                                              | Tested | Checkver | Autoupdate (Hash) |
| -------------------------------------------------------------------------------------------------------------------------------------- | :----: | :------: | :---------------: |
| [Clash for Windows **(clash)**](./bucket/clash.json)                                                                                   |   ✔    |    ✔     |      ✔ (⛔)       |
| [Meow **(meow)**](./bucket/meow.json)                                                                                                  |   ✔    |    ✔     |      ✔ (⛔)       |
| [Office Tool Plus **(office-tool)**](./bucket/office-tool.json)                                                                        |   ✔    |    ✔     |      ✔ (⛔)       |
| [万彩办公大师 **(officebox)**](./bucket/officebox.json)                                                                                |   ✔    |    ✔     |      ✔ (⛔)       |
| [微信 **(wechat)**](./bucket/wechat.json)                                                                                              |   ✔    |    ✔     |      ✔ (⛔)       |
| [Winrar **(winrar-sc)**](./bucket/winrar-sc.json)                                                                                      |   ✔    |    ✔     |      ⛔ (⛔)      |
| [Tim **(tim)**](./bucket/tim.json)                                                                                                     |  🎃🔶  |    ✔     |      ✔ (⛔)       |
| [Oracle JDK 8 **(oraclejdk8)**](./bucket/oraclejdk8.json)                                                                              |   ✔    |    ✔     |      ✔ (⛔)       |
| [PicGo **(picgo)**](./bucket/picgo.json)(from [helbing/scoop-bucket](https://github.com/helbing/scoop-bucket))                         |   ✔    |    ✔     |      ✔ (⛔)       |
| [企业微信 **(wechat-work)**](./bucket/wechat-work.json)                                                                                |   ✔    |    ✔     |      ✔ (⛔)       |
| [pgAdmin 4 **(pgadmin4-np)**](./bucket/pgadmin4-np.json)(from [oltolm/scoop-nonportable](https://github.com/oltolm/scoop-nonportable)) |   ✔    |    ✔     |      ✔ (⛔)       |

## TODO

| App name **(Scoop name)** | Tested | Checkver | Autoupdate (Hash) |
| ------------------------- | :----: | :------: | :---------------: |
| N/A                       |        |          |                   |

-   🔶 Additional testing is needed
-   ⭕ Not needed
-   ⛔ Not possible (need download)
-   ♻ Nightly
-   🎃 Installers have their own mind
    -   Basicly manifests which break my philosophy of no hurt mode.
        -   No Registry
        -   No junk files creating
        -   ...
    -   Installing is needed in some cases and path cannot be changed.
