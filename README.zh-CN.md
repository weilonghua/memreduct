<h1 align="center">Mem Reduct</h1>

<p align="center">
	<a href="README.en.md"><img src="https://img.shields.io/badge/English-111111?style=for-the-badge" alt="English" /></a>
	<a href="README.zh-CN.md"><img src="https://img.shields.io/badge/%E7%AE%80%E4%BD%93%E4%B8%AD%E6%96%87-1677ff?style=for-the-badge" alt="简体中文" /></a>
</p>

<p align="center">
	<a href="https://github.com/weilonghua/memreduct/releases"><img src="https://img.shields.io/github/v/release/weilonghua/memreduct?style=flat-square&include_prereleases&label=version" /></a>
	<a href="https://github.com/weilonghua/memreduct/releases"><img src="https://img.shields.io/github/downloads/weilonghua/memreduct/total.svg?style=flat-square" /></a>
	<a href="https://github.com/weilonghua/memreduct/issues"><img src="https://img.shields.io/github/issues-raw/weilonghua/memreduct.svg?style=flat-square&label=issues" /></a>
	<a href="https://github.com/weilonghua/memreduct/graphs/contributors"><img src="https://img.shields.io/github/contributors/weilonghua/memreduct?style=flat-square" /></a>
	<a href="https://github.com/weilonghua/memreduct/blob/master/LICENSE"><img src="https://img.shields.io/github/license/weilonghua/memreduct?style=flat-square" /></a>
</p>

-------

<p align="center">
	<img src="/images/memreduct.png?cachefix" />
</p>

> 由 `weilonghua` 维护的公开分支。
> 基于 Henry++ 的 Mem Reduct，包含本地稳定性修复、异步清理和构建兼容性调整。

### 简介：
Mem Reduct 是一款轻量级的实时内存管理程序，用于监控并清理电脑上的系统内存。

这个分支保留了原有功能，并增加了清理流程稳定性修复、异步 UI 处理和构建兼容性更新。

程序使用未公开的系统内部特性（Native API）清理系统缓存（system working set、working set、standby page lists、modified page lists），实际效果通常在 10-50% 之间。它兼容 <s>Windows XP SP3</s> Windows 7 SP1 及以上操作系统。

你可以下载安装版或便携版。正常使用需要管理员权限。

```
要启用便携模式，请在程序目录中创建 "memreduct.ini"，或者从 "%APPDATA%\Henry++\Mem Reduct" 将它移动过来。
```

### 系统要求：
- Windows 7、8、8.1、10、11，64 位/ARM64
- 支持 SSE2 的 CPU
- <s>KB2533623</s> Windows 7 需要 [KB3063858](https://www.microsoft.com/en-us/download/details.aspx?id=47442) 更新

### 捐赠：
- [比特币](https://www.blockchain.com/btc/address/1LrRTXPsvHcQWCNZotA9RcwjsGcRghG96c) (BTC)
- [以太坊](https://www.blockchain.com/explorer/addresses/eth/0xe2C84A62eb2a4EF154b19bec0c1c106734B95960) (ETH)
- [Yandex Money](https://yoomoney.ru/to/4100115776040583) (RUB)
- [Paypal](https://paypal.me/henrypp) (USD)

### 二进制签名：
上游发布版会在应用目录中包含名为 `memreduct.exe.sig` 的 GPG 签名文件。

本分支本地重新编译的二进制不会匹配上游签名文件。

- 公钥: [pubkey.asc](https://raw.githubusercontent.com/henrypp/builder/master/pubkey.asc) ([pgpkeys.eu](https://pgpkeys.eu/pks/lookup?op=index&fingerprint=on&search=0x5635B5FD))
- Key ID: 0x5635B5FD
- 指纹: D985 2361 1524 AB29 BE73 30AC 2881 20A7 5635 B5FD

---

- Fork 仓库: [github.com/weilonghua/memreduct](https://github.com/weilonghua/memreduct)
- 上游项目: [github.com/henrypp/memreduct](https://github.com/henrypp/memreduct)
- 支持: 通过本仓库 GitHub issues

---

(c) 2011-2026 Henry++
