## UnionBan客户端：Spigot插件

### 项目介绍

UnionBan官网：https://unionban.icu/

申请加入：https://unionban.icu/join-us/

UnionBan中央服务器有一份联合封禁名单。参与此项目的Minecraft服务器安装此Spigot插件。管理员安装此插件，可阻止列入封禁名单的玩家进入服务器，也可以通过此插件修改封禁名单。

### 插件功能

插件不修改服务器的白名单（`whitelist.json`）和黑名单（`banned-players.json`），所有功能仅在插件启用时生效。

#### 基础功能（不需要账号，安装即可使用）

- 封禁列表中的玩家试图进入服务器时将其踢出；
- 管理员为玩家添加白名单时，如果此玩家在封禁列表中，发出警告。

#### 高级功能（需要账号）

- 登录账号；
- 将玩家添加到联合封禁列表中；
- 将玩家从联合封禁列表中移除。

### 参与开发

欢迎提issue或者pull request。

项目使用JDK 1.8和maven，建议使用IDEA。