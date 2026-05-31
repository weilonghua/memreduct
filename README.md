<h1 align="center">Mem Reduct</h1>

<p align="center">
	<a href="https://github.com/weilonghua/memreduct/releases"><img src="https://img.shields.io/github/v/release/weilonghua/memreduct?style=flat-square&include_prereleases&label=version" /></a>
	<a href="https://github.com/weilonghua/memreduct/releases"><img src="https://img.shields.io/github/downloads/weilonghua/memreduct/total.svg?style=flat-square" /></a>
	<a href="https://github.com/weilonghua/memreduct/issues"><img src="https://img.shields.io/github/issues-raw/weilonghua/memreduct.svg?style=flat-square&label=issues" /></a>
	<a href="https://github.com/weilonghua/memreduct/graphs/contributors"><img src="https://img.shields.io/github/contributors/weilonghua/memreduct?style=flat-square" /></a>
	<a href="https://github.com/weilonghua/memreduct/blob/master/LICENSE"><img src="https://img.shields.io/github/license/weilonghua/memreduct?style=flat-square" /></a>
</p>

-------

> Public fork maintained by weilonghua.
> Based on Henry++ Mem Reduct with local stability, async cleanup, and build compatibility changes.

<p align="center">
	<img src="/images/memreduct.png?cachefix" />
</p>

### Description:
Lightweight real-time memory management application to monitor
and clean system memory on your computer.

This fork keeps the original utility and adds local cleanup-flow stability fixes, async UI handling, and build compatibility updates.

The program uses undocumented internal system features (Native API) to clear system cache (system working set, working set, standby page lists, modified page lists) with variable result ~10-50%. Application it is compatible with <s>Windows XP SP3</s> Windows 7 SP1 and higher operating systems.

You can download either the installer or portable version. For correct working you are required to have administrator rights.

```
To activate portable mode, create "memreduct.ini" in application folder, or move it from "%APPDATA%\Henry++\Mem Reduct".
```

### System requirements:
- Windows 7, 8, 8.1, 10, 11 64-bit/ARM64
- An SSE2-capable CPU
- <s>KB2533623</s> [KB3063858](https://www.microsoft.com/en-us/download/details.aspx?id=47442) update for Windows 7 was required

### Donate:
- [Bitcoin](https://www.blockchain.com/btc/address/1LrRTXPsvHcQWCNZotA9RcwjsGcRghG96c) (BTC)
- [Ethereum](https://www.blockchain.com/explorer/addresses/eth/0xe2C84A62eb2a4EF154b19bec0c1c106734B95960) (ETH)
- [Yandex Money](https://yoomoney.ru/to/4100115776040583) (RUB)
- [Paypal](https://paypal.me/henrypp) (USD)

### Binary signature:
Upstream release binaries have a GPG signature file named `memreduct.exe.sig` in the application folder.

Locally rebuilt binaries from this fork do not match the upstream signature file.

- Public key: [pubkey.asc](https://raw.githubusercontent.com/henrypp/builder/master/pubkey.asc) ([pgpkeys.eu](https://pgpkeys.eu/pks/lookup?op=index&fingerprint=on&search=0x5635B5FD))
- Key ID: 0x5635B5FD
- Fingerprint: D985 2361 1524 AB29 BE73 30AC 2881 20A7 5635 B5FD
---
- Fork repository: [github.com/weilonghua/memreduct](https://github.com/weilonghua/memreduct)
- Upstream project: [github.com/henrypp/memreduct](https://github.com/henrypp/memreduct)
- Support: GitHub issues in this fork
---
(c) 2011-2026 Henry++
