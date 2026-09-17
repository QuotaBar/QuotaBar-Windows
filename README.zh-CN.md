<div align="center">

<img src="Assets/icon.png" alt="QuotaBar" width="112" height="112">

# QuotaBar for Windows

**每个 AI 编码额度，抬眼就看见——在系统托盘。**

[![状态](https://img.shields.io/badge/%E7%8A%B6%E6%80%81-%E5%BC%80%E5%8F%91%E4%B8%AD-black)](#状态)
[![许可证](https://img.shields.io/badge/%E8%AE%B8%E5%8F%AF%E8%AF%81-MIT-black)](LICENSE)

[macOS 版](https://github.com/QuotaBar/QuotaBar) ·
[官网](https://quota.bar)

[English](README.md) · **简体中文**

</div>

## 状态

开发中，尚未发布。现在可以使用的是
[QuotaBar macOS 版](https://github.com/QuotaBar/QuotaBar/releases/latest)。

## 功能

QuotaBar 显示各家 AI 编码服务的额度用了多少、每个窗口什么时候重置，以及大致花了多少钱，
支持 Claude、Codex、Gemini、Cursor、Grok 等。所有数据都在你自己的电脑上读取和计算，
无需账号，不收集遥测。

## 与 macOS 版的关系

这是一个独立的代码库，使用 Windows 原生技术开发。各服务商的读取与解析逻辑以 macOS 版的
[`Sources/QuotaCore`](https://github.com/QuotaBar/QuotaBar/tree/main/Sources/QuotaCore)
为参考实现，Quota Run 遵循
[`docs/quota-run.md`](https://github.com/QuotaBar/QuotaBar/blob/main/docs/quota-run.md)
中的接口约定。

## 许可证

[MIT](LICENSE)
