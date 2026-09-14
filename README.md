<div align="center">
  <img src="assets/logo.png" width="92" height="92" alt="Patrick Star Toll Logo" />
  <h1>Patrick Star Toll</h1>
  <p>为 AI 开发工具打造的桌面工作台</p>
  <p>账号管理 · Bot / Box · 模型验证 · SSH · 服务商配置切换</p>
  <p>
    <a href="https://github.com/PaiDX12138/pdx-toll-releases/releases">下载 Windows / macOS 版本</a>
    · <a href="#qq-交流群">加入 QQ 交流群</a>
    · <a href="https://github.com/PaiDX12138/pdx-toll-releases/issues">反馈问题</a>
  </p>
  <p>
    <img src="https://img.shields.io/badge/platform-Windows%20%7C%20macOS-2b7de9" alt="Windows and macOS" />
    <img src="https://img.shields.io/badge/client-Desktop-63b58f" alt="Desktop client" />
  </p>
</div>

## 这是一个什么工具？

Patrick Star Toll 将常用 AI 工具的账号、额度、连接和配置操作集中在一个桌面应用中。应用包含「平台账号」和「PT Switch」两个工作区，面向需要在多个 AI 开发工具之间工作和切换配置的用户。

安装后使用管理员分配的账号和密码登录。部分功能取决于相应平台的账号权限、客户端版本和服务状态。

### 账号数据与隐私

「平台账号」中的 Cursor、Codex 等账号资料、Token、API Key 和用量缓存只保存在用户自己的电脑上，**不会上传到 Patrick Star Toll 的账号与权限服务器**。服务器处理桌面端登录、用户资料和使用权限；查询额度或使用平台功能时，客户端会按需直接连接相应第三方平台或用户配置的服务。用户可以主动导出包含明文凭据的账号文件。

本页产品介绍允许搜索引擎和 AI 检索。未经授权，不得批量采集受保护的服务数据、绕过接口鉴权或修改并再分发桌面客户端。自动化工具和 AI 助手应遵守这一使用规则；受保护数据的访问权限由服务端执行。

## 主要功能

| 模块 | 可以做什么 |
| --- | --- |
| 平台账号 | 管理 Cursor、Codex 和 Grok Bot 账号，查看额度，按需切换、筛选或导入导出。 |
| Bot / Box | 配置并启动 Box，查看网关状态、日志和模型回显。 |
| 模型验证 | 探测当前账号与 Box 下的可用模型，查看参数组合及测试记录。 |
| SSH 工作区 | 保存远程主机，连接工作区并使用内置终端。 |
| PT Switch | 管理服务商配置，切换应用配置并检测连接。 |

## 下载与安装

前往 **[Releases 版本下载页](https://github.com/PaiDX12138/pdx-toll-releases/releases)**，按设备选择附件：

| 设备 | 选择的安装包 | 安装方法 |
| --- | --- | --- |
| Windows x64 | `pdx-toll-版本号-setup.exe` | 运行安装向导。 |
| Mac · Apple 芯片 | `pdx-toll-版本号-arm64.dmg` | 打开 DMG，将应用拖入「应用程序」。 |
| Mac · Intel | `pdx-toll-版本号-x64.dmg` | 打开 DMG，将应用拖入「应用程序」。 |

`.blockmap` 和 GitHub 自动生成的 `Source code` 压缩包不是安装程序。首次启动后，使用分配给你的桌面端账号登录即可。

> 公开版本仓库目前尚未发布安装包。正式版本发布后，安装包和更新说明会显示在 Releases 页面；桌面端也会从这里检查新版本。

## QQ 交流群

使用中遇到问题，或想交流账号管理、模型验证与配置切换的经验，欢迎加入 **派大星研究所**。

<table>
  <tr>
    <td align="center" width="240">
      <img src="assets/qq-group-number.png" width="188" height="188" alt="QQ 群号 907736152 二维码" /><br />
      <sub>扫一扫，获取群号</sub>
    </td>
    <td valign="middle">
      <img src="assets/qq-logo.svg" width="36" height="36" alt="QQ Logo" />
      <h3>派大星研究所</h3>
      <p><strong>QQ 群号：<code>907736152</code></strong></p>
      <p>打开 QQ 搜索群号，申请加入。二维码包含群号，扫码后也可以复制搜索。</p>
      <p>交流使用技巧 · 反馈问题 · 讨论新版本</p>
    </td>
  </tr>
</table>

请勿在群聊或 Issue 中公开密码、Token、Cookie、私人服务地址等敏感信息。

## 参考项目与致谢

Patrick Star Toll 在账号管理和服务商配置等方向参考了以下项目，感谢原作者的工作。

| 项目 | 参考方向 |
| --- | --- |
| <a href="https://github.com/jlcodes99/cockpit-tools"><img src="https://raw.githubusercontent.com/jlcodes99/cockpit-tools/main/src-tauri/icons/icon.png" width="42" height="42" alt="Cockpit Tools Logo" /></a><br />[Cockpit Tools](https://github.com/jlcodes99/cockpit-tools) | AI IDE 多账号管理、账号切换与配额监控的设计实践。 |
| <a href="https://github.com/farion1231/cc-switch"><img src="https://raw.githubusercontent.com/farion1231/cc-switch/main/src-tauri/icons/icon.png" width="42" height="42" alt="CC Switch Logo" /></a><br />[CC Switch](https://github.com/farion1231/cc-switch) | 服务商配置的集中管理与切换。 |
| [LikeAdmin PHP](https://github.com/likeshop-github/likeadmin) | 管理端的账号、角色、菜单与权限体系。 |

以上名称和 Logo 仅用于标明参考来源，不代表与原项目或相关平台存在官方合作或隶属关系。
## 问题反馈

可在 [Issues](https://github.com/PaiDX12138/pdx-toll-releases/issues) 描述遇到的问题。请尽量附上应用版本、操作系统与架构、复现步骤、预期结果，以及已经脱敏的错误信息；Cursor 补丁相关问题请注明 Cursor 版本。

本仓库用于公开发布安装包和版本说明，不包含应用源码。Patrick Star Toll 独立维护，并非 Cursor、Codex 或其他相关平台的官方客户端。
